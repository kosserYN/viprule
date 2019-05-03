# VIP解析规则
Ctrl + C，Ctrl + V，自定义规则。

<pre><code>

|http://v.youku.com/v_show/*$s@</head>@<script src="https://raw.githubusercontent.com/voltachan/viprule/master/vip.js"></script></head>@
|http://v.youku.com/v_show/*$s@</body>@<script>insVIP('fns','player');</script></body>@
||v.youku.com/v_show/*###player:not([style])>iframe{height:calc(100% - 50px)}csshack
|http://www.tudou.com/albumplay/*.html$s@</head>@<script src="https://raw.githubusercontent.com/voltachan/viprule/master/vip.js"></script></head>@
|http://www.tudou.com/albumplay/*.html$s@</body>@<script>insVIP('tab_nav fix','player');</script></body>@
|http://www.tudou.com/albumplay/*.html##.tab_nav.fix select{margin-top:11px;font-size: 15px}csshack
|http://www.iqiyi.com/v_*$s@</head>@<script src="https://raw.githubusercontent.com/voltachan/viprule/master/vip_iqiyi.js"></script></head>@
|http://www.iqiyi.com/v_*$s@</body>@<script>insVIP('mod-play-tit','flashbox');</script></body>@
|http://www.iqiyi.com/v_*##div[style*="absolute"][style*="visibility"]
|http://www.le.com/$s@</head>@<script src="https://raw.githubusercontent.com/voltachan/viprule/master/vip.js"></script></head>@
|http://www.le.com/$s@</body>@<script>insVIP('j-video-name video-name','fla_box');</script></body>@
||sohu.com/crossdomain.xml$c
||https://sohu.com/album/$s@</head>@<script src="https://raw.githubusercontent.com/voltachan/viprule/master/vip.js"></script></head>@
||https://sohu.com/album/$s@</body>@<script>insVIP('player-content-info','playerWrap');</script></body>@
||https://sohu.com/album/##.player-content-info>select{margin-top:20px;font-size: 15px}csshack
|https://v.qq.com/x/*.html*$s@</head>@<script src="https://raw.githubusercontent.com/voltachan/viprule/master/vip_qq.js"></script></head>@
|https://v.qq.com/x/*.html*$s@</body>@<script>insVIPssl('action_wrap cf','tenvideo_player');</script></body>@
|https://v.qq.com/x/*.html*##[class="action_wrap cf"]>select{margin-top:18px}[class="action_item action_count"] .icon_text
|https://www.mgtv.com/b/*$s@</head>@<script src="https://raw.githubusercontent.com/voltachan/viprule/master/vip.js"></script></head>@
|https://www.mgtv.com/b/*$s@</body>@<script>insVIP("v-panel-count","mgtv-player-wrap");</script></body>@

</code></pre>
