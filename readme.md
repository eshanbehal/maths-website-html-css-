just created a small website using html5 and css:

           maths website
     ========================
     
     html code for the following project is as follow:
==========================================================
     
     <!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>
    Maths Website
    </title>
    <meta name="viewport" content="width=device-width , initial-scale=1.0 , user-scalable=yes">
    <link rel="stylesheet" href="styling.css">
    </head>
    <body>
    <div id="container">
        <div id="header">
        <h1><div id="brand"><a href="#">Maths the fun way</a></div></h1>
            <div id="searchbox">
            <form method="get">
                <input type="text" class="text">
                <input type="submit" value="Search a topic" class="submit">
                </form>
            </div>
            <div class="clear"></div>
        </div>
        <div id="menu">
        <ul>
            <li><a href="#" class="active"><b>HOME</b></a></li>
            <li><a href="#">ONLINE TUTORIALS</a></li>
            <li><a href="#">GET A PRIVATE TUTOR</a></li>
            <li><a href="#">SIGN UP</a></li>
            <li><a href="#">CONTACT US</a></li>
            </ul>
        </div>
        <div id="introduction">
        <h3>Do you need help with Maths?</h3>
        <p>Our website uses an interactive methodology of teaching Maths using the latest web technologies. Your learning experience with us is guaranteed to be intuitive and fun. You will have fun while learning. This is the secret of our outstanding results. Check reviews from our students.</p>
        </div>
        <div id="leftsidebar" class="sidebar">
        <h3>Go to:</h3>
        <ul>
            <li><a href="#">Year 1 Free Lessons.</a></li>
            <li><a href="#">Year 2 Free Lessons.</a></li>
            <li><a href="#">Year 3 Free Lessons.</a></li>
            <li><a href="#">Year 4 Free Lessons.</a></li>
            <li><a href="#">Year 5 Free Lessons.</a></li>
            <li><a href="#">Year 6 Free Lessons.</a></li>
            <li><a href="#">Year 7 Free Lessons.</a></li>
            <li><a href="#">Year 8 Free Lessons.</a></li>
            <li><a href="#">Year 9 Free Lessons.</a></li>
            <li><a href="#">Year 10 Free Lessons.</a></li>
            <li><a href="#">Year 11 Free Lessons.</a></li>
            <li><a href="#">Year 12 Free Lessons.</a></li></ul></div>
        
        <div id="rightsidebar" class="sidebar">
        <h3>Why us?</h3>
        <ul><li><a href="#">Our teachers are available any time.</a></li>
            <li><a href="#">Available on laptop, Tablets and Phones.</a></li>
            <li><a href="#">30 day Money Back Guarantee.</a></li>
            <li><a href="#">Interactive games for an enjoyable learning experience.</a></li>
            <li><a href="#">Learn at your own pace.</a></li>
            <li><a href="#">Complete curriculum.</a></li></ul></div>
        <div class="clear"></div>
        <footer class="footer">
        <p>Company name. Copyright &copy; 2015-2020</p>
        </div></footer>
        
    </body>
</html>



                      styling code for the same project is as follows:
                ===========================================================
                      
                      body{
    font: Arial , Helvetica , sans-serif;
}
#container{
    width: 1300px;
/*    border: 1px solid grey;*/
    margin: 0 auto;
}
#header{
    height: 100px;
    padding: 10px 0px;
}
#searchbox{
    float: right;
    background: linear-gradient(#E4F2B9 , #B7E953);
    background: -webkit-linear-gradient(#E4F2B9 , #B7E953);
    background: -moz-linear-gradient(#E4F2B9 , #B7E953);
    background: -o-linear-gradient(#E4F2B9 , #B7E953);
    width: 400px;
    height: 50px;
    padding: 20px 20px 0px 20px;
    margin-top: 3px;
}
.text{
    font-size: 15px;
    width: 200px;
    float: left;
    color: purple;
    padding: 7px;
    background: white url(images/search.png) right center no-repeat;
    border: 1px solid #C8D03E;
}
.submit{
    float: right;
    color: white;
    padding: 7px;
    background: mediumpurple;
    font-weight: bold;
    font-size: 15px;
}
#brand{
    float: left;
}
h1 a{
    font-size: 50px;
    font-weight: 100;
    color: darkorchid;
    text-decoration: none;
}
.clear{
    clear: both;
}
ul{
    list-style: none;   
}
#menu{
    height: 70px;
    background: linear-gradient(#F8F594 , #D5D533);
    background: -webkit-linear-gradient(#F8F594 , #D5D533);
    background: -moz-linear-gradient(#F8F594 , #D5D533);
    background: -o-linear-gradient(#F8F594 , #D5D533);
    padding: 10px 0px;
}
#menu ul li{
    float: left;
    padding: 10px 25px;
    height: 30px;
    line-height: 22px;
    border-right: 1px solid #5d12e7; 
}
#menu ul li:last-child{
    border-right: none;
}
#menu ul li a{
    text-decoration: none;
    text-transform: uppercase;
    font-size: 18px;
    color: #5d12e7;
    transition: font-size 0.4s ease;
    -webkit-transition: font-size 0.4s ease;
    -moz-transition: font-size 0.4s ease;
    -0-transition: font-size 0.4s ease;
    -ms-transition: font-size 0.4s ease;
}
#menu ul li a:hover , #menu ul li a.active{
    font-size: 22px;
    font-weight: bold;
    color: #B314DB;
}
#introduction{
    background: linear-gradient(#E4F2B9 , #B9EA56);
    background: -webkit-linear-gradient(#E4F2B9 , #B9EA56);
    background: -moz-linear-gradient(#E4F2B9 , #B9EA56);
    background: -o-linear-gradient(#E4F2B9 , #B9EA56);
    padding: 30px;
    margin: 16px 0px;
}
#introduction h3{
    font-size: 50px;
    color: #316901;
    font-weight: normal;
}
#introduction p{
    font-size: 25px;
    color: #628F19;
    text-align: justify;
}
.sidebar{
    height: 550px;
    width: 640px;
    border: 1px solid #DCF9B7;
    border-radius: 20px;
}
#leftsidebar{
    float: left;
}
#rightsidebar{
    float: right;
}
#leftsidebar h3{
    font-size: 30px;
    color: #B314DB;
    font-weight: bold;
    padding: 20px;
    padding-top: 12px;
    padding-bottom: 5px;
}
#rightsidebar h3{
    font-size: 32px;
    color: #B314DB;
    font-weight: bold;
    padding: 20px;
    padding-top:12px;
    padding-bottom:5px; 
}
#leftsidebar ul li{
    
    padding-bottom: 10px;
    list-style-image: url(images/arrow.png);
    padding-left: 20px;
}
#rightsidebar ul li{
    
    padding-bottom: 27px;
    list-style-image: url(images/tick.png) ;
    list-style-position: inside;
}
#leftsidebar ul li a{
    text-decoration: none;
    font-size: 20px;
    color: #5d12e7;
    transition: font-size 0.4s ease;
    -webkit-transition: font-size 0.4s ease;
    -moz-transition: font-size 0.4s ease;
    -0-transition: font-size 0.4s ease;
    -ms-transition: font-size 0.4s ease;
}
#rightsidebar ul li a{
    text-decoration: none;
    font-size: 23px;
    color: #5d12e7;
    transition: font-size 0.3s ease;
    -webkit-transition: font-size 0.4s ease;
    -moz-transition: font-size 0.4s ease;
    -0-transition: font-size 0.4s ease;
    -ms-transition: font-size 0.4s ease;
}
#leftsidebar ul li a:hover{
    font-size: 22px;
    font-weight: bold;
    color: #B314DB;
}
#rightsidebar ul li a:hover{
    font-size: 27px;
    font-weight: bold;
    color: #B314DB;
}
.footer{
    height: 50px;
    background: linear-gradient(#F4F18A, #D7D638);
    background: -webkit-linear-gradient(#F4F18A, #D7D638);
    background: -moz-linear-gradient(#F4F18A, #D7D638);
    background: -o-linear-gradient(#F4F18A, #D7D638);
    padding: 20px 5px 20px 20px;
    margin-top: 15px;
}