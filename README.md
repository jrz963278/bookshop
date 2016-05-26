# bookshop
code
Theme Name: MiTao 4.5

*/
*{margin:0;padding:0;border:0}
body{background:#f5f5f5;color:#555;font:14px Microsoft Yahei,Verdana,Arial,Helvetica,sans-serif;cursor:default;line-height:24px}
h1,h2,h3,h4,h5,h6{font-weight:bold;font-size:16px}
::selection{background:#dcdcdc;color:#08d}
::-moz-selection{background:#dcdcdc;color:#08d}
a:link,a:visited{color:#555;text-decoration:none}
a:hover{color:#08d;text-decoration:none}
.clear{clear:both}
#rss{float:right;border:0;max-width:174px}
#rss ul{list-style:none}
#rss ul li{float:right;margin:6px 0 0 14px}
.icon1,.icon1 span.hover,.icon2,.icon2 span.hover,.icon3,.icon3 span.hover,.icon4,.icon4 span.hover{display:block;width:28px;height:28px;background-image:url(images/icon.png);background-repeat:no-repeat}
.icon1{background-position:-84px 0}
.icon1 span.hover{background-position:-84px -28px}
.icon2{background-position:-56px 0}
.icon2 span.hover{background-position:-56px -28px}
.icon3{background-position:-28px 0}
.icon3 span.hover{background-position:-28px -28px}
.icon4{background-position:0 0}
.icon4 span.hover{background-position:0 -28px}
.logo{float:left;display:block;overflow:hidden;width:100px;height:40px;background:url(images/logo.png) no-repeat;font-size:15px;line-height:100px}
.logo a{display:block;overflow:hidden;height:40px;color:#fff}
.mainmenus{position:fixed;z-index:99999;width:100%;background:#222;background:#222 url(images/header_bg.png) repeat-x left bottom;height:45px;padding-top:5px}
.mainmenu{margin:0 auto;width:1108px}
.mainnav{float: left;line-height: 30px;height:30px;margin-top:5px;font-size: 15px;}
.mainnav li{float:left;position:relative;margin-right:1px;list-style:none}
.mainnav li a{color:#fff;padding:0 12px;float:left;line-height: 28px;height: 29px;font-weight:bold}
.mainnav li a:hover,.mainnav li:hover a{background-color:#000;color:#fff}
.mainnav li.current-menu-item a,.mainnav li.current-menu-parent a,.mainnav li.current_page_item a,.mainnav li.current-post-ancestor a{color:#fff;background-color:#000;position:relative;z-index:2;}
.mainnav li:hover ul{display:none}
.mainnav li ul{position:absolute;top:29px;left:0;min-width:130px;z-index:10;display:none;line-height:18px;background-color:#222;}
.mainnav li li{float:none;margin:0;position:relative}
.mainnav li li a{padding:0 10px;float:none;display:block;*min-width: 100px;}
.mainnav li li a:hover,.mainnav li li.current-menu-item a{background-color:#08d;color:#fff}
.mainnav li li ul{position:absolute;top:0;left:130px}

#content{margin:0 auto;width:1108px}
#content #map{padding-left:10px;width:610px;height:34px;border-bottom:1px #dfdfdf dashed;background:#fff;color:#777;line-height:34px}
#content #map_2{margin-bottom:10px;padding-left:10px;width:820px;height:34px;background:#fff;color:#777;line-height:34px}
#content #map h1,#content #map_2 h1{display:inline;color:#f0586c;font-size:13px}
#content #map .site,#content #map_2 .site{float:left}
#content #map a:link,#content #map a:visited,#content #map_2 a:link,#content #map_2 a:visited{color:#777;text-decoration:none}
#content #map a:hover,#content #map_2 a:hover{color:#08d;text-decoration:none}
.shopbox{float:left;margin:0 10px 10px 0;width:180px;height:253px;background:#fff;padding:10px;}
.shopbox .thumbnail{margin:0;width:180px;margin-bottom:8px;background:#fff}
.shopbox .thumbnail img{width:180px;height:180px;border:none;margin-bottom:4px}
.shopbox .thumbnail h2{overflow:hidden;height:38px;font-size:14px;font-weight:normal;line-height:20px}
.shopbox .thumbnail a:link,.shopbox .thumbnail a:visited{color:#555;display:block;}
.shopbox .thumbnail:hover h2{color:#f0586c;cursor:pointer;}
.main .shopbox .price{position:absolute;z-index:9;float:right;margin:-62px 0 0 12px;padding:0 5px;background:#fff;color:#000;font-size:12px;line-height:24px;opacity:.7}
.main .shopbox .buy{float:left;padding:0 5px;background:#f0586c;color:#fff;font-size:13px;line-height:24px;font-weight:bold}
.buy a:link,.buy a:visited{color:#fff;display: block;}
.main .shopbox a:hover span{background:#45b4eb;color:#fff;cursor:pointer}
.main .shopbox .read{float:right;padding:0 5px;background:#e6e6e6;font-size:12px;line-height:24px}
.main{float:left;width:840px}
.main ul li{list-style:none}
.main .article{margin:0px 10px 10px 0;background:#fff}
.article h2{padding:7px 0 5px 10px;font-size:13px}
.article h3{font-size:15px}
.main .article .error p{padding:4px 0 4px 15px;font-size:15px}
.main .article .error p a:link,.main .article .error p a:visited{color:#08d}
.main .article .error p a:hover{color:#777}
.main .article p.nocomments{padding:10px 15px}
.main .article_right .price{float:left;width:180px;background:#45b4eb;color:#fff;text-align:center;font-size:16px;line-height:30px;font-weight:bold;}
.main .article_right .buy{float:left;margin-bottom:5px;width:180px;background:#f0586c;color:#fff;text-align:center;font-size:16px;line-height:30px;font-weight:bold;}
.main .article_right a:hover .buy{display: block;background:#e6e6e6;color:#f0586c;cursor:pointer}
.main .article_right .shop{float:left;margin-bottom:5px;width:180px;background:#f0586c;color:#fff;text-align:center;font-size:16px;line-height:30px;font-weight:bold;}
.main .article_right a:hover .shop{display: block;background:#e6e6e6;color:#f0586c;cursor:pointer}
.main .article_right .shopbox-info{padding:10px;background:#fff}
.main .article_right .shopbox-info img{width:180px;height:180px;padding-bottom:5px}
.shopbox_roll{position:fixed;top:60px;z-index:250;width:200px;_position:absolute}
.main .entry-content{color:#777;line-height:24px}
.main .entry-content p{padding:5px 0 5px 15px;line-height:24px}
.main .entry-content a:link,.entry-content a:visited{color:#555}
.main .entry-content a:hover{color:#08d}
.main .context{position:relative;overflow:hidden;padding:5px 10px 10px 10px;color:#555}
.main .context p{margin-bottom:10px}
.main .context pre{margin:5px 0 5px 0;padding:10px 12px;border:#e6e6e6 1px solid;word-wrap:break-word;font:100 12px/18px monaco,andale mono,courier new;border-left-width:4px;word-break:break-all;white-space:pre-wrap}
.main .context blockquote{margin:5px 0 5px 0;padding:10px 10px 0 10px;border:#e6e6e6 1px solid;background:#fafafa}
.main .context blockquote img{padding:0;border:none}
.main .context ol,.main .context ul{margin:5px 0 5px 0}
.main .context ol li{margin-left:4em}
.main .context ul li{margin-left:2em}
.main .context img{clear:both;max-width:100%}
.main .context a:link,.main .context p a:link,.main .context a:visited,.main .context p a:visited{color:#08d;text-decoration:none}
.main .context a:hover,.main .context p a:hover{color:#777;text-decoration:none}
.main .context p textarea{margin-left:-2em;border:1px #ccc solid}

.main .article_head{border-bottom:1px #e6e6e6 dashed;padding:5px 10px}
.main .article_head h1{line-height:30px}
.main .article_info{color:#777;font-size:13px}
.postauthor{background: url(images/meta.png) no-repeat -9px -8px;padding-left: 18px;margin-right:15px;float:left}
.postviews{background: url(images/meta.png) no-repeat -7px -35px;padding-left: 22px;margin-right:15px;float:left}
.postcomm{background:url(images/meta.png) no-repeat -9px -64px;padding-left:18px;float:left}
.posttime{background:url(images/meta.png) no-repeat -9px -116px;padding-left:18px;float:left;margin-right:15px}
.postcat{background:url(images/meta.png) no-repeat -9px -93px;padding-left:18px;margin-right:15px;float:left;max-width:180px;height:24px;overflow:hidden;}

.main-list{background:#fff;width:830px;margin-bottom:10px}
.main-list .title{width:310px;overflow:hidden;float:left}
.main-list ul{list-style:none;padding:10px 0}
.main-list ul li{padding-bottom:2px;border-bottom:1px #e6e6e6 dashed;line-height:28px;height:28px;overflow:hidden;width:395px;float:left;margin:0 10px}
.main-list ul li a{display:block}

#article-bottom{color:#777;margin-bottom:10px;padding:10px;background:#fff}
#link{height:24px;overflow:hidden}
#article-bottom-tags{float:left;color:#777;width:500px;height:24px;overflow:hidden}
#baidushare{float:right;margin-top:-23px}
#last-page{width:45%;height:24px;overflow:hidden;float:left}
#next-page{width:45%;height:24px;overflow:hidden;float:right;text-align:right}
#article-bottom a:link,#article-bottom a:visited{color:#777;text-decoration:none}
#article-bottom a:hover{color:#08d;text-decoration:none}

.wp-caption p.wp-caption-text{margin-bottom:-0px;color:#777;text-align:center;text-indent:-0em}
img.size-auto,img.size-full,img.size-large,img.size-medium,.attachment img,.widget-container img{height:auto;max-width:100%}
.alignleft,img.alignleft{float:left;display:inline;margin-top:5px;margin-right:15px}
.alignright,img.alignright{float:right;display:inline;margin-top:5px;margin-left:15px}
.aligncenter,img.aligncenter{clear:both;display:block;margin-right:auto;margin-left:auto}
.navigation{margin:0;padding:0;border:0;text-align:right}
.pagination{margin:0 10px 10px 0;font-size:12px}
.pagination span,.pagination a{display:inline-block;margin:0 0 0 4px;width:28px;height:28px;border:1px #dfdfdf solid;background:#fff;color:#888;text-align:center;text-decoration:none;line-height:28px}
.pagination .current{width:28px;height:28px;border:1px #222 solid;border:1px #dfdfdf solid;background:#222;color:#fff}
.pagination a:hover{width:28px;height:28px;border:1px #222 solid;border:1px #dfdfdf solid;background:#222;color:#fff;text-decoration:none}
.pagination .page_previous,.pagination .prev{width:54px;height:28px;text-align:center}
.pagination .page_previous:hover,.pagination .prev:hover{width:54px;height:28px;text-align:center}
.pagination .page_next,.pagination .next,.pagination .page_next:hover,.pagination .next:hover{width:54px;height:28px;text-align:center}
.pagination .fir_las,.pagination .fir_las:hover{width:34px;height:28px;text-align:center}
.paging,.pagenav{margin:0 10px 10px 0;float:right;font-size:12px;clear:both}
.pagenav{padding-top: 16px;}
.paging a,.paging .current,.pagenav a,.pagenav .current,.paging .dots,.pagenav .page-numbers{padding:4px 12px;color:#666;border:1px solid #e6e6e6;display:block;margin-left:3px;float:left;background-color:#fff}
.paging .current,.paging a:hover,.pagenav .current,.pagenav a:hover{background-color:#222;color:#fff}
.article .navigation{float:right;margin:0 15px 5px 5px;text-align:right;font-size:12px}
.article .pagination{margin-bottom:0}
.comments-main{margin-bottom:10px;width:620px;background:#fff}
.comments-main .pagination{margin-right:15px}
.commenttitle{padding:8px 0 8px 15px}
.commentlist{padding:0 15px}
.commentlist .comment{border-top:1px #e6e6e6 dashed;list-style:none}
.commentlist li.comment ul.children{margin-left:30px}
.commentlist li.comment ul li.comment ul.children{margin-left:0}
.commentlist .depth-1{margin:0}
.commentlist li{position:relative}
.commentlist .comment-body{padding:8px 0 6px 0}
.commentlist .comment-body:hover{background:#fafafa}
.commentlist .comment-body p{margin:5px 30px 2px 56px;color:#888;line-height:22px}
.reply{font-size:12px}
.commentlist .reply a:link,.commentlist .reply a:visited{color:#777}
.commentlist .reply a:hover{color:#08d}
.datetime{margin-right:10px;color:#777;font-size:12px}
.floor{margin-right:10px;color:#777;font-size:12px}
.commentlist a:link,.commentlist a:visited{color:#08d;text-align:center}
.commentlist a:hover{color:#777;text-align:center}
.commentmetadata{margin-left:50px;color:#aaa;text-shadow:0 1px 0 #fff}
ol.commentlist li div.comment-author img.avatar{position:relative;float:left;margin:0 10px 0 0;padding:2px;width:40px;height:40px;border:1px solid #e6e6e6;background:#fff;background:#fff;-webkit-transition:.8s;-moz-transition:.8s;-o-transition:.8s;-ms-transition:.8s}
#respond_box{clear:both;padding:0 15px;border-top:1px solid #eaeaea}
#respond{overflow:hidden;padding-bottom:10px}
.article #respond h3{padding:0}
#comment{background:#fff}
.cancel-comment-reply a{color:#08d;font-size:13px}
.cancel-comment-reply a:hover{color:#777;font-size:13px}
#commentform label{color:#777}
#commentform input{margin:3px 10px 3px 0;padding:3px;width:180px;border:1px solid #ddd;font-family:Microsoft Yahei}
#commentform input:focus{border:1px solid #ccc}
#commentform #author,#commentform #email{padding:5px 5px 5px 15px}
#commentform textarea{margin-top:4px;padding:5px 15px;width:75%;height:120px;border:1px solid #ddd;font-size:13px;font-family:Microsoft Yahei}
#commentform textarea:focus{border:1px solid #ccc}
#commentform input#submit,#commentform input#reset{margin-top:8px;width:100px;height:30px;border:1px solid #ddd;background:#eaeaea;color:#555;text-align:center;font-family:Microsoft Yahei}
#commentform #submit:hover,#commentform #reset:hover{background:#ccc;color:#fff}
#real-avatar .avatar{float:right;padding:2px;border:1px solid #ddd;background:#fff}
#commentform a:link,#commentform a:visited{color:#08d;text-decoration:none}
#commentform a:hover{color:#777;text-decoration:none}
.ajaxcomm{height:30px;color:#777;line-height:30px}
#edita{padding-left:56px}
#sidebar{float:right;width:268px}
.widget{margin-bottom:10px;padding:9px;background:#fff}

.mainlist{width:390px;padding:5px 10px;background:#fff;margin:0 10px 10px 0;float:left}
.mainlist .title{width:340px;overflow:hidden;float:left;}
.mainlist ul{list-style:none}
.mainlist ul li{padding-bottom:2px;border-bottom:1px #e6e6e6 dashed;line-height:28px;height:28px;overflow:hidden}
.mainlist ul li a{display:block}
.article_right{float:right;width:200px;margin-right:10px}
.sidebarhot{width:259px;background:#fff;margin-top:-5px}
.sidebarhot .hotshopbox{float:left;margin:6px 9px 0 0;width:120px;height:120px}
.sidebarhot img{width:121px;height:121px}
.widget h3{margin-top:-3px;margin-bottom:5px}
.widget{margin-bottom:10px}
.widget ul{list-style:none}
.widget ul li{padding-bottom:2px;border-bottom:1px #e6e6e6 dashed;line-height:28px;height:28px;overflow:hidden}
.widget ul li a{display:block}
.widget .colorbar{height:auto;}
.widget .colorbar li {border-bottom:none;height:40px}
.widget .colorbar li a{display:block;padding:0 10px;color:#fff;font-size:14px;line-height:40px;border:none;}
.widget .colorbar li a:hover{opacity:0.8}
.widget .menu{width:252px}
.widget .menu li{width:124px;height:28px;line-height:30px;margin:0 2px 2px 0;text-align:center;float:left;overflow:hidden;background:#45CBC4;border:none}
.widget .menu a{color:#fff;display:block}
.widget .menu a:hover{background:#f0586c}
.widget .xoxo li{width:50%;float:left}
.widget .xoxo li a{display:block;}
.widget .w-readers{width:260px}
.widget .w-readers ul{margin-top:3px}
.widget .w-readers ul li{display:inline;padding:0;border-bottom:none;list-style:none}
.widget .w-readers ul li a{display:inline}
.widget .w-readers img.avatar{margin:2px 10px 2px 0;width:40px;height:40px;border:1px solid #e6e6e6}
.widget .w-readers img.avatar:hover{opacity:0.5}
.widget .w_comment ul li{clear:both;overflow:hidden;height:45px;line-height:22px}
.widget .w_comment ul li img.avatar{float:left;margin:3px 10px 0 0;width:40px;height:40px;border:1px solid #e6e6e6;background:#fff}
.widget .tags a{float:left;display:inline-block;margin:0 4px 4px 0;padding:5px 8px 0;height:18px;background:#f5f5f5;color:#555;line-height:14px;width:auto;white-space:nowrap}
.widget .tags a:hover{color:#fff;background:#f0586c}
input,textarea,button{outline:none}
.search{margin-bottom:10px;background:#f5f5f5}
#searchform{border:4px solid #fff;padding-left:5px}
#searchform label{display:none}
#searchform input{vertical-align:middle;height:28px;float:left;background:#f5f5f5;width:180px}
#searchform #searchsubmit{width:58px;height:28px;line-height:50;cursor:pointer;vertical-align:middle;background:#555 url(images/search.png) no-repeat 50% 50%;float:right}
#searchform #searchsubmit:hover{background:#45CBC4 url(images/search.png) no-repeat 50% 50%}
#ad-single-top{margin-bottom:10px;padding:10px;width:810px;height:80px;background:#fff}
#ad-single-top img{width:810px;height:80px}
#ad-single-bottom{margin-bottom:10px;padding:10px;width:600px;height:60px;background:#fff}
#ad-single-bottom img{width:600px;height:60px}
#roll_top{position:relative;width:50px;height:50px;cursor:pointer}
#roll_top{background:url(images/roll.png) no-repeat}
#roll_top:hover{background:url(images/roll.png) no-repeat right top}
#roll{position:fixed;top:70%;right:50%;display:block;margin-right:-610px}
#footer{padding:10px;background:#222;color:#fff;font-size:12px;line-height:22px;position:relative}
#footermain{margin:0 auto;width:1108px}
#footer a:link,#footer a:visited{color:#fff}
#footer a:hover{color:#08d}
#footer .comm1{padding-right:5px}
#footer .comm{padding-right:5px;padding-left:5px}
#footerlogo{float:right;margin-top:4px;width:100px;height:40px;background:url(images/footerlogo.png?v1.01) no-repeat}
#focusbox{margin-bottom:10px;padding:10px;width:810px;background:#fff}
#focus{position:relative;overflow:hidden;width:810px;height:280px;background:#fff}
#focus a:hover img{opacity:1}
#focus ul{position:absolute;height:380px}
#focus ul li{position:relative;float:left;overflow:hidden;width:810px;height:280px;background:#000}
#focus ul li div{position:absolute;overflow:hidden}
#focus .btnBg{position:absolute;bottom:0;left:0;width:810px;height:20px;background:#000}
#focus .btn{position:absolute;right:0;bottom:0;padding:10px 10px;height:10px;text-align:right}
#focus .btn span{display:inline-block;margin-left:5px;width:25px;height:10px;background:#000;cursor:pointer;_display:inline;_zoom:1;_font-size:0}
#focus .btn span.on{background:#fff}
#focus .preNext{position:absolute;top:90px;width:45px;height:100px;background:url(images/sprite.png) no-repeat 0 0;cursor:pointer}
#focus .pre{left:0}
#focus .next{right:0;background-position:right top}
.fancybox-wrap,.fancybox-skin,.fancybox-outer,.fancybox-inner,.fancybox-image,.fancybox-wrap iframe,.fancybox-wrap object,.fancybox-nav,.fancybox-nav span,.fancybox-tmp{margin:0;padding:0;outline:0;border:0;vertical-align:top}
.fancybox-wrap{position:absolute;top:0;left:0;z-index:8020}
.fancybox-skin{position:relative;margin-top:50px;background:#fff;color:#444;text-shadow:none}
.fancybox-opened{z-index:8030}
.fancybox-outer,.fancybox-inner{position:relative}
.fancybox-inner{overflow:hidden}
.fancybox-type-iframe .fancybox-inner{-webkit-overflow-scrolling:touch}
.fancybox-error{margin:0;padding:15px;color:#444;white-space:nowrap}
.fancybox-image,.fancybox-iframe{display:block;width:100%;height:100%}
.fancybox-image{max-width:100%;max-height:100%}
#fancybox-loading,.fancybox-close,.fancybox-prev span,.fancybox-next span{background-image:url(images/fancybox_sprite.png)}
#fancybox-loading{position:fixed;top:50%;left:50%;z-index:8060;margin-top:-22px;margin-left:-22px;background-position:0 -108px;opacity:.8;cursor:pointer}
#fancybox-loading div{width:44px;height:44px;background:url(images/fancybox_loading.gif) center center no-repeat}
.fancybox-close{position:absolute;top:-18px;right:-18px;z-index:8040;width:36px;height:36px;cursor:pointer}
.fancybox-nav{position:absolute;top:0;z-index:8040;width:40%;height:100%;background:transparent url(images/blank.gif);text-decoration:none;cursor:pointer;-webkit-tap-highlight-color:rgba(0,0,0,0)}
.fancybox-prev{left:0}
.fancybox-next{right:0}
.fancybox-nav span{position:absolute;top:50%;z-index:8040;visibility:hidden;margin-top:-18px;width:36px;height:34px;cursor:pointer}
.fancybox-prev span{left:10px;background-position:0 -36px}
.fancybox-next span{right:10px;background-position:0 -72px}
.fancybox-nav:hover span{visibility:visible}
.fancybox-tmp{position:absolute;top:-99999px;left:-99999px;visibility:hidden;overflow:visible !important;max-width:99999px;max-height:99999px}
.fancybox-lock{overflow:hidden}
.fancybox-overlay{position:absolute;top:0;left:0;z-index:8010;display:none;overflow:hidden;background:url(images/fancybox_overlay.png)}
.fancybox-overlay-fixed{position:fixed;right:0;bottom:0}
.fancybox-lock .fancybox-overlay{overflow:auto;overflow-y:scroll}
.fancybox-title{position:relative;z-index:8050;visibility:hidden;text-shadow:none}
.fancybox-opened .fancybox-title{visibility:visible}
.fancybox-title-float-wrap{position:absolute;right:50%;bottom:0;z-index:8050;margin-bottom:-35px;text-align:center}
.fancybox-title-float-wrap .child{display:inline-block;margin-right:-100%;padding:2px 20px;-webkit-border-radius:15px;-moz-border-radius:15px;border-radius:15px;background:transparent;background:rgba(0,0,0,0.8);color:#FFF;text-shadow:0 1px 2px #222;white-space:nowrap;font-weight:bold;line-height:24px}
.fancybox-title-outside-wrap{position:relative;margin-top:10px;color:#fff}
.fancybox-title-inside-wrap{padding-top:10px}
.fancybox-title-over-wrap{position:absolute;bottom:0;left:0;padding:10px;background:#000;background:rgba(0,0,0,.8);color:#fff}
#topbj-main{margin:0 auto;max-width:1108px;height:120px}
#topbj-text{float:left;margin-top:30px}
#topbj-title{font-size:22px}
#topbj-title a:link,#topbj-title a:visited{color:#555;}
#topbj-subtitle{padding-top:9px;color:#555;font-
