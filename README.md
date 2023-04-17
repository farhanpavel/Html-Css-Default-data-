# Html-Css-Default-data-
Important Data to make a website Responsive
/* For desktop: */
.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}


mobile.css


.about-me::after{
    clear: both;
    display: table;
    content: '';
}

[class*="col-"]{
    float: left;
    padding: 10px;
}

/* for mobile  */
[class*="col-"]{
    width: 100%;
}

*{
    font-family: 'Ubuntu', sans-serif;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

Responsive Check:
For Mobile-360×640
For Desktop-1920×1080
For Tablet:768×1024 & 601×962 


