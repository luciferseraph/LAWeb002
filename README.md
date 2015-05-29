article,aside,details,figcaption,figure,footer,header,main,nav,section {
    display: block;
}

audio,canvas,video {
    display: inline-block;
    *display: inline;
    *zoom: 1;
}

audio:not([controls]) {
    display: none;
    height: 0;
}

[hidden] {
    display: none;
}

html {
    font-size: 100%;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%;
}

a:focus {
    outline: thin dotted #333;
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px;
}

a:hover,a:active {
    outline: 0;
}

b,strong {
    font-weight: bold;
}

small {
    font-size: 80%;
}

sub,sup {
    position: relative;
    font-size: 75%;
    line-height: 0;
    vertical-align: baseline;
}

sup {
    top: -0.5em;
}

sub {
    bottom: -0.25em;
}

img {
    width: auto\9;
    height: auto;
    vertical-align: middle;
    border: 0;
    -ms-interpolation-mode: bicubic;
}

form {
    margin: 0;
}

button,input,select,textarea {
    font-size: 100%;
    margin: 0;
    vertical-align: baseline;
    *vertical-align: middle;
}

button,input {
    line-height: normal;
}

button,html input[type="button"],input[type="reset"],input[type="submit"] {
    -webkit-appearance: button;
    cursor: pointer;
    *overflow: visible;
}

button[disabled],html input[disabled] {
    cursor: default;
}

input[type="checkbox"],input[type="radio"] {
    box-sizing: border-box;
    padding: 0;
    *height: 13px;
    *width: 13px;
}

input[type="search"] {
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
    -webkit-appearance: textfield;
}

input[type="search"]::-webkit-search-decoration,input[type="search"]::-webkit-search-cancel-button {
    -webkit-appearance: none;
}

button::-moz-focus-inner,input::-moz-focus-inner {
    border: 0;
    padding: 0;
}

textarea {
    overflow: auto;
    vertical-align: top;
}

table {
    border-collapse: collapse;
    border-spacing: 0;
}

.xm-side {
    width: 230px;
    float: left;
    _display: inline;
    min-height: 1px;
}

.xm-box {
    margin-bottom: 10px;
    background: #fff;
    _zoom: 1;
    border-radius: 5px;
}

.xm-box .hd {
    height: 50px;
    border-bottom: 1px solid #ddd;
}

.xm-box .hd .title {
    float: left;
    padding-left: 1px;
    font: 400 18px/50px arial,"Hiragino Sans GB","Microsoft YaHei",SimHei,sans-serif;
    color: #000;
}

.xm-content {
    width: 990px;
    float: left;
    _display: inline;
    min-height: 1px;
    margin-left: 10px;
    -webkit-transition: width 1s;
    -moz-transition: width 1s;
    -o-transition: width 1s;
    transition: width 1s;
}

.xm-goods-sublist {
    margin: 0;
    _margin-bottom: -4px;
    padding: 0;
    list-style-type: none;
}

.xm-goods-sublist li {
    position: relative;
    border-bottom: 1px solid #ededed;
    _zoom: 1;
}

.xm-goods-sublist li .item-name {
    width: 100%;
    white-space: nowrap;
    text-overflow: ellipsis;
    overflow: hidden;
}

.xm-goods-sublist li .item-price {
    color: #434a54;
}

.xm-goods-sublist li .item-thumb {
    position: absolute;
    top: 8px;
    width: 60px;
    height: 60px;
}

.xm-goods-sublist li .item-thumb a img {
    width: 60px;
    height: 60px;
}

.xm-goods-sublist-l li {
    padding: 18px 18px 18px 80px;
}

.xm-goods-sublist-l li .item-thumb {
    left: 8px;
}

@media screen and (min-width: 1px) and (max-width: 1260px) {
    .xm-content {
        width: 690px;
    };
}

.container-fluid {
    padding-right: 10px;
    padding-left: 10px;
    *zoom: 1;
}

.container-fluid:before,.container-fluid:after {
    display: table;
    content: "";
    line-height: 0;
}

.container-fluid:after {
    clear: both;
}

a {
    color: #6d6d6d;
    text-decoration: none;
}

a:hover,a:focus {
    color: #ff6f3d;
    text-decoration: none;
}

.img-rounded {
    -webkit-border-radius: 6px;
    -moz-border-radius: 6px;
    border-radius: 6px;
}

.img-polaroid {
    padding: 4px;
    background-color: #fff;
    border: 1px solid #ccc;
    border: 1px solid rgba(0,0,0,0.2);
    -webkit-box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    -moz-box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

menu,ol,ul,li {
    list-style: none;
}

body,input,button,textarea,select,option,optgroup {
    font-size: 14px;
    line-height: 20px;
}

body,h1,h2,h3,h4,h5,h6,blockquote,p,pre,dl,dd,menu,ol,ul,caption,th,td,form,fieldset,legend,input,button,textarea {
    margin: 0;
    padding: 0;
}

h1,h2,h3,h4,h5,h6 {
    font-size: 100%;
}

.img-circle {
    -webkit-border-radius: 500px;
    -moz-border-radius: 500px;
    border-radius: 500px;
}

.clearfix {
    *zoom: 1;
}

.clearfix:before,.clearfix:after {
    display: table;
    content: "";
    line-height: 0;
}

.clearfix:after {
    clear: both;
}

.hide {
    display: none;
}

.close {
    float: right;
    font-size: 20px;
    font-weight: bold;
    line-height: 1.5;
    color: #FFFFFF;
    text-shadow: 0 1px 0 #fff;
    opacity: 0.2;
}

.close:hover,.close:focus {
    color: #000;
    text-decoration: none;
    cursor: pointer;
    opacity: 0.4;
}

.btn {
    display: inline-block;
    *display: inline;
    *zoom: 1;
    margin-bottom: 0;
    font-size: 14px;
    height: 38px;
    line-height: 38px;
    text-align: center;
    cursor: pointer;
    background-color: #fff;
    border: 1px solid #e6e9ed;
    color: #6d6d6d;
    padding: 0;
    width: 140px;
}

.btn:hover,.btn:focus {
    color: #6d6d6d;
    text-decoration: none;
    background-color: #fff;
}

.btn:focus {
    outline: thin dotted #333;
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px;
}

.btn.active,.btn:active {
    outline: 0;
    background-color: #f5f7fa;
    -webkit-box-shadow: inset 0 2px 4px rgba(0,0,0,.15);
    -moz-box-shadow: inset 0 2px 4px rgba(0,0,0,.15);
    box-shadow: inset 0 2px 4px rgba(0,0,0,.15);
}

.btn.disabled,.btn[disabled] {
    cursor: default;
    opacity: 0.65;
    -webkit-box-shadow: none;
    -moz-box-shadow: none;
    box-shadow: none;
    color: #e5e9ec;
    background: #ccd0d9;
}

.btn-block {
    display: block;
    width: 100%;
    padding-left: 0;
    padding-right: 0;
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
}

.btn-primary {
    background-color: #ee330a;
    border: 0;
    color: #fff;
}

.btn-primary:hover,.btn-primary:focus {
    color: #fff;
    background-color: #ff4a00;
}

.btn-primary.active,.btn-primary:active {
    background-color: #cb2e3c;
}

.btn-white {
    background-color: #fff;
}

.btn-white:hover,.btn-white:focus {
    color: #333;
    background-color: #e0e0e0;
}

.btn-white.active,.btn-white:active {
    background-color: #e0e0e0;
}

.btn-green {
    background-color: #85c143;
    border: 0;
    color: #fff;
}

.btn-green:hover,.btn-green:focus {
    color: #fff;
    background-color: #8cc84d;
}

.btn-green.active,.btn-green:active {
    background-color: #7cb83a;
}

.btn-blue {
    background-color: #4b89dc;
    border: 0;
    color: #fff;
}

.btn-blue:hover,.btn-blue:focus {
    color: #fff;
    background-color: #5d9cec;
}

.btn-blue.active,.btn-blue:active {
    background-color: #4682d3;
}

.btn-purple {
    background-color: #967adc;
    border: 0;
    color: #fff;
}

.btn-purple:hover,.btn-purple:focus {
    color: #fff;
    background-color: #a084e4;
}

.btn-purple.active,.btn-purple:active {
    background-color: #8b6fd1;
}

.btn-red {
    background-color: #ed5567;
    border: 0;
    color: #fff;
}

.btn-red:hover,.btn-red:focus {
    color: #fff;
    background-color: #f86072;
}

.btn-red.active,.btn-red:active {
    background-color: #e14d5e;
}

.btn-dake {
    background-color: #656d78;
    border: 0;
    color: #fff;
}

.btn-dake:hover,.btn-dake:focus {
    color: #fff;
    background-color: #717984;
}

.btn-dake.active,.btn-dake:active {
    background-color: #5a606c;
}

.btn-dakeLight {
    background-color: #ccd0d8;
    border: 0;
    color: #fff;
}

.btn-dakeLight:hover,.btn-dakeLight:focus {
    color: #fff;
    background-color: #d2d5dc;
}

.btn-dakeLight.active,.btn-dakeLight:active {
    background-color: #c6cad3;
}

.btn-small {
    height: 30px;
    line-height: 30px;
    width: 110px;
    font-size: 12px;
}

.btn-round {
    height: 24px;
    line-height: 24px;
    width: 105px;
    font-size: 12px;
    -webkit-border-radius: 12px;
    -moz-border-radius: 12px;
    border-radius: 12px;
}

.icon-common {
    display: inline-block;
    *display: inline;
    *zoom: 1;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/main/icon-common-newyear.png?2013122401");
    background-repeat: no-repeat;
}

.icon-common-logo {
    width: 145px;
    height: 62px;
    background-position: 0 0;
}

.icon-common-face {
    width: 28px;
    height: 27px;
    background-position: -148px 0;
}

.icon-common-tel {
    width: 31px;
    height: 22px;
    background-position: -177px -5px;
}

.icon-common-cart {
    width: 16px;
    height: 13px;
    background-position: -212px 0px;
}

.icon-common-carthover {
    width: 16px;
    height: 13px;
    background-position: -294px -53px;
}

.icon-common-sina {
    width: 22px;
    height: 17px;
    background-position: -458px -2px;
}

.icon-common-sina:hover {
    background-position: -485px -2px;
}

.icon-common-kongjian {
    width: 22px;
    height: 17px;
    background-position: -459px -24px;
}

.icon-common-kongjian:hover {
    background-position: -485px -23px;
}

.icon-common-weixin {
    width: 22px;
    height: 17px;
    background-position: -462px -51px;
}

.icon-common-weixin:hover {
    background-position: -486px -51px;
}

.icon-common-add {
    width: 20px;
    height: 20px;
    background-position: -305px -12px;
}

.icon-common-negative {
    width: 20px;
    height: 20px;
    background-position: -281px -12px;
}

.icon-common-nextRound {
    width: 16px;
    height: 16px;
    background-position: -359px -14px;
}

.icon-common-radio {
    width: 16px;
    height: 16px;
    background-position: -334px -51px;
}

.icon-common-radioHover {
    width: 16px;
    height: 16px;
    background-position: -354px -51px;
}

.icon-common-editGray {
    width: 22px;
    height: 20px;
    background-position: -327px -12px;
}

.icon-common-question {
    width: 16px;
    height: 16px;
    background-position: -212px -15px;
}

.icon-common-questionBg {
    width: 18px;
    height: 18px;
    background-position: -420px -48px;
}

.icon-common-questionBgHover {
    width: 18px;
    height: 18px;
    background-position: -441px -48px;
}

.icon-common-checkbox {
    width: 16px;
    height: 16px;
    background-position: -313px -51px;
}

.icon-common-grayheart {
    width: 13px;
    height: 13px;
    background-position: -232px -18px;
}

.icon-common-heart {
    width: 13px;
    height: 13px;
    background-position: -249px -18px;
}

.icon-common-arrow {
    width: 13px;
    height: 13px;
    background-position: -265px -20px;
}

.icon-common-edit {
    width: 35px;
    height: 35px;
    background-position: -146px -32px;
}

.icon-common-grid {
    width: 14px;
    height: 14px;
    background-position: -184px -32px;
}

.icon-common-right {
    width: 16px;
    height: 16px;
    background-position: -201px -32px;
}

.icon-common-pop {
    width: 15px;
    height: 14px;
    background-position: -204px -52px;
}

.icon-common-del {
    width: 16px;
    height: 17px;
    background-position: -220px -32px;
}

.icon-common-search {
    width: 17px;
    height: 18px;
    background-position: -223px -51px;
}

.icon-common-searchhover {
    width: 36px;
    height: 34px;
    background-position: -402px -12px;
}

.icon-common-plus {
    width: 15px;
    height: 15px;
    background-position: -242px -34px;
}

.icon-goods-add {
    width: 12px;
    height: 12px;
    margin: 0 3px -1px 0;
    background-image: url(//global.mifile.cn/webfile/globalimg/sg/2014/main/icon-goods-list.png?2013092302);
    background-position: -24px 0;
}

.icon-goods-add-success {
    position: relative;
    top: 2px;
    *top: 0;
    width: 16px;
    height: 16px;
    margin-right: 2px;
    background-image: url(//global.mifile.cn/webfile/globalimg/sg/2014/main/icon-goods-list.png?2013092302);
    background-position: -36px 0;
}

.icon-goods-notice {
    width: 20px;
    height: 14px;
    margin-right: 3px;
    margin-bottom: -2px;
    background-image: url(//global.mifile.cn/webfile/globalimg/sg/2014/main/icon-goods-list.png?2013092302);
    background-position: 0 -24px;
}

.icon-common-minus {
    width: 15px;
    height: 15px;
    background-position: -262px -34px;
}

.icon-common-qq {
    width: 18px;
    height: 22px;
    background-position: -242px -51px;
}

.icon-common-arrowdown {
    width: 14px;
    height: 14px;
    background-position: -263px -52px;
}

.icon-common-arrowup {
    width: 14px;
    height: 14px;
    background-position: -203px -72px;
}

.icon-common-arrowright {
    width: 14px;
    height: 14px;
    background-position: -278px -52px;
}

.icon-common-comment {
    width: 15px;
    height: 15px;
    background-position: -204px -52px;
}

.icon-common-people {
    width: 18px;
    height: 18px;
    background-position: -184px -49px;
    _background-position: -184px -47px;
}

.icon-common-close {
    width: 18px;
    height: 18px;
    background-position: -302px -32px;
}

.icon-common-close:hover {
    background-position: -281px -32px;
}

.icon-common-closehover {
    width: 18px;
    height: 18px;
    background-position: -281px -32px;
}

.icon-common-facebook {
    width: 18px;
    height: 22px;
    background-position: -378px -12px;
}

.icon-common-openbox {
    width: 17px;
    height: 10px;
    background-position: -403px 0;
}

.icon-common-global {
    width: 16px;
    height: 16px;
    background-position: -20px -65px;
}

.icon-common-globalhover {
    width: 16px;
    height: 16px;
    background-position: -1px -65px;
}

.icon-saleoff {
    display: inline-block;
    *display: inline;
    *zoom: 1;
    width: 50px;
    height: 40px;
    text-indent: -9999em;
    overflow: hidden;
    background-image: url(//global.mifile.cn/webfile/globalimg/sg/2014/main/icon-saleoff.png?140218);
    background-repeat: no-repeat;
}

.icon-saleoff-large {
    width: 76px;
    height: 60px;
}

.icon-saleoff-1 {
    background-position: -70px 0;
}

.icon-saleoff-2 {
    background-position: -140px 0;
}

.icon-saleoff-3 {
    background-position: -210px 0;
}

.icon-saleoff-4 {
    background-position: -280px 0;
}

.icon-saleoff-5 {
    background-position: -350px 0;
}

.icon-saleoff-6 {
    background-position: -420px 0;
}

.icon-saleoff-7 {
    background-position: -490px 0;
}

.icon-saleoff-8 {
    background-position: -560px 0;
}

.icon-saleoff-9 {
    background-position: -630px 0;
}

.icon-saleoff-large-1 {
    background-position: -140px -60px;
}

.icon-saleoff-large-2 {
    background-position: -235px -60px;
}

.icon-saleoff-large-3 {
    background-position: -330px -60px;
}

.icon-saleoff-large-4 {
    background-position: -425px -60px;
}

.icon-saleoff-large-5 {
    background-position: -520px -60px;
}

.icon-saleoff-large-6 {
    background-position: -615px -60px;
}

.icon-saleoff-large-7 {
    background-position: -140px -138px;
}

.icon-saleoff-large-8 {
    background-position: -235px -138px;
}

.icon-saleoff-large-9 {
    background-position: -330px -138px;
}

.icon-saleoff-specia {
    background-position: 0 0;
}

.icon-saleoff-new {
    background-position: 0 -60px;
}

.icon-saleoff-over {
    background-position: -70px -60px;
}

.icon-stat {
    display: inline-block;
    *display: inline;
    *zoom: 1;
    width: 85px;
    height: 14px;
    text-indent: -9999em;
    overflow: hidden;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/main/icon-stat.png");
    background-repeat: no-repeat;
}

.icon-stat-5 {
    background-position: 0 1px;
}

.icon-stat-4half {
    background-position: 0 -15px;
}

.icon-stat-4 {
    background-position: 0 -29px;
}

.icon-stat-3half {
    background-position: 0 -45px;
}

.icon-stat-3 {
    background-position: 0 -59px;
}

.icon-stat-2half {
    background-position: 0 -74px;
}

.icon-stat-2 {
    background-position: 0 -89px;
}

.icon-stat-1half {
    background-position: 0 -104px;
}

.icon-stat-1 {
    background-position: 0 -119px;
}

.icon-stat-half {
    background-position: 0 -133px;
}

.icon-stat-0 {
    background-position: 0 -149px;
}

.icon-slides {
    display: inline-block;
    *display: inline;
    *zoom: 1;
    width: 41px;
    height: 69px;
    text-indent: -9999em;
    overflow: hidden;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/main/icon-slides.png");
    background-repeat: no-repeat;
    _filter: alpha(opacity=40);
}

.icon-slides:hover {
    opacity: 0.6;
}

.icon-slides:focus {
    outline: 0;
}

.icon-slides-prev {
    background-position: -84px center;
}

.icon-slides-prev:hover {
    background-position: 0 center;
}

.icon-slides-next {
    background-position: -125px center;
}

.icon-slides-next:hover {
    background-position: -42px center;
}

.modal-backdrop {
    position: fixed !important;
    _position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1040;
    background-color: #000;
}

.modal-backdrop.fade {
    opacity: 0;
}

.modal-backdrop {
    opacity: 0.2;
}

.modal {
    position: fixed !important;
    top: 50%;
    left: 50%;
    z-index: 1050;
    width: 560px;
    margin-left: -280px;
    margin-top: -200px;
    _position: absolute;
    _top: 30%;
    background-color: #fff;
    -webkit-border-radius: 6px;
    -moz-border-radius: 6px;
    border-radius: 6px;
    -webkit-box-shadow: 0 3px 7px rgba(0,0,0,0.3);
    -moz-box-shadow: 0 3px 7px rgba(0,0,0,0.3);
    box-shadow: 0 3px 7px rgba(0,0,0,0.3);
    -webkit-background-clip: padding-box;
    -moz-background-clip: padding-box;
    background-clip: padding-box;
    outline: none;
}

.modal.fade {
    -webkit-transition: e("opacity .3s linear, top .3s ease-out");
    -moz-transition: e("opacity .3s linear, top .3s ease-out");
    -o-transition: e("opacity .3s linear, top .3s ease-out");
    transition: e("opacity .3s linear, top .3s ease-out");
    top: -25%;
}

.modal-header {
    padding: 9px 15px;
    border-bottom: 1px solid #eee;
}

.modal-header .close {
    margin-top: 2px;
    cursor: pointer;
}

.modal-header .modalclose {
    margin-top: 2px;
    cursor: pointer;
    float: right;
    _display: inline;
    font-size: 20px;
    font-weight: bold;
    line-height: 20px;
    color: #000;
    text-shadow: 0 1px 0 #fff;
    opacity: 0.2;
}

.modal-header h3 {
    margin: 0;
    line-height: 30px;
}

.modal-body {
    position: relative;
    max-height: 400px;
    padding: 15px;
}

.modal-body .text {
    text-align: center;
}

.modal-body .text a.btn-primary {
    margin-top: 40px;
    margin-right: 40px;
}

.modal-form {
    margin-bottom: 0;
}

.modal-footer {
    padding: 14px 15px 15px;
    margin-bottom: 0;
    text-align: right;
    background-color: #f5f5f5;
    border-top: 1px solid #ddd;
    -webkit-border-radius: 0 0 6px 6px;
    -moz-border-radius: 0 0 6px 6px;
    border-radius: 0 0 6px 6px;
    -webkit-box-shadow: inset 0 1px 0 #fff;
    -moz-box-shadow: inset 0 1px 0 #fff;
    box-shadow: inset 0 1px 0 #fff;
    *zoom: 1;
}

.modal-footer:before,.modal-footer:after {
    display: table;
    content: "";
    line-height: 0;
}

.modal-footer:after {
    clear: both;
}

.modal-footer .btn+.btn {
    margin-left: 5px;
    margin-bottom: 0;
}

.modal-footer .btn-group .btn+.btn {
    margin-left: -1px;
}

.modal-footer .btn-block+.btn-block {
    margin-left: 0;
}

.xmSlide {
    overflow: hidden;
    position: relative;
}

.xmSlide-pagination {
    display: none;
}

.xmSlide-navigation {
    display: none;
    position: absolute;
    top: 0;
    height: 100%;
    z-index: 1000;
}

.xmSlide-previous {
    left: 0;
}

.xmSlide-next {
    right: 0;
}

.mileftnav .span3 {
    margin-top: 580px;
}

body {
    line-height: 20px;
    font-family: "Lucida Grande","Lucida Sans Unicode",Helvetica,Arial,Verdana,sans-serif;
}

.container {
    width: 1240px;
    margin: 0 auto;
    -webkit-transition: width 1s;
    -moz-transition: width 1s;
    -o-transition: width 1s;
    transition: width 1s;
}

.clearfix {
    *zoom: 1;
}

.clearfix:after {
    content: "\0020";
    display: block;
    height: 0;
    clear: both;
    overflow: hidden;
    visibility: hidden;
}

.focus {
    height: 550px;
}

.focus a {
    display: none;
    height: 550px;
    overflow: hidden;
}

.focus .xmSlide {
    position: relative;
}

.focus .xmSlide_01 {
    height: 550px;
}

.focus .xmSlide_note {
    height: 550px;
}

.focus .xmSlide_03 {
    height: 550px;
}

.focus .xmSlide_powerbank {
    height: 550px;
}

.focus .xmSlide-pagination {
    position: relative;
    display: block;
    *display: none;
    top: -30px;
    height: 0;
    text-align: center;
    z-index: 1000;
}

.focus .xmSlide-pagination li {
    display: inline-block;
    width: 10px;
    height: 10px;
    margin: 0 5px;
}

.focus .xmSlide-pagination li a {
    display: block;
    width: 8px;
    height: 8px;
    border: 1px solid #434A54;
    border-radius: 50%;
    text-indent: -9999px;
    overflow: hidden;
}

.focus .xmSlide-pagination li a.active {
    background-color: #434A54;
}

.focus .xmSlide-control {
    overflow: hidden;
}

.focus .xmSlide-navigation {
    position: absolute;
    display: block;
    top: 230px;
    width: 24px;
    height: 47px;
    background: url("//global.mifile.cn/webfile/globalimg/sg/2014/main/focus_arrow.png?150414") no-repeat;
    text-indent: -9999px;
    z-index: 1000;
}

.focus .xmSlide-navigation.xmSlide-previous {
    left: 10px;
    background-position: left top;
}

.focus .xmSlide-navigation.xmSlide-next {
    right: 10px;
    background-position: right top;
}

.info_content {
    width: 960px;
    margin: 0 auto;
    overflow: hidden;
}

.info_content li {
    overflow: hidden;
    zoom: 1;
    position: relative;
    background-repeat: no-repeat;
    border-bottom: 1px solid #e0e0e0;
    padding-bottom: 50px;
}

.info_content li h3 {
    font-size: 28px;
    color: #666;
    line-height: 50px;
    font-weight: normal;
    margin: 0px;
    padding: 0px;
}

.info_content li p {
    font-size: 14px;
    color: #666;
    line-height: 24px;
    margin: 0px;
    padding: 0px;
}

.info_content .info_con1 {
    background: url("//global.mifile.cn/webfile/globalimg/en/2014/zt/xminfo_1.jpg") no-repeat;
}

.info_content .info_con1 .text {
    margin-top: 425px;
}

.info_content .info_con2 {
    background: url("//global.mifile.cn/webfile/globalimg/en/2014/zt/xminfo_2.jpg") 0px 50px no-repeat;
    height: 490px;
}

.info_content .info_con2 .text {
    position: absolute;
    width: 430px;
    top: 150px;
    right: 0px;
}

.info_content .info_con3 {
    background: url("//global.mifile.cn/webfile/globalimg/en/2014/zt/xminfo_3.jpg") 695px 50px no-repeat;
    height: 295px;
}

.info_content .info_con3 .text {
    position: absolute;
    width: 530px;
    top: 85px;
    left: 30px;
}

.xmEn_titImg {
    height: 530px;
    margin-top: -1px;
    background: #161515 url("//global.mifile.cn/webfile/globalimg/en/2014/zt/xmEn_3.jpg") center top no-repeat;
}

.xmEn_content {
    width: 960px;
    margin: 10px auto 0;
    overflow: hidden;
}

.xmEn_content li {
    margin-top: -1px;
    padding-top: 40px;
    border-top: 1px solid #e0e0e0;
    padding-bottom: 40px;
}

.xmEn_content li .left {
    float: left;
}

.xmEn_content li .right {
    float: left;
    margin-left: 30px;
    width: 708px;
}

.xmEn_content li .right h3 {
    font-weight: normal;
    margin: 0px;
    padding: 0px;
    font-size: 34px;
    color: #666;
    line-height: 40px;
}

.xmEn_content li .right p {
    margin: 0px;
    padding: 0px;
    font-size: 14px;
    color: #666;
    line-height: 24px;
}

.xmEn_content .creator1 .right h3 {
    margin-top: 30px;
}

.xmEn_content .creator1 .right p {
    margin-top: 55px;
}

.xmEn_content .creator2 .right p {
    margin-top: 20px;
}

.xmEn_content .creator3 .right p {
    margin-top: 20px;
}

.xmEn_content .creator4 .right p {
    margin-top: 20px;
}

.xmEn_content .creator5 .right p {
    margin-top: 20px;
}

.xmEn_content .creator6 .right p {
    margin-top: 20px;
}

.xmEn_content .creator7 .right p {
    margin-top: 20px;
}

.xmEn_content .creator8 .right p {
    margin-top: 20px;
}

.xmEn_content .creator9 .right p {
    margin-top: 20px;
}

.contact {
    background: #ccd1d9;
}

.contact .address {
    padding: 40px 0;
    color: #000 Light;
    overflow: auto;
}

.contact .address dl {
    float: left;
    width: 330px;
    height: 400px;
    margin: 0 0 0 62px;
    background: #fff;
    text-align: center;
    -webkit-transition: all 1s;
    -moz-transition: all 1s;
    -o-transition: all 1s;
    transition: all 1s;
}

.contact .address dl.address_hk {
    background: #fff url("//global.mifile.cn/webfile/globalimg/sg/2014/main/address_hk.jpg") center top no-repeat;
}

.contact .address dl.address_sg {
    background: #fff url("//global.mifile.cn/webfile/globalimg/sg/2014/main/address_sg.jpg") center top no-repeat;
}

.contact .address dl.address_tw {
    background: #fff url("//global.mifile.cn/webfile/globalimg/sg/2014/main/address_tw.jpg") center top no-repeat;
}

.contact .address dt {
    line-height: 24px;
    margin-top: 230px;
    margin-bottom: 16px;
    font-size: 18px;
}

.contact .address dd {
    line-height: 18px;
    width: 230px;
    margin: 6px auto;
    font-size: 14px;
}

.contact .address a {
    color: #656D78;
}

.contact .address a:hover {
    color: #ff6f3d;
}

.hide,.block_hide {
    display: none;
}

.site-topbar {
    *position: relative;
    *z-index: 11;
    height: 36px;
    border-bottom: 1px solid #dfdfdf;
    font-size: 12px;
    line-height: 36px;
    color: #6d6d6d;
    background: #fafafa;
}

.site-topbar a {
    color: #6d6d6d;
}

.site-topbar a:hover,.site-topbar a.current {
    color: #333;
}

.site-topbar .sep {
    margin: 0 10px;
    color: #dfdfdf;
}

.site-topbar .topbar-nav {
    float: left;
    _width: 630px;
}

.site-topbar .topbar-info {
    position: relative;
    float: right;
    _width: 400px;
    padding: 10px 74px 0 0;
    line-height: 1.5;
    text-align: right;
}

.site-topbar .topbar-info.mini {
    padding-right: 0;
}

.site-topbar .topbar-info .out {
    margin-left: 7px;
}

.site-topbar .topbar-info .arrow {
    display: inline-block;
    *display: inline;
    *zoom: 1;
    width: 0;
    height: 0;
    _font-size: 0;
    _line-height: 1;
    margin-left: 3px;
    border-width: 5px;
    border-style: solid;
    border-color: #6d6d6d transparent transparent;
    _border-color: #6d6d6d #e6e9ed #e6e9ed;
    vertical-align: middle;
}

.site-topbar .topbar-info .user-info-menu {
    display: none;
    position: absolute;
    right: 136px;
    top: 36px;
    z-index: 30;
    width: 136px;
    padding: 9px 0 10px;
    border: 1px solid #dfdfdf;
    font-size: 12px;
    line-height: 1.5;
    text-align: left;
    background: #fff;
}

.site-topbar .topbar-info .user-info-menu ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

.site-topbar .topbar-info .user-info-menu li a {
    display: block;
    padding: 6px 20px;
    color: #333;
}

.site-topbar .topbar-info .user-info-menu li a:hover {
    background: #ccd1d9;
}

.site-topbar .topbar-info .user-info-menu .menu-arrow {
    position: absolute;
    left: 50%;
    top: -7px;
    width: 30px;
    height: 7px;
    margin-left: -15px;
    _font-size: 0;
    background: url(//global.mifile.cn/webfile/globalimg/zh/2014/icon/user-menu-arrow.png) no-repeat 50% 0;
}

.site-topbar .container {
    width: 1240px;
}

.user-shop {
    position: absolute;
    right: 0;
    top: 0;
    color: #333;
    width: 86px;
    height: 37px;
    line-height: 36px;
    display: inline-block;
    border: 1px solid transparent;
    border-width: 0 1px;
    text-align: center;
    font-size: 12px;
}

.user-shop:after {
    content: '|';
    position: absolute;
    right: 0;
    top: 0;
    color: #dfdfdf;
    width: 1px;
}

.user-shop a {
    padding-right: 3px;
    display: block;
}

.user-shop .shop-car {
    vertical-align: middle;
}

.user-shop .number b {
    font-weight: normal;
}

.mini-cart-on {
    background-color: #fff;
    border-color: transparent #ff6f3d #fff;
    z-index: 41;
}

.mini-cart-on:after {
    content: '';
}

.mini-cart-list {
    width: 295px;
    position: absolute;
    top: 36px;
    _top: 32px;
    right: 0;
    border: 1px solid #ff6f3d;
    padding-left: 20px;
    padding-right: 20px;
    background: #fff;
    text-align: left;
    font-size: 12px;
    z-index: 40;
    *zoom: 1;
}

.mini-cart-list ul,.mini-cart-list li {
    margin: 0;
    padding: 0;
    list-style: none;
}

.mini-cart-list li {
    display: block;
    height: 60px;
    padding-top: 10px;
    padding-bottom: 10px;
    border-bottom: 1px solid #ededed;
    zoom: 1;
    _overflow: hidden;
    _float: left;
    position: relative;
}

.mini-cart-list li .pic,.mini-cart-list li .name,.mini-cart-list li .price {
    float: left;
}

.mini-cart-list li .pic img {
    width: 60px;
    height: 60px;
}

.mini-cart-list li .name,.mini-cart-list li .price {
    line-height: 20px;
    margin-top: 10px;
}

.mini-cart-list li .name {
    width: 110px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
}

.mini-cart-list li .icon-common-close {
    position: absolute;
    cursor: pointer;
    top: 20px;
    right: 0px;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/icon/common/iconAll.png?140419");
    background-position: -97px -90px;
}

.mini-cart-list li .icon-common-close:hover {
    background-position: -80px -93px;
}

.mini-cart-list li em {
    font-style: normal;
}

.mini-cart-list .count {
    padding: 20px 15px;
    text-align: right;
}

.mini-cart-list .count p {
    float: left;
    margin: 0;
    color: #c3c3c3;
    text-align: left;
}

.mini-cart-list .count em {
    font-style: normal;
    color: #ff6f3d;
}

.mini-cart-list .count strong {
    display: block;
    color: #333;
}

.mini-cart-list .count .btn {
    width: 130px;
    color: #fff;
}

.mini-cart-list .tip {
    font-size: 14px;
    text-align: center;
    padding: 20px;
    color: #aab2bd;
}

.mini-cart-list .loading {
    padding: 20px;
    color: #999;
    text-align: center;
}

.car-icon {
    display: inline-block;
    width: 25px;
    height: 22px;
    background-repeat: no-repeat;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/icon/common/iconAll.png");
    background-position: -109px -66px;
}

.logo-icon {
    display: inline-block;
    width: 50px;
    height: 50px;
    background-repeat: no-repeat;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/icon/common/iconAll.png");
    background-position: -8px -8px;
}

.header {
    background-color: #fff;
    border-bottom: 1px solid #ff4a00;
}

.header .top {
    width: 1240px;
    margin: 0 auto;
    height: 80px;
    position: relative;
    z-index: 33;
    overflow: visible;
    -webkit-transition: width 1s;
    -moz-transition: width 1s;
    -o-transition: width 1s;
    transition: width 1s;
}

.header .logo {
    position: absolute;
    top: 15px;
    left: 0px;
}

.header .nav-menu {
    float: right;
    list-style-type: none;
    display: inline-block;
    margin: 0px;
    padding: 0px;
    font-family: Helvetica,"Lucida Grande","Lucida Sans Unicode",Arial,Verdana,sans-serif;
    font-weight: 100;
}

.header .nav-menu li.nav-item {
    float: left;
    font-size: 18px;
    line-height: 70px;
    display: inline-block;
    height: 70px;
    color: #333;
    padding-top: 10px;
    text-align: center;
    position: relative;
    cursor: pointer;
}

.header .nav-menu li.nav-item a {
    display: inline-block;
    height: 70px;
}

.header .nav-menu li.nav-item a span.text {
    padding-left: 30px;
    padding-right: 30px;
    border-right: 1px solid #dfdfdf;
    -webkit-transition: all 1s;
    -moz-transition: all 1s;
    -o-transition: all 1s;
    transition: all 1s;
}

.header .nav-menu li.nav-item a span.last {
    border-right: none;
    padding-right: 0;
}

.header .nav-menu li.nav-item a span.last.right {
    padding-right: 30px;
}

.header .nav-menu li.nav-item a:hover {
    color: #ff4a00;
}

.header .nav-menu .nav-item {
    position: relative;
}

.header .nav-menu .nav-item .text {
    position: relative;
}

.header .nav-menu .nav-item .text .arrow {
    position: absolute;
    top: 50%;
    right: 11px;
    width: 7px;
    height: 10px;
    margin-top: -5px;
    background: url(http://global.mifile.cn/webfile/globalimg/en/2015/icons/arrow-down.png) 50% 50% no-repeat;
}

.header .nav-menu .nav-item .text-title {
    display: inline-block;
    height: 100%;
}

.header .nav-menu .nav-item .text-title:after {
    content: '';
    display: block;
    margin: auto;
    height: 3px;
    width: 0px;
    margin-top: -3px;
    background: transparent;
    transition: width .5s ease, background-color .5s ease;
}

.header .nav-menu .nav-item .nav-item-child {
    display: none;
    position: absolute;
    top: 80px;
    padding: 10px 30px;
    background: #ffffff;
    text-align: left;
    box-shadow: 0px 5px 20px -6px #000;
}

.header .nav-menu .nav-item .nav-item-child a {
    font-size: 16px;
}

.header .nav-menu .nav-item .left {
    left: 0;
}

.header .nav-menu .nav-item .right {
    right: 0;
}

.header .nav-menu .active {
    cursor: default;
}

.header .nav-menu .active .item-link {
    cursor: default;
    color: #ff4a00;
}

.header .nav-menu .active .item-link:hover {
    color: #ff4a00;
}

.header .nav-menu .children-list li a {
    display: block;
    height: 35px;
    line-height: 35px;
    white-space: nowrap;
}

.header .nav-menu .children-list .choosed a {
    cursor: default;
    color: #ff4a00;
}

.header .nav-menu .children-list .choosed a:hover {
    color: #ff4a00;
}

.header .nav-menu a:hover .text-title:after {
    width: 100%;
    background: #fb3107;
}

.header .user-box {
    height: 30px;
    line-height: 30px;
    float: right;
    position: relative;
    margin-top: 30px;
    background-color: #f3f3f3;
    font-size: 12px;
    *width: 312px;
}

.header .user-info {
    width: 129px;
    float: right;
    padding-left: 13px;
    padding-right: 13px;
    margin-top: 5px;
    line-height: 20px;
    color: #333;
    border-right: 1px solid #CCD1D9;
    overflow: hidden;
    position: relative;
    text-align: center;
}

.header .user-info a {
    color: #333;
}

.header .user-info .out {
    position: absolute;
    right: 13px;
}

.header .user-info .name {
    float: left;
    width: 68px;
    overflow: hidden;
    display: block;
    -o-text-overflow: ellipsis;
    text-overflow: ellipsis;
    white-space: nowrap;
    text-align: left;
}

.header .user-order {
    float: right;
    padding-left: 10px;
    padding-right: 10px;
    margin-top: 5px;
    margin-right: 75px;
    line-height: 20px;
    border-right: 1px solid #CCD1D9;
}

.header .user-order a {
    color: #333;
}

.header .head-prompt {
    height: 0;
    overflow: hidden;
    position: relative;
    background-color: #fff4c7;
    color: #ff6c00;
    -webkit-transition: height 0.5s;
    -moz-transition: height 0.5s;
    -o-transition: height 0.5s;
    transition: height 0.5s;
}

.header .head-prompt p {
    width: 1240px;
    height: 40px;
    line-height: 40px;
    margin: 0 auto;
    text-align: center;
}

.header .head-prompt .hdclose {
    width: 25px;
    height: 25px;
    display: block;
    position: absolute;
    top: 7px;
    right: 20px;
    border-radius: 12px;
    background: #ffdd8c url("//global.mifile.cn/webfile/globalimg/sg/2014/main/headclose.png") no-repeat;
    cursor: pointer;
}

.header .head-prompt.show {
    height: 40px;
}

.breadcrumbs {
    _position: relative;
    margin: 10px auto;
    font-size: 12px;
    color: #333;
}

.breadcrumbs a {
    color: #333;
    text-decoration: none;
}

.breadcrumbs a:hover {
    color: #ff6f3d;
}

.breadcrumbs .separator {
    color: #ccd1d9;
}

@media screen and (min-width: 1px) and (max-width: 1260px) {
    .header .top {
        width: 930px;
    }

    .header .head-prompt p {
        width: 930px;
    }

    .header .nav-menu li.nav-item a span.text {
        padding-left: 22px;
        padding-right: 22px;
    }

    .header .nav-menu li.nav-item a span.text.last {
        padding-right: 0;
    }

    .header .nav-menu li.nav-item a span.text.last.right {
        padding-right: 22px;
    }

    .header .nav-menu li.nav-item .nav-item-child {
        padding: 10px 22px;
    }

    .site-topbar .container {
        width: 930px;
    };
}

@media screen and (min-width: 1px) and (max-width: 930px) {
    .header {
        width: 930px;
    };
}

.footer {
    padding: 0 0px 20px;
    border-top: 1px solid #dfdfdf;
    background: #fff;
    color: #434A54;
    font-size: 12px;
    margin-top: 50px;
    border-top: 1px solid #dddddd;
    background-color: #f3f3f3;
}

.foot_container {
    width: 1240px;
    margin: 0 auto;
    padding-bottom: 82px;
    -webkit-transition: width 1s;
    -moz-transition: width 1s;
    -o-transition: width 1s;
    transition: width 1s;
}

.footerup {
    padding-top: 40px;
    padding-bottom: 30px;
}

.footercont {
    height: 120px;
}

.footercont .service {
    overflow: hidden;
}

.footercont .service dl {
    float: left;
    width: 170px;
    height: 130px;
    padding-left: 30px;
    border-right: 1px solid #dfdfdf;
    -webkit-transition: width 1s;
    -moz-transition: width 1s;
    -o-transition: width 1s;
    transition: width 1s;
}

.footercont .service dl dt {
    font-size: 14px;
    color: #333;
    line-height: 20px;
    font-weight: normal;
    margin-bottom: 10px;
}

.footercont .service dl dd {
    margin: 0px;
    padding: 0px;
    color: #6d6d6d;
    line-height: 20px;
    margin-top: 15px;
    height: 20px;
    overflow: hidden;
}

.footercont .service dl.last {
    border-right: none;
}

.footercont .hotline {
    height: 130px;
    float: right;
    text-align: center;
    padding-left: 15px;
    border-left: 1px solid #dfdfdf;
}

.footercont .hotline-top {
    line-height: 20px;
    position: relative;
}

.footercont .hotline-top .telNum {
    color: #333;
    font-size: 18px;
    line-height: 24px;
    font-weight: normal;
}

.footercont .hotline-top .info {
    color: #6d6d6d;
    margin-top: 10px;
}

.footercont .chatbtn {
    height: 30px;
    line-height: 30px;
    margin-top: 15px;
    font-size: 12px;
    background-color: #ff4a00;
}

.footerbtm {
    padding-top: 10px;
    border-top: 1px solid #dddddd;
}

.footerbtm .select {
    display: block;
    float: right;
    width: 200px;
    height: 40px;
    position: relative;
    vertical-align: middle;
}

.footerbtm .main_tar {
    position: absolute;
    font-size: 12px;
    line-height: 38px;
    color: #333;
    display: inline-block;
    width: 186px;
    height: 38px;
    background-repeat: no-repeat;
    background-position: 92% 50%;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/main/newindex/sg_10.png");
    cursor: pointer;
    z-index: 3;
    padding-left: 12px;
    border: 1px solid #dfdfdf;
    background-color: #fff;
}

.footerbtm .main_content {
    display: none;
    background-color: #fff;
    border: 1px solid #dfdfdf;
    border-bottom: 0;
    position: absolute;
    bottom: 35px;
    z-index: 5;
    left: 0;
}

.footerbtm .main_content li {
    width: 198px;
    font-size: 12px;
}

.footerbtm .main_content li a {
    display: block;
    color: #6d6d6d;
    padding-left: 12px;
    height: 30px;
    line-height: 30px;
}

.footerbtm .main_content li a:hover {
    color: #ff4a00;
}

.footerbtm .select:hover .main_tar {
    background-color: #fff;
    border: 1px solid #dfdfdf;
}

.footerbtm .select:hover .main_content {
    display: block;
}

.footerbtm .claim {
    display: block;
    float: left;
    font-size: 12px;
    color: #6d6d6d;
    line-height: 40px;
    color: #000;
}

@media screen and (min-width: 1px) and (max-width: 1260px) {
    .footer .foot_container {
        width: 930px;
    }

    .footer .foot_container .footerup .footercont .service dl {
        width: 155px;
        padding-left: 20px;
    };
}

@media screen and (min-width: 1px) and (max-width: 930px) {
    .footer {
        width: 930px;
    };
}

.get-dm-loading {
    width: 100px;
    margin-left: -50px;
    margin-top: -31px;
    text-align: center;
}

.xm-dm-queue {
    width: 700px;
    height: 400px;
    margin-left: -350px;
    margin-top: -200px;
}

.xm-dm-queue .close {
    position: absolute;
    top: 10px;
    right: 15px;
    color: #333;
    z-index: 5;
}

.xm-dm-queue .modal-body {
    text-align: center;
    padding-top: 30px;
}

.xm-dm-queue h3 {
    margin: 15px 0;
    color: #333;
    font-size: 40px;
    line-height: 1;
}

.xm-dm-queue .queue-tip {
    color: #666;
    font-size: 18px;
    line-height: 24px;
    margin: 10px 0 0;
}

.xm-dm-queue .queue-animate {
    width: 450px;
    margin: 0 auto;
    position: relative;
}

.xm-dm-queue .animate-mask {
    width: 100px;
    height: 200px;
    position: absolute;
    top: 0;
}

.xm-dm-queue .animate-mask-left {
    left: 0;
    background-image: -webkit-linear-gradient(left, #fff 20%, rgba(255,255,255,0));
    background-image: -moz-linear-gradient(left, #fff 20%, rgba(255,255,255,0));
    background-image: -o-linear-gradient(left, #fff 20%, rgba(255,255,255,0));
    background-image: -ms-linear-gradient(left, #fff 20%, rgba(255,255,255,0));
    background-image: linear-gradient(to right, #fff 20%, rgba(255,255,255,0));
}

.xm-dm-queue .animate-mask-right {
    right: 0;
    background-image: -webkit-linear-gradient(right, #fff 20%, rgba(255,255,255,0));
    background-image: -moz-linear-gradient(right, #fff 20%, rgba(255,255,255,0));
    background-image: -o-linear-gradient(right, #fff 20%, rgba(255,255,255,0));
    background-image: -ms-linear-gradient(right, #fff 20%, rgba(255,255,255,0));
    background-image: linear-gradient(to left, #fff 20%, rgba(255,255,255,0));
}

.xm-dm-queue .mitu-walk {
    width: 450px;
    height: 200px;
    margin: 10px auto 0;
    background: url("//global.mifile.cn/webfile/globalimg/en/2014/open/animate-mitu.png") repeat-x 0;
}

.xm-dm-error {
    width: 900px;
    height: 500px;
    margin-left: -450px;
    margin-top: -250px;
}

.xm-dm-error .close {
    position: absolute;
    top: 10px;
    right: 15px;
    color: #333;
    z-index: 5;
}

.xm-dm-error .modal-body {
    height: 360px;
    padding: 140px 50px 0 385px;
    background: url("//global.mifile.cn/webfile/globalimg/en/2014/open/mitu-2.png") no-repeat 5px 0;
}

.xm-dm-error h3 {
    color: #333;
    font-size: 32px;
    line-height: 1;
    padding: 0 0 20px;
    margin: 0;
}

.xm-dm-error .error-tip {
    margin: 0;
    padding-bottom: 40px;
    line-height: 28px;
    font-size: 16px;
    color: #666;
}

@media screen and (min-width: 1px) and (max-width: 1260px) {
    .container {
        width: 930px;
    };
}

.xmSlide-slide {
    height: 100%;
}

.site-topbar {
    height: auto;
    border-bottom: 0;
    position: relative;
    z-index: 34;
}

.site-topbar.store-topbar {
    height: 37px;
    background-color: #fff;
    margin-top: 10px;
}

.site-topbar .topbar-nav {
    font-size: 18px;
    color: #000;
}

.header ~ .site-topbar {
    z-index: 30;
}

.store-shop {
    border-width: 1px 1px 0;
}

.store-shop.mini-cart-on {
    border-color: #ccd1d9;
}

.store-mini-cart-list {
    border-color: #ccd1d9;
    top: 37px;
}

.user-country {
    position: absolute;
    margin-left: -107px;
    top: 0;
    width: 118px;
    height: 37px;
    line-height: 37px;
    border: 1px solid transparent;
    border-width: 1px 1px 0;
    text-align: center;
}

.user-country a {
    display: block;
}

.user-country.user-country-on {
    border-color: #ccd1d9;
    background-color: #fff;
    z-index: 31;
}

.user-country.no-country-selected {
    width: 158px;
    margin-left: -147px;
}

.icon-country {
    display: inline-block;
    width: 22px;
    height: 14px;
    vertical-align: text-top;
    background-image: url("//global.mifile.cn/webfile/globalimg/sg/2014/icon/common/country-flags.png");
    margin-left: 1em;
}

.icon-country.icon-gb {
    background-position: 0 -14px;
}

.icon-country.icon-fr {
    background-position: 0 -28px;
}

.icon-country.icon-de {
    background-position: 0 -42px;
}

.user-country-selector {
    width: 270px;
    position: absolute;
    top: 37px;
    margin-left: -299px;
    border: 1px solid #ccd1d9;
    padding: 20px;
    background: #fff;
    text-align: left;
    z-index: 30;
}

.user-country-selector .country-selector {
    line-height: 34px;
    *zoom: 1;
}

.user-country-selector .country-selector:before,.user-country-selector .country-selector:after {
    display: table;
    content: "";
    line-height: 0;
}

.user-country-selector .country-selector:after {
    clear: both;
}

.user-country-selector .site-switch {
    padding-top: 15px;
    margin-top: 15px;
    border-top: 1px solid #ccd1d9;
    line-height: 1.8em;
}

.user-country-selector .site-switch a {
    color: #ff6f3d;
}

.country-dropdown-label {
    float: left;
}

.country-dropdown {
    position: relative;
    width: 180px;
    margin: 0 auto;
    padding: 0 15px;
    line-height: 34px;
    background: #fff;
    border: 1px solid #ccd1d9;
    cursor: pointer;
    outline: none;
    -webkit-transition: all 0.3s ease-out;
    -moz-transition: all 0.3s ease-out;
    -o-transition: all 0.3s ease-out;
    transition: all 0.3s ease-out;
    float: right;
}

.country-dropdown:after {
    content: "";
    width: 0;
    height: 0;
    position: absolute;
    top: 50%;
    right: 15px;
    margin-top: -3px;
    border-width: 6px 6px 0 6px;
    border-style: solid;
    border-color: #aab2bd transparent;
    -webkit-transition: all 0.3s ease-out;
    -moz-transition: all 0.3s ease-out;
    -o-transition: all 0.3s ease-out;
    transition: all 0.3s ease-out;
}

.country-dropdown.active {
    border-bottom: none;
    background-color: #f5f7fa;
}

.country-dropdown.active:after {
    -webkit-transform: rotate(180deg);
    -moz-transform: rotate(180deg);
    -ms-transform: rotate(180deg);
    -o-transform: rotate(180deg);
    transform: rotate(180deg);
}

.country-dropdown.active .dropdown {
    border-bottom-width: 1px;
    max-height: 400px;
}

.country-dropdown .dropdown {
    position: absolute;
    top: 100%;
    left: -1px;
    right: -1px;
    background: #fff;
    border: 1px solid #ccd1d9;
    border-width: 0 1px;
    list-style: none;
    -webkit-transition: all 0.3s ease-out;
    -moz-transition: all 0.3s ease-out;
    -o-transition: all 0.3s ease-out;
    transition: all 0.3s ease-out;
    max-height: 0;
    overflow: hidden;
}

.country-dropdown .dropdown .dropdown-country {
    padding: 0 15px;
    display: block;
}

.country-dropdown .dropdown .dropdown-country:hover {
    background-color: #f5f7fa;
}

.country-dropdown .icon-country {
    margin-left: 0;
    margin-right: 1em;
}

.simple-footer {
    background-color: #fff;
    padding-top: 25px;
}

.simple-footer .footer_l {
    float: left;
}

.simple-footer .footer_l .nav {
    height: 12px;
}

.simple-footer .footer_l .nav a {
    float: left;
    line-height: 12px;
    padding: 0 15px;
    border-left: 1px solid #dfdfdf;
    color: #6d6d6d;
}

.simple-footer .footer_l .nav a:first-child {
    padding: 0 15px 0 0;
    border-left: none;
}

.simple-footer .footer_l .social {
    height: 25px;
    margin-top: 12px;
}

.simple-footer .footer_l .social a {
    float: left;
    height: 25px;
    width: 26px;
    margin: 0 5px 0 0;
    background: #8c8c8c url("//global.mifile.cn/webfile/globalimg/en/2014/comm/social_logo.png") no-repeat;
    text-indent: -9999px;
}

.simple-footer .footer_l .social a.facebook {
    background-position: left top;
}

.simple-footer .footer_l .social a.google-plus {
    background-position: center center;
}

.simple-footer .footer_l .social a.twitter {
    background-position: right center;
}

.simple-footer .footerbtm {
    padding-top: 0;
    border-top: none;
    float: right;
}

.simple-footer .footerbtm .claim {
    float: right;
    color: #6d6d6d;
    line-height: normal;
}

.simple-footer .footerbtm .select {
    clear: both;
    margin-top: 10px;
}