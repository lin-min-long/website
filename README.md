body,
html {
    display: block;
    margin: 0 auto;
    width: 100%;
    height: 100%;
    padding: 0;
    font-family: arial;
}

header {
    width: 50%;
    height: 8%;
    margin: 0 25%;
}

header h1 {
    display: inline-block;
    width: 25%;
    float: left;
}

nav {
    display: block;
    float: left;
    width: 65%;
    height: 100%;
}

.nav ul {
    margin: 0;
    padding: 0;
    float: right;
}

.nav li {
    position: relative;
    float: left;
    color: #000;
    list-style: none;
}

.nav li a {
    margin: 20px 0 0 0;
    display: block;
    padding: 15px 40px;
    color: #000;
    text-decoration: none;
}

.nav li a:hover,
#hover {
    color: #fc0;
}

.icon {
    display: block;
    float: right;
    width: 10%;
    height: 100%;
}

.icon ul {
    margin: 0;
    padding: 0;
}

.icon li {
    position: relative;
    float: left;
    color: #000;
    list-style: none;
    margin-top: 30px;
}

.toggle {
    display: none;
}

.arrow-bottom {
    position: absolute;
    top: 25px;
    right: 13px;
    margin-left: 5px;
    border-top: 4px solid #FFF;
    border-right: 4px solid transparent;
    border-left: 4px solid transparent;
    width: 1px;
    height: 1px;
}

header #icon {
    padding: 0 4px;
    display: inline-block;
}

section#main-img {
    margin: 0;
    width: 100%;
    height: 60%;
    font-family: "Microsoft JhengHei";
}

section#main-img img {
    width: 100%;
    height: 100%;
    z-index: 1;
}

.content {
    position: relative;
    z-index: 2;
    color: #fff;
    font-size: 40px;
    margin: 0 0 0 25%;
    bottom: 580px;
    font-family: "Georgia";
}

section#main-img .content p {
    position: relative;
    bottom: 40px;
    font-size: .7em;
    font-style: italic;
}

section#main-img .content ul {
    display: block;
    position: relative;
    top: -30px;
    left: -2%;
    font-size: .4em;
}

section#main-img li {
    display: inline-block;
    margin: 0 40px 0 0;
}

section#main-img a {
    color: #fff;
    text-decoration: none;
    padding: 10px 30px;
    border: 2px solid #fff;
    -webkit-transition: .3s;
    /* Safari */
    transition: .3s;
}

section#main-img li:hover a {
    color: #fc0;
    border: 2px solid #fc0;
}

article {
    display: block;
    width: 100%;
}

#section-1 {
    width: 100%;
    height: 32vh;
    background: #fc0;
    margin: 0;
    text-align: center;
}

#section-1 div {
    display: inline-block;
    margin: 50px;
    background: #fff;
    width: 100px;
    height: 100px;
    vertical-align: top;
    border-radius: 50px;
    /* Firefox, Chrome */
    line-height: 100px;
    /* IE */
    *font-size: 90px;
    /* 200px * 0.9 = 180px */
}

#section-1 img {
    vertical-align: middle;
}

#section-1 p {
    margin: 40px 0 0 0;
    font-size: 14px;
    line-height: 20px;
}

#section-2 {
    width: 100%;
    height: 80vh;
    margin: 0;
    text-align: center;
}

#section-2 h1 {
    font-size: 3em;
    text-align: left;
    font-family: "Georgia";
    margin: 0 0 0 25%;
    padding: 50px 0 0 0;
}

#section-2 h3 {
    text-align: left;
    font-family: "Georgia";
    margin: 10px 0 0 25%;
}

#section-2 div {
    display: inline-block;
}

.about-us {
    display: inline-block;
    margin: 60px 30px 0 0;
    vertical-align: top;
    font-style: italic;
    font-family: "Georgia";
    float: left;
    position: relative;
    left: 25%;
}

.paper {
    margin: 50px 0 0 0;
    width: 456px;
    padding: 0 10px;
    vertical-align: top;
    display: inline-block;
    text-align: left;
    font-size: 16px;
    font-family: "Georgia";
}

#section-3 {
    width: 100%;
    height: 90vh;
    margin: 0;
    text-align: center;
    background: rgba(0, 0, 0, .9);
    color: #fff;
}

#section-3 h1 {
    font-size: 3em;
    text-align: left;
    font-family: "Georgia";
    margin: 0 0 0 25%;
    padding: 50px 0 0 0;
}

#section-3 h3 {
    text-align: left;
    font-family: "Georgia";
    margin: 10px 0 0 25%;
    font-style: italic;
}

#section-3 .left {
    margin: 50px 0 0 25%;
    width: 20%;
    height: 40vh;
    float: left;
    text-align: left;
}

#section-3 li {
    padding: 10px 0;
    list-style: none;
    font-size: 18px;
    float: left;
    width: 100%;
}

#one span {
    background-image: url("../img/icon-mail.png");
    background-position: left;
    background-repeat: no-repeat;
    padding-left: 40px;
}

#two span {
    background-image: url("../img/icon-phone.png");
    background-position: left;
    background-repeat: no-repeat;
    padding-left: 40px;
}

#section-3 #three {
    font-size: 18px;
    margin: 40px 0 0 0;
    float: left;
}

#section-3 iframe {
    margin: 40px 0 0 0;
}

#section-3 .right {
    margin: 50px 25% 0 0;
    width: 20%;
    height: 40vh;
    float: right;
    font-family: "Georgia";
}

.right p {
    width: 100%;
    float: left;
    text-align: left;
    font-size: 20px;
}

input {
    float: left;
}

#target {
    width: 90%;
    height: 40px;
    margin: 0 0 5px 0;
}

#target-content {
    width: 90%;
    height: 280px;
}

#target-send {
    width: 30%;
    float: left;
    margin: 5px 0 0 59%;
    background: #fc0;
    border: 0;
    color: #fff;
    padding: 2% 1%;
    text-align: center;
    font-weight: 600;
}


/* page of find-talent*/

#find-talent {
    z-index: 2;
    width: 100%;
    color: #000;
    position: relative;
    bottom: 600px;
    background: #fc0;
    padding: 0 0 30px 0;
}

#find-talent h1 {
    font-size: 3em;
    text-align: left;
    font-family: "Georgia";
    margin: 0 0 0 25%;
    padding: 50px 0 0 0;
}

#find-talent h3 {
    text-align: left;
    font-family: "Georgia";
    margin: 10px 0 0 25%;
    font-style: italic;
}

#section-find-1 {
    width: 100%;
    height: 52vh;
    margin: 0;
    text-align: center;
}

#section-find-1 .left {
    width: 22%;
    float: left;
    margin: 60px 0 0 25%;
    text-align: left;
    font-family: "Georgia";
    display: inline-block;
}

#section-find-1 .left p {
    margin: 0 0 20px 0;
}

#section-find-1 .right {
    display: inline-block;
    width: 22%;
    float: right;
    margin: 60px 28% 0 0;
    text-align: left;
    font-family: "Georgia";
}

#section-find-1 .right h1 {
    margin: 0;
    font-size: 1.55em;
    line-height: 30px;
    vertical-align: top;
}

#section-find-1 .right a {
    float: right;
    background: #fc0;
    color: #000;
    text-decoration: none;
    font-family: arial;
    font-weight: bold;
    padding: 10px 20px;
    font-size: .8em;
    margin: 30px 0 0 0;
    border: 1px solid #fff;
    -webkit-transition: .5s;
    /* Safari */
    transition: .5s;
}

#section-find-1 .right a:hover {
    background: #fff;
    border: 1px solid #000;
}

footer {
    display: block;
    width: 60%;
    height: 50px;
    margin: 0 20%;
    vertical-align: middle;
    text-align: center;
    font-size: 13px;
}

footer p {
    display: inline-block;
    margin: 20px 60px 0 0;
    float: left;
}

footer ul {
    margin: 0;
}

footer li {
    display: inline-block;
    margin: 16px 0 0 0;
}
