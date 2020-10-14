<html lang="en">
<head>
 <style>
   html {
    box-sizing: border-box;
}
*, *:before, *:after {
    box-sizing: inherit;
}
body {
    font-family: 'Open Sans', sans-serif;
}
h1, h2, h3, h4, h5, h6 {
    font-family: 'Kavivanar','open sans';
    font-weight: normal;
}
h2 {
    font-size: 2rem;
    color: blue;
    margin: 0;
}
a {
    color: red;
    text-decoration: none;
}
a:hover {
    text-decoration: underline;
}
.wrapper{
      width:80%;
      margin:0 auto;
}
header{
    display:flex;
    flex-flow: row nowrap; 
     justify-content: space-between;  
}
.leftheader{
flex-basis:50%;
  padding-right: 0.5rem;
text-align: right;
}
.rightheader{
    flex-basis:50%;
padding-left: 0.5rem;
margin-top: 2.75rem;
}
.rightheader h1{
    margin:0;
     color: blue; }
.rightheader p{
         margin-top:-0.3rem;
color:red;}
.posted {
    font-size: 0.8rem;
    color: red;  
}
footer {
    text-align: center;
    font-size: 0.8rem;
    border-top:1px blue solid;
}
nav {
    border-top:1px solid blue;
    border-bottom:1px solid blue;
}
nav ul{
    list-style-type: none;
    padding:0;
    margin:0;
    text-align: center;
}
nav li{
    display:inline-block;
}
nav a{
    color:red;
    padding:0.5rem 1rem;      
  display: block;
}
nav a:hover{
    color:white;
    background-color:blue;
  text-decoration:none;
}
article{
    margin:3rem 0;
}
article img{
    float:left;
    margin: -3rem 1rem 1rem 0; 
}
section{
    border-bottom:1px blue solid;
    margin-bottom:0.3rem;
}
article:after{
    content: "";
    display: table;
    clear:both;
}
footer ul{
    padding:0;
    margin:0;
     list-style-type: none;  
}
footer li{
    display:inline-block;
   padding:0.5rem;
}
footer a:hover{
  background-color:blue;
  color:white;
  text-decoration:none;
}
   </style>
	 
</head>
 
<body>
	<div class="wrapper">
		<header>
			<div class="leftheader">
				<a href="/"><img src= "  https://i.postimg.cc/c4BLmNrH/download-2.jpg" alt="best shoe"></a>
			</div>
			<div class="rightheader">
				<h1 >Kiran Shoes</h1>
				<p>Good shoes take u good place</p>
			</div>
		</header>
		<nav>
			<ul>											 
				<li><a href="#">Home</a></li>
				<li><a href="#">Branded</a></li>
				<li><a href="#">Men</a></li>
				<li><a href="#">Women</a></li>
				<li><a href="#"> Unisex</a></li>
			</ul>
		</nav> 
		<section>
			<article> 
				<h2>Crush your comfort zone-adidas</h2>
				<p class="posted">Posted October 15, 2018</p>
				<p> These adidas shoes are certainly a classic, and most people will 
own a pair of these. They are available in a whole variety of colors and women can 
even wear them too, as they are also called as unisex. They are
made from synthetic water-resistant materials on the outside, 
making them very suitable for all types of weather conditions. They 
are also a lace-up type of shoes, which makes them very easy to 
wear, plus, if they do become a little loose, you can easily tighten 
them up. They have textile lining inside the shoe, making them 
comfortable.</p>
				<p><a href="blog1.html">Read more >> </a></p>
			</article>
			<article>
				<h2>Runs end. running doesn't -Nike</h2>
				<p class="posted">Posted October 5, 2018</p>
				<p>Nike produces a wide range of sports equipment. Their first products were track running shoes. They currently also make shoes, jerseys, shorts, cleats, baselayers, etc. for a wide range of sports, including track and field, baseball, ice hockey, tennis, association football (soccer), lacrosse, basketball, and cricket. Nike Air Max is a line of shoes first released by Nike, Inc. in 1987. Additional product lines were introduced later, such as Air Huarache, which debuted in 1992. The most recent additions to their line are the Nike 6.0, Nike NYX, and Nike SB shoes, designed for skateboarding. Nike has recently introduced cricket shoes called Air Zoom Yorker, designed to be 30% lighter than their competitors'.[49] In 2008, Nike introduced the Air Jordan XX3, a high-performance basketball shoe designed with the environment in mind.</p>
				<p><a href="blog2.html">Read more >> </a></p>
			</article>
		</section>
		<footer>
			<p>Legal disclaimer, copyright, etc.</p>
			<ul>
				<li><a href="#"> About us</a></li>
				<li><a href="#">Contact us</a></li>
				<li><a href="#"> Privacy policy</a></li>
				<li><a href="#"> cookies statement</a></li>
				<li><a href="#">Developers </a></li>
			</ul>
		</footer>
	</div>
</body>
</html>
