
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<!--
  <script>
    function myFunction() {
    document.getElementById("photoslink").style.color = "yellow";
    }
    function myFunction2() {
    document.getElementById("photoslink").style.color = "white";
    }
  </script>
-->
  <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-121420262-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-121420262-1');
</script>

<style>
body, html {
  height: 100%;
  margin: 0;
  font: 400 15px/1.8 "Lato", sans-serif;
  color: #777;
}
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  right: 71%;
}

/* Position the "next button" to the right */
.next {
  right: 25%;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
  left: 25%
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
.bgimg-1, .bgimg-2, .bgimg-3, .content {
  position: relative;
  opacity: 0.65;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

}
.bgimg-1 {
  background-image: url("background.jpg");
  height: 100%;
  background-attachment: fixed;
}
  .content {
    background-color: #656565
;
    position: relative;
  }
.caption {
  position: absolute;
  left: 0;
  top: 20%;
  width: 100%;
  text-align: center;
  color: #000;
}
  h1 {
  letter-spacing: 5px;
  font: 20px "Lato", sans-serif;
  color: #111;
  }
.caption span.border {
  background-color: #111;
  color: #fff;
  padding: 10px;
  font-size:20px;
  letter-spacing: 10px;
}
.centered {
    position: absolute;
    top: 300%;
    left: 30%;
    transform: translate(-50%, -50%);
    color: white;
    background-color: #101010;
    padding-left: 2%;
    padding-right: 2%;
}
.centered2 {
    position: absolute;
    top: 262%;
    left: 70%;
    transform: translate(-50%, -50%);
    color: white;
    background-color: #101010;
    padding-left: 2%;
    padding-right: 2%;
    width: 453.27px;
}
  .centered3 {
    position: absolute;
    top: 470%;
    left: 70%;
    transform: translate(-50%, -50%);
    color: white;
    background-color: #101010;
    padding-left: 2%;
    padding-right: 2%;
    width: 453.27px;
}
  .centered4 {
    position: absolute;
    top: 96%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    background-color: #656565;
    padding-left: 2%;
    padding-right: 2%;
    width: 453.27px;

}
h3 {
  letter-spacing: 5px;
  text-transform: uppercase;
  font: 20px "Lato", sans-serif;
  color: #111;
}
  .masterbox {
    
  }
</style>
</head>
<body>
<div class="bgimg-1">
  <div class="caption">
    <span class="border">Scarecrow Row</span><br>
    <span class="border">Lunken Airport and Armleader Park</span><br><br>
    <div class="larger">
    </div>
<!--
  <div class=masterbox>
    <div class="centered"><span style="font-size: 25px; letter-spacing: 10px;">Sign Up</span>
      <form method="POST" name="sign up" action="https://formspree.io/3jbc22@gmail.com">
          <input type="text" name="name" id="name" placeholder="Your name" style="background-color: skyblue;" required><input  style="background-color: skyblue;" type="email" id="email" name="email" placeholder="Your email" required><br>
          <input type="tel" name="Tel" id="Tel" placeholder="Your Phone Number"><input type="text" id="SM" name="SM" placeholder="Social Media"><br>
          <textarea name="comments" id="comments" rows="10" cols="30" placeholder="you have 400 characters to describe your scarecrow" maxlength="400" style="background-color: skyblue;"  required></textarea><br>
        <label>Where would you like your scarecrow to be located?</label>  <br>
        <select name="location" style="background-color: skyblue;"  required>
            <option value="Lunken">Lunken Loop</option>
            <option value="Arm">Armleader Trail</option>
            <option value="Connector">Lunken/Armleader connector</option>
            <option value="Don't Care">Don't Care</option>
          </select><br>
          <label>Have you participated in the past?</label>
          <input type="radio" name="Past_Participation" value="Yes"> Yes
          <input type="radio" name="Past_Participation" value="No"> No<br>
          <label>Upload Pictures (if you have any):</label><br>
          <input type="file" name="images" multiple>
          <br><button type="submit">Finish</button><br>
          <label style="color: skyblue;" >required fields</label>
      </form>
      </div>
    
      <div class="centered2"><span style="font-size: 25px; letter-spacing: 10px;">Contact</span>
      <form method="POST" name="contact" action="https://formspree.io/3jbc22@gmail.com">
          <input type="text" name="name" style="background-color: skyblue;"  id="name" placeholder="Your name" required><input style="background-color: skyblue;"  type="email" id="email" name="email" placeholder="Your email" required><br>
          <label>Why are you contacting us?</label>
        <select name="reason" id="reason" style="background-color: skyblue;"  required>
            <option value="Select...">Select...</option>
            <option value="Complaint">Complaint</option>
            <option value="Compliment">Compliment</option>
            <option value="Volunteer">Volunteer</option>
            <option value="Remove sign up">Remove your sign up</option>
            <option value="Remove sign up">Other</option>
          </select><br>
          <textarea name="comments" style="background-color: skyblue;"  id="comments" rows="10" cols="30" placeholder="you have 400 characters to elaborate" maxlength="400"></textarea><br>
          <label>Are you a participant?</label>
          <input type="radio" name="Past_Participation" value="Yes"> Yes
          <input type="radio" name="Past_Participation" value="No"> No
          <br><input type="file" name="images" multiple>
          <br><button type="submit">Finish</button><br>
          <label style="color: skyblue;" >required fields</label>
      </form>
      </div>
    <a href="photos.md">
      <div class="centered3" onMouseover ="myFunction2()" onMouseover="myFunction()" id="photoslink"><span style="font-size: 25px; letter-spacing: 10px;">Photos</span>
        
      </div>
    </a>
    </div>
-->
    <div class="slideshow-container">

    <footer>
<div class="mySlides fade">
  <div class="numbertext">1 / 9</div>
  <img src="1.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 9</div>
  <img src="2.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 9</div>
  <img src="3.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 9</div>
  <img src="4.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 9</div>
  <img src="5.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 9</div>
  <img src="6.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 9</div>
  <img src="7.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">8 / 9</div>
  <img src="8.jpg" style="width:50%">
  
</div>

<div class="mySlides fade">
  <div class="numbertext">9 / 9</div>
  <img src="9.jpg" style="width:50%">
  
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
  <span class="dot" onclick="currentSlide(5)"></span> 
  <span class="dot" onclick="currentSlide(6)"></span> 
  <span class="dot" onclick="currentSlide(7)"></span> 
  <span class="dot" onclick="currentSlide(8)"></span> 
  <span class="dot" onclick="currentSlide(9)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
  </div>

</div>
<a href="index.md">
  <div class="centered4" onMouseover ="myFunction2()" onMouseover="myFunction()" id="photoslink"><span style="font-size: 25px; letter-spacing: 10px;"><center>Home</center></span>
        
      </div>
    </a>
</body>
</html>