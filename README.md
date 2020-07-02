# CSS-CODE
CSS CODE FOR THE WEBSITE
*{
    margin: 0;
    padding: 0;
    font-family: sans-serif:
}
.container{
    width: 100%;
    height: 100;
    background: #42455a;
}
.menu ul{
    display: inline-flex;
    margin: 50px;
}
.menu ul li{
    list-style: none;
    margin: 0 20px;
    color: #b2b1b1;
    cursor: pointer;
}
.logo img{
    width: 30px;
    margin-top: -7px;
    margin-right: 48px;
}
.active{
    color: #19dafa !important;
}
.signup-btn{
    top: 40px;
    right: 80px;
    position: absolute;
    text-decoration: none;
    color: #fff;
    border: 2px solid transparent;
    border-radius: 20px;
    background-image: linear-gradient(#42455a,#42455a),radial-gradient(circle at top left,#fd00da,#19d7f8);
    background-origin: border-box;
    background-clip: content-box,border-box;
}
.signup-btn span{
    display: block;
    padding: 8px 22px;
}
.banner{
    width: 80%;
    height: 70%;
    top: 25%;
    left: 130px;
    position: absolute;
    color: #fff;
}
.app.text{
    width: 50%;
    float: left;
}
.app.text h1{
    font-size: 43px;
    width: 640px;
    position: relative;
    margin-left: 40px;
}
.app.text p{
    width: 650px;
    font-size: 15px;
    margin: 30px 0 30px 40px;
    line-height: 25px;
    color: #919191;
}
.app-picture{
    width: 50%;
    float: right;
}
.app-picture img{
    width: 100%;
    margin-top: -20px;
    padding-left: 50px;
}
.play-btn{
    margin-left: 40px;
    display: 50px;
}
.play-btn-inner{
    height: 50px;
    width: 50px;
     border: 2px solid transparent;
    border-radius: 50px;
    background-image: linear-gradient(#42455a,#42455a),radial-gradient(circle at top left,#fd00da,#19d7f8);
    background-origin: border-box;
    background-clip: content-box,border-box;
    text-align: center;
}
.play-btn-inner .fa{   
    padding: 18px 0;
    font-size: 13px;
    cursor: pointer;
}
.small{
    margin: auto 20px;
    cursor: pointer;
    font-sixe: 12px;
    color: 19dafa;
    letter-spacing: 3px;
} 
.quick-links{
    left: 0;
    bottom: 0;
    position: absolute;
    background: linear-gradient(to tright,#db1bf6,#169d7f8);
}
.quick-links ul{
    display: inline-flex;
    margin: 30px auto;
    text-align: center;
}
.quick-links ul li{
    list-style: nonr;
    margin: 0 50px;
    cursor: pointer;
}
.quick-links ul li .fa{
    font-size: 25px;
    color: #fff;
}
.quick-links ul li p{
    margin-top: 15px;
    font-size: 10px;
    color: #fff;
}
.social-icons{
    right: 72px;
    bottom: 35px;
    position: absolute;
}
.social-icons ul li{
    list-style: none;
    margin-top: 15px;
    text-align: center;
}
.social-icons ul li a{
    color: #999;
    border-tadius: 50%;
    border: 1px solid #999;
    padding: 5px;
    display: block;
}
