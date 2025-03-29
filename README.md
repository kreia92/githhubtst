<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>EMS DESSERTS</title>
</head>
<body>
<hr>
<div class="maincontainer"></div>

   <div class="header">

  <h1>EMS Desserts
  <p>Eat me sweetie</p></h1>
<ul>
      	<li><a href="homedessert.html">Home</a></li>
      	<li><a href="shopdessert.html">Shop</a></li>
      	<li><a href="recipedessert.html">Recipe</a></li>
      	<li><a href="aboutdessert.html">About</a></li>
      	<li><a href="contactdessert.html">Contact Us</a></li>
      	<li><a href="accountdesser.html">Account</a></li>
 </ul>
   </div>
<hr>
   <div class="midcontainer">

   <div class="leftnav">
       <h1>Categories</h1>
       <ul>
       	<li>Pastries</li>
       	<li>Cakes</li>
       	<li>Frozen Desserts</li>
       	<li>Cupcakes</li>
       	<li>Cookies</li>
       	<li>Donuts</li>
       </ul>
   </div>

<div class="f">

   <div class="rightnav">
      <h1>HEAVENLY<br><span>SWEET</span><br>DELIGHTS.</h1>
   </div>
</div>

<div class="featured"> 
	<p>Featured Desserts</p>
   <div class="fd">
      <img src="chocolate-cake.jpg" alt="Cake">
   </div>
  
</div>
</div>
<div class="footer">
	<p>ORDER HERE:</p>
   <div class="items">
            <div class="item1">
                <img src="chocolate-cake.jpeg" alt="Chocolate Triff">
                <p>Chocolate Triff</p>
            </div>

            <div class="item2">
                <img src="royalty-cake.jpg" alt="Royalty Cake">
                <p>Royalty Cake</p>
            </div>

            <div class="item4">
                <img src="ice-cream.jpg" alt="Ice Cream">
                <p>Ice Cream</p>
            </div>

            <div class="item5">
                <img src="super-moist-choco.jpg" alt="Super Moist Chocolate Cupcake">
                <p>Super Moist <br>Chocolate Cupcake</p>
            </div>

            <div class="item6">
                <img src="white-choco-cookie.jpg" alt="Soft White Chocolate Cookie">
                <p>Soft White<br> Chocolate Cookie</p>
            </div>

            <div class="item7">
                <img src="chocolate-donut.jpg" alt="Chocolate Donut">
                <p>Chocolate Donut</p>
            </div>
        </div>
<div class="footer">
<h3>© 2024 EMS DESSERTS. All Rights Reserved</h3>
</div>
</div>

</body>
</html>

<style type="text/css">
   *{
   margin: 5px;
}

body{
   font-family: Arial, 'sans-serif';
    margin: 0;
    padding: 0;
    background-color: #white;

}

.maincontainer{
   border: 0px red solid;
   /*width: 988px;*/
}

.header h1{
   font-family: cambria;
   font-size: 40px;
}

.header p{
    font-family: cursive;
    font-size: 20px;
    text-align: center;
}

.header{
   border: 0px red solid;
   height: 100px;
   display:flex;
   list-style: none;
   justify-content: space-evenly;
   align-items: center;
    background-color: #f6fff8;
}

.header ul{
   list-style: none;
}

.header ul li{
   display: inline-block;
   margin: 0 15px;
}

.header ul li a{
   text-decoration: none;
   color: #000;
   font-weight: 500;
   font-size: 17px;
   transition: 0.1s;
}

.header ul li a::after{
   content:'';
   width: 0;
   height: 2px;
   background: #fac031;
   display: block;
   transition: 0.2s linear;
}

.header ul li a:hover:after{
    width: 100%;
}

.header ul li a:hover{
   color: #fac013;
}

.midcontainer{
   border: 0px red solid;
   display: flex;
   background-color: #cce3de;
}

.leftnav{
   border: 0px red solid;
   width: 25%;
   height: 330px;
   background-color: #eaf4f4;
   
}

.leftnav h1{
   font-family:cursive;
   margin left: 1px;
   color: #f1948a;
}

.leftnav ul{
   font-family: verdana;
}


.rightnav{
   border: 0px red solid;
   width: 150%;
   height: 330px;
   font-size: 30px;
    position: relative;
   text-align: center;
   top: 50px;
}

.rightnav span{
  margin-left: 15px;
   color: #fac013;
   font-family: mv boli;
   line-height: 22px;
   font-size: 70px;
}

.featured{
   border: 0px #aed6f1 solid;
   width: 50%;
  margin: 20px;
 margin-left: 25%;
  background-color: #eaf4f4;
}

*{
   box-sizing: border-box;
}

.featured .fd{
   border: 1px red solid;
   width: 70%;
   margin: 20px;
  height: 75%;
 margin-left: 15%;
}

@keyframes myani{
   0%{background-image: url("cake.jpeg");}
   35%{background-image: url("cake.jpeg");}
   75%{background-image: url("cake.jpeg");}
}

.featured p{
   font-family: cursive;
   padding-top: 0px;
   color: #f1948a;
   font-size: 20px;

}
.footer{
   border: 0px red solid;
   height: 500px;
   margin: 5px;
   background-color: #eaf4f4;

}

.footer p{
   font-size: 30px;
   padding: 5px;
   font-family: fantasy;
   color: #5d6d7e;
}

.items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .item {
            text-align: center;
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 15px;
            border-radius: 8px;
        }
        .item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #ffd1dc;
            margin-top: 20px;
        }

.footer{
   height: 40px;
   text-align: center;
   padding: 3PX;
}
 
 @media (max-width: 1000px) {
    .header h1{
       flex-direction: column;
    }

    .header ul {
        flex-direction: column;
        align-items: center;
    }

    .midcontainer {
        flex-direction: column;
        align-items: center;
    }

    .leftnav, .rightnav, .featured {
        width: 100%;
        max-width: 100%;
    }

    .items {
        flex-direction: column;
        align-items: center;
    }

    .item1, .item2, .item4, .item5, .item6, .item7 {
        width: 80%;
    }
}

@media (max-width: 480px) {
    .header h1 {
        font-size: 28px;
    }

    .header p {
        font-size: 18px;
    }

    .footer p {
        font-size: 24px;
    }

    .items {
        flex-direction: column;
        gap: 10px;
    }

    .item1, .item2, .item4, .item5, .item6, .item7 {
        width: 90%;
    }
}

</style>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Website for Dessert Lovers</title>
	
</head>
<body>
<hr>
<div class="maincontainer"></div>

   <div class="header">

  <h1><a href="k.html">EMS Desserts</a>
  <p>Eat me sweetie</p></h1>
<ul>
      	<li><a href="homedessert.html">Home</a></li>
        <li><a href="shopdessert.html">Shop</a></li>
        <li><a href="recipedessert.html">Recipe</a></li>
        <li><a href="aboutdessert.html">About</a></li>
        <li><a href="contactdessert.html">Contact Us</a></li>
        <li><a href="accountdesser.html">Account</a></li>
 </ul>
   </div>
<hr>
   <div class="welcome">
   	<h1>WELCOME DESSERT LOVERS!</h1>
   </div>

   <div class="description">
   	<h2>Here you’ll find sweet recipes, Pastries, Cakes, Frozen Desserts, Cupcakes,<br> Cookies, Doughnut for every occasion. Grab any of our recipes.</h2>
   </div>
<hr>
<div class="new">
	<h1>NEW RECIPES!</h1>
 <div class="items">
            <div class="item1">
                <img src="chessecake.jpg" alt="chessecake">
                <p>Chessecake</p>
            </div>

            <div class="item2">
                <img src="cookie dough.jpg" alt="cookie dough">
                <p>Cookie Dough</p>
            </div>

            <div class="item3">
                <img src="salted caramel.jpg" alt="salted  caramel">
                <p>Salted Caramel</p>
            </div>

            <div class="item4">
                <img src="chocolate lava cake.jpg" alt="Chocolate lava cake">
                <p>Chocolate Lava <br>Cake</p>
            </div>

            <div class="item5">
                <img src="Jelly filled donut.jpg" alt="Jelly filled donut">
                <p>Jelly Filled<br>Donut</p>
            </div>

            <div class="item6">
                <img src="mini apple rose pies.jpeg" alt="mini apple rose pies">
                <p>Mini Aplle<br>Rose Pies</p>
            </div>

             <div class="item7">
                <img src="triple chocolate.jpeg" alt="triple chocolate">
                <p>Triple Chocolate</p>
            </div>

             <div class="item8">
                <img src="white chocolate cranberry oat.jpeg" alt="white chocolate cranberry oat.jpeg">
                <p>white chocolate <br>cranberry oat.jpeg</p>
            </div>

             <div class="item9">
                <img src="very cherry cupcake.jpeg" alt="very cherry cupcake">
                <p>very cherry cupcake</p>
            </div>

             <div class="item10">
                <img src="triple berry delight.jpeg" alt="triple berry delight">
                <p>triple berry delight</p>
            </div>
        </div>
    </div>

<div class="popular">
    <h1>POPULAR RECIPES!</h1>
<div class="items">
            <div class="item1">
                <img src="caramel brownie lava cake.jpeg" alt="caramel brownie lava cake">
                <p>caramel brownie<br> lava cake</p>
            </div>

            <div class="item2">
                <img src="cookie dough.jpg" alt="cookie dough">
                <p>Cookie Dough</p>
            </div>

            <div class="item4">
                <img src="new york chessecake.jpg" alt="new york chessecake">
                <p>new york chessecake</p>
            </div>

            <div class="item5">
                <img src="deep fried bar & ice cream.jpg" alt="deep fried bar & ice cream">
                <p>deep fried bar <br>& ice cream</p>
            </div>

            <div class="item6">
                <img src="tiramisu.jpg" alt="tiramisu">
                <p>tiramisu</p>
            </div>

            <div class="item7">
                <img src="butterscoth.jpg" alt="butterscoth">
                <p>butterscoth</p>
            </div>
        </div>
    </div>
<hr>

<div class="footer">
<h3>© 2024 EMS DESSERTS. All Rights Reserved</h3>
</div>
</div>
</body>
</html>

<style type="text/css">
    *{
    margin: 3px;
}

body{
    font-family: Arial, 'sans-serif';
    margin: 0;
    padding: 0;
    background-color: #white;

}

.maincontainer{
    border: 0px red solid;
    /*width: 988px;*/
}

.header h1{
    font-family: cambria;
    font-size: 40px;
}

.header p{
    font-family: cursive;
    font-size: 20px;
    text-align: center;
}

.header a{
    text-decoration: none;
    color: #000;
    transition: 0.1s;
}

.header a:after{
    width: 0;
    background: #fac031;
    display: block;
    transition: 0.2s linear;
}

.header a:hover{
    color: #fac013;
}

.header{
    border: 0px red solid;
    height: 100px;
    display:flex;
    list-style: none;
    justify-content: space-evenly;
    align-items: center;
     background-color: #f6fff8;
}

.header ul{
    list-style: none;
}

.header ul li{
    display: inline-block;
    margin: 0 15px;
}

.header ul li a{
    text-decoration: none;
    color: #000;
    font-weight: 500;
    font-size: 17px;
    transition: 0.1s;
}

.header ul li a::after{
    content:'';
    width: 0;
    height: 2px;
    background: #fac031;
    display: block;
    transition: 0.2s linear;
}

.header ul li a:hover:after{
    width: 100%;
}

.header ul li a:hover{
    color: #fac013;
}

.welcome{
    border: 0px red solid;
    width: 90%;
    margin-left: 5%;
    height: 70px;
    text-align: center;
    font-family: mv boli;
    color: #fac013;
    background-color: #cce3de;
}

.description {
    border: 0px red solid ;
    width: 80%;
    margin-left:10%;
    height: 100px;
    background-color: #eaf4f4;
}

.description h2{
    font-family: cursive;
    justify-content: center;
    text-align: center;
    background-color: #eaf4f4;
}

.new{
    border: 0px red solid;
    height: 300px;
    margin: 5px;
    background-color: #cce3de;

}

.new h1{
   font-size: 30px;
   padding: 5px;
   font-family: cambria;
   color: #5d6d7e;
   text-align: center;
}

.items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            border: 0px red solid;
        }
        .item {
            text-align: center;
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 15px;
            border-radius: 8px;
        }
        .item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        new {
            text-align: center;
            padding: 10px;
            background-color: #ffd1dc;
            margin-top: 20px;
        }

.popular{
    border: 0px red solid;
    height: 300px;
    background-color: #eaf2f8;
}

.popular h1{
     font-size: 30px;
   padding: 5px;
   font-family: cambria;
   color: #5d6d7e;
   text-align: center;
}

.items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            border: 0px red solid;
        }
        .item {
            text-align: center;
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 15px;
            border-radius: 8px;
        }
        .item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        new {
            text-align: center;
            padding: 10px;
            background-color: #ffd1dc;
            margin-top: 20px;
        }

.footer{
    height: 40px;
    text-align: center;
    padding: 3PX;
}

    @media screen and (max-width: 1000px) {
            .header ul {
                flex-direction: column;
                align-items: center;
            }

            .header ul li {
                margin-bottom: 10px;
            }

            .header h1 {
                font-size: 28px;
            }

            .welcome, .description, .new, .popular {
                width: 100%;
                padding: 10px;
            }

            .new .items, .popular .items {
                flex-direction: column;
            }

            .item {
                flex: 1 1 100%;
                max-width: 100%;
            }

            .footer {
                font-size: 14px;
            }
        }

        @media screen and (max-width: 480px) {
            .header h1 {
                font-size: 24px;
            }

            .header ul li a {
                font-size: 12px;
            }

            .new h1, .popular h1 {
                font-size: 24px;
            }

            .items {
                gap: 10px;
            }

            .item {
                flex: 1 1 calc(50% - 10px);
            }

            .footer {
                font-size: 12px;
            }
        }
    </style>

    <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>shop</title>
	
</head>
<body>
<hr>
<div class="maincontainer"></div>

   <div class="header">

  <h1><a href="k.html">EMS Desserts</a>
  <p>Eat me sweetie</p></h1>
<ul>
      <li><a href="homedessert.html">Home</a></li>
      	<li><a href="shopdessert.html">Shop</a></li>
      	<li><a href="recipedessert.html">Recipe</a></li>
      	<li><a href="aboutdessert.html">About</a></li>
      	<li><a href="contactdessert.html">Contact Us</a></li>
      	<li><a href="accountdesser.html">Account</a></li>
 </ul>
   </div>
<hr>

<div  class="entry">
<p>Indulge in the sweetest selections, hand-crafted with love and the finest ingredients. From decadent cakes and delicate pastries to velvety tarts and artisanal cookies, our shop offers a delightful array of desserts that are perfect for any occasion—or just because.</p><br>
<p>Browse through our collection of treats, carefully designed to satisfy every craving, and enjoy the convenience of having your favorites delivered straight to your door. Whether you're planning a celebration, looking for a gift, or simply treating yourself, you'll find something irresistible in our dessert shop</p>
</div>

<div class="pictures">
<div class="items">
            <div class="items">
                <img src="caramel brownie lava cake.jpeg" alt="caramel brownie lava cake">
                <p>caramel brownie<br> lava cake</p>
            </div>

            <div class="items">
                <img src="cookie dough.jpg" alt="cookie dough">
                <p>Cookie Dough</p>
            </div>

            <div class="items">
                <img src="new york chessecake.jpg" alt="new york chessecake">
                <p>new york chessecake</p>
            </div>

            <div class="items">
                <img src="deep fried bar & ice cream.jpg" alt="deep fried bar & ice cream">
                <p>deep fried bar <br>& ice cream</p>
            </div>

            <div class="items">
                <img src="tiramisu.jpg" alt="tiramisu">
                <p>tiramisu</p>
            </div>

            <div class="items">
                <img src="butterscoth.jpg" alt="butterscoth">
                <p>butterscoth</p>
            </div>
        </div>
    </div>
</div>

<div class="footer">
<h3>© 2024 EMS DESSERTS. All Rights Reserved</h3>
</div>
</div>
</body>
</html>

<style type="text/css">
	*{
	margin: 5px;
}

body{
	font-family: Arial, 'sans-serif';
    margin: 0;
    padding: 0;
    background-color: white;

}

.maincontainer{
	border: 0px red solid;
	/*width: 988px;*/
}

.header h1{
	font-family: cambria;
	font-size: 40px;
}

.header p{
    font-family: cursive;
    font-size: 20px;
    text-align: center;
}

.header a{
	text-decoration: none;
	color: #000;
	transition: 0.1s;
}

.header a:after{
	width: 0;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header a:hover{
	color: #fac013;
}

.header{
	border: 0px red solid;
	height: 100px;
	display:flex;
	list-style: none;
	justify-content: space-evenly;
	align-items: center;
	 background-color: #f6fff8;
}

.header ul{
	list-style: none;
}

.header ul li{
	display: inline-block;
	margin: 0 15px;
}

.header ul li a{
	text-decoration: none;
	color: #000;
	font-weight: 500;
	font-size: 17px;
	transition: 0.1s;
}

.header ul li a::after{
	content:'';
	width: 0;
	height: 2px;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header ul li a:hover:after{
    width: 100%;
}

.header ul li a:hover{
	color: #fac013;
}

.entry{
	border: 0px red solid;
	height:170px;
	background-color: #FBFBFB;
	font-family: cursive;
	padding: 2px;
}

.pictures{
	background-color: #FFF6E3;
}

.items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            border: 0px red solid;
        }
        .item {
            text-align: center;
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 15px;
            border-radius: 8px;
        }
        .item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        new {
            text-align: center;
            padding: 10px;
            background-color: #ffd1dc;
            margin-top: 20px;
        }

.entry 
.footer{
	height: 40px;
	text-align: center;
	padding: 3PX;
}
@media screen and (max-width: 1000px) {

            .header h1 p{
            	 flex-direction: column;
                align-items: center;
            }

            .header ul {
                flex-direction: column;
                align-items: center;
            }

            .header ul li {
                margin-bottom: 10px;
            }

            .header h1 {
                font-size: 28px;
            }

            .entry p{
                width: 100%;
                padding: 3px;
            }

            .pictures, .item {
                flex-direction: column;
            }

            .item {
                flex: 1 1 100%;
                max-width: 100%;
            }

            .footer {
                font-size: 14px;
            }
        }

        
</style>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>recipe</title>
</head>
<body>

	<div class="maincontainer"></div>
<hr>
   <div class="header">

  <h1><a href="k.html">EMS Desserts</a>
  <p>Eat me sweetie</p></h1>
<ul>
      <li><a href="homedessert.html">Home</a></li>
      	<li><a href="shopdessert.html">Shop</a></li>
      	<li><a href="recipedessert.html">Recipe</a></li>
      	<li><a href="aboutdessert.html">About</a></li>
      	<li><a href="contactdessert.html">Contact Us</a></li>
      	<li><a href="accountdesser.html">Account</a></li>
 </ul>
   </div>
<hr>
<div class="entry">
  <h1>ALL RECIPE</h1>
</div>

<div class="description">
<p>Find the recipes by type and occasion, or look them up in the search bar below.</p>
</div>
<hr>
<div class="pictures">pics
	<div class="items">
            <div class="item1">
                <img src="layer Cakes.jpeg" alt="layer Cakes">
                <p>layer Cakes</p>
            </div>

            <div class="item2">
                <img src="cupcake.jpg" alt=" cupCake">
                <p> cupCake</p>
            </div>

            <div class="item4">
                <img src="cookies.jpg" alt="cookies">
                <p>cookies</p>
            </div>

            <div class="item5">
                <img src="frozendessert.jpg" alt="frozendessert">
                <p>frozendessert</p>
            </div>

            <div class="item6">
                <img src="cakes.jpg" alt="cakes">
                <p>cakes</p>
            </div>

            <div class="item7">
                <img src="donut.jpg" alt=" Donut">
                <p> Donut</p>
            </div>
        </div>

</div>
<hr>
<div class="occasion">occasion
<h1>BY OCCASION</h1>
<div class="items">
            <div class="item1">
                <img src="caramel brownie lava cake.jpeg" alt="caramel brownie lava cake">
                <p>caramel brownie<br> lava cake</p>
            </div>

            <div class="item2">
                <img src="cookie dough.jpg" alt="cookie dough">
                <p>Cookie Dough</p>
            </div>

            <div class="item4">
                <img src="new york chessecake.jpg" alt="new york chessecake">
                <p>new york chessecake</p>
            </div>

            <div class="item5">
                <img src="deep fried bar & ice cream.jpg" alt="deep fried bar & ice cream">
                <p>deep fried bar <br>& ice cream</p>
            </div>

            <div class="item6">
                <img src="tiramisu.jpg" alt="tiramisu">
                <p>tiramisu</p>
            </div>

            <div class="item7">
                <img src="butterscoth.jpg" alt="butterscoth">
                <p>butterscoth</p>
            </div>
        </div>
    </div>
</div>

<div class="info">info</div>

<div class="footer">
<h3>© 2024 EMS DESSERTS. All Rights Reserved</h3>
</div>

</div>
</body>
</html>

<style type="text/css">
	*{
	margin: 5px;
}

body{
	font-family: Arial, 'sans-serif';
    margin: 0;
    padding: 0;
    background-color: white;

}

.maincontainer{
	border: 0px red solid;
	/*width: 988px;*/
}

.header h1{
	font-family: cambria;
	font-size: 40px;
}

.header p{
    font-family: cursive;
    font-size: 20px;
    text-align: center;
}

.header{
	border: 0px red solid;
	height: 100px;
	display:flex;
	list-style: none;
	justify-content: space-evenly;
	align-items: center;
	 background-color: #f6fff8;
}

.header ul{
	list-style: none;
}

.header ul li{
	display: inline-block;
	margin: 0 15px;
}

.header ul li a{
	text-decoration: none;
	color: #000;
	font-weight: 500;
	font-size: 17px;
	transition: 0.1s;
}

.header ul li a::after{
	content:'';
	width: 0;
	height: 2px;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header ul li a:hover:after{
    width: 100%;
}

.header ul li a:hover{
	color: #fac013;
}

.header a{
	text-decoration: none;
	color: #000;
	transition: 0.1s;
}

.header a:after{
	width: 0;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header a:hover{
	color: #fac013;
}

.entry{
	border: 0px red solid;
	height: 80px;
	background-color: #f6fff8;
}

.entry h1{
	font-family: courier;
	margin-left: 8%;
	letter-spacing:3px;
	margin-top: 30px;
}

.description{
	border:0px red solid;
	height: 60px;
	color: grey;
	font-size: 20px;
}

.description p{
	margin-left: 3%;
}


.pictures{
	border: 0px red solid;
	height: 150px;
	background-color: #cce3de;
}

.items {
            display: inline-flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .item {
            text-align: center;
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 15px;
            border-radius: 8px;
        }
        .item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        pictures {
            text-align: center;
            padding: 10px;
            background-color: #ffd1dc;
            margin-top: 20px;
        }

.occasion{
	border: 0px red solid;
	height: 300px;
	background-color: #cce3de;
}

.occasion h1{
   font-family: courier;
	margin-left: 8%;
	letter-spacing:3px;
	margin-top: 10px;
}
.info{
	border: 1px red solid;
}

.footer{
	height: 40px;
	text-align: center;
	padding: 3PX;
}
</style>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>recipe</title>
</head>
<body>

	<div class="maincontainer"></div>
<hr>
   <div class="header">

  <h1><a href="k.html">EMS Desserts</a>
  <p>Eat me sweetie</p></h1>
<ul>
      <li><a href="homedessert.html">Home</a></li>
      	<li><a href="shopdessert.html">Shop</a></li>
      	<li><a href="recipedessert.html">Recipe</a></li>
      	<li><a href="aboutdessert.html">About</a></li>
      	<li><a href="contactdessert.html">Contact Us</a></li>
      	<li><a href="accountdesser.html">Account</a></li>
 </ul>
   </div>
<hr>
<div class="entry">
  <h1>ALL RECIPE</h1>
</div>

<div class="description">
<p>Find the recipes by type and occasion, or look them up in the search bar below.</p>
</div>
<hr>
<div class="pictures">pics
	<div class="items">
            <div class="item1">
                <img src="layer Cakes.jpeg" alt="layer Cakes">
                <p>layer Cakes</p>
            </div>

            <div class="item2">
                <img src="cupcake.jpg" alt=" cupCake">
                <p> cupCake</p>
            </div>

            <div class="item4">
                <img src="cookies.jpg" alt="cookies">
                <p>cookies</p>
            </div>

            <div class="item5">
                <img src="frozendessert.jpg" alt="frozendessert">
                <p>frozendessert</p>
            </div>

            <div class="item6">
                <img src="cakes.jpg" alt="cakes">
                <p>cakes</p>
            </div>

            <div class="item7">
                <img src="donut.jpg" alt=" Donut">
                <p> Donut</p>
            </div>
        </div>

</div>
<hr>
<div class="occasion">occasion
<h1>BY OCCASION</h1>
<div class="items">
            <div class="item1">
                <img src="caramel brownie lava cake.jpeg" alt="caramel brownie lava cake">
                <p>caramel brownie<br> lava cake</p>
            </div>

            <div class="item2">
                <img src="cookie dough.jpg" alt="cookie dough">
                <p>Cookie Dough</p>
            </div>

            <div class="item4">
                <img src="new york chessecake.jpg" alt="new york chessecake">
                <p>new york chessecake</p>
            </div>

            <div class="item5">
                <img src="deep fried bar & ice cream.jpg" alt="deep fried bar & ice cream">
                <p>deep fried bar <br>& ice cream</p>
            </div>

            <div class="item6">
                <img src="tiramisu.jpg" alt="tiramisu">
                <p>tiramisu</p>
            </div>

            <div class="item7">
                <img src="butterscoth.jpg" alt="butterscoth">
                <p>butterscoth</p>
            </div>
        </div>
    </div>
</div>

<div class="info">info</div>

<div class="footer">
<h3>© 2024 EMS DESSERTS. All Rights Reserved</h3>
</div>

</div>
</body>
</html>

<style type="text/css">
	*{
	margin: 5px;
}

body{
	font-family: Arial, 'sans-serif';
    margin: 0;
    padding: 0;
    background-color: white;

}

.maincontainer{
	border: 0px red solid;
	/*width: 988px;*/
}

.header h1{
	font-family: cambria;
	font-size: 40px;
}

.header p{
    font-family: cursive;
    font-size: 20px;
    text-align: center;
}

.header{
	border: 0px red solid;
	height: 100px;
	display:flex;
	list-style: none;
	justify-content: space-evenly;
	align-items: center;
	 background-color: #f6fff8;
}

.header ul{
	list-style: none;
}

.header ul li{
	display: inline-block;
	margin: 0 15px;
}

.header ul li a{
	text-decoration: none;
	color: #000;
	font-weight: 500;
	font-size: 17px;
	transition: 0.1s;
}

.header ul li a::after{
	content:'';
	width: 0;
	height: 2px;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header ul li a:hover:after{
    width: 100%;
}

.header ul li a:hover{
	color: #fac013;
}

.header a{
	text-decoration: none;
	color: #000;
	transition: 0.1s;
}

.header a:after{
	width: 0;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header a:hover{
	color: #fac013;
}

.entry{
	border: 0px red solid;
	height: 80px;
	background-color: #f6fff8;
}

.entry h1{
	font-family: courier;
	margin-left: 8%;
	letter-spacing:3px;
	margin-top: 30px;
}

.description{
	border:0px red solid;
	height: 60px;
	color: grey;
	font-size: 20px;
}

.description p{
	margin-left: 3%;
}


.pictures{
	border: 0px red solid;
	height: 150px;
	background-color: #cce3de;
}

.items {
            display: inline-flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .item {
            text-align: center;
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 15px;
            border-radius: 8px;
        }
        .item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        pictures {
            text-align: center;
            padding: 10px;
            background-color: #ffd1dc;
            margin-top: 20px;
        }

.occasion{
	border: 0px red solid;
	height: 300px;
	background-color: #cce3de;
}

.occasion h1{
   font-family: courier;
	margin-left: 8%;
	letter-spacing:3px;
	margin-top: 10px;
}
.info{
	border: 1px red solid;
}

.footer{
	height: 40px;
	text-align: center;
	padding: 3PX;
}
</style>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>contact us</title>

</head>
<body>
<hr>
	<div class="maincontainer"></div>

   <div class="header">

  <h1><a href="k.html">EMS Desserts</a>
  <p>Eat me sweetie</p></h1>
<ul>
      <li><a href="homedessert.html">Home</a></li>
      	<li><a href="shopdessert.html">Shop</a></li>
      	<li><a href="recipedessert.html">Recipe</a></li>
      	<li><a href="aboutdessert.html">About</a></li>
      	<li><a href="contactdessert.html">Contact Us</a></li>
      	<li><a href="accountdesser.html">Account</a></li>
 </ul>
   </div>
<hr>
</div>
</body>
</html>

<style type="text/css">
	*{
	margin: 5px;
}

body{
	font-family: Arial, 'sans-serif';
    margin: 0;
    padding: 0;
    background-color: white;

}

.maincontainer{
	border: 0px red solid;
	/*width: 988px;*/
}

.header h1{
	font-family: cambria;
	font-size: 40px;
}

.header p{
    font-family: cursive;
    font-size: 20px;
    text-align: center;
}

.header{
	border: 0px red solid;
	height: 100px;
	display:flex;
	list-style: none;
	justify-content: space-evenly;
	align-items: center;
	 background-color: #f6fff8;
}

.header ul{
	list-style: none;
}

.header ul li{
	display: inline-block;
	margin: 0 15px;
}

.header ul li a{
	text-decoration: none;
	color: #000;
	font-weight: 500;
	font-size: 17px;
	transition: 0.1s;
}

.header ul li a::after{
	content:'';
	width: 0;
	height: 2px;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header ul li a:hover:after{
    width: 100%;
}

.header ul li a:hover{
	color: #fac013;
}

.header a{
	text-decoration: none;
	color: #000;
	transition: 0.1s;
}

.header a:after{
	width: 0;
	background: #fac031;
	display: block;
	transition: 0.2s linear;
}

.header a:hover{
	color: #fac013;
}
</style>
