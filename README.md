# kaolinhida.github.io

<!DOCTYPE html>
<html lang="en">
<title>Måneskin</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: "Lato", sans-serif}
.mySlides {display: none}
</style>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-black w3-card">
    <a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">HOME</a>
    <a href="#gang" class="w3-bar-item w3-button w3-padding-large w3-hide-small">ABOUT GANG</a>
    <a href="#participants" class="w3-bar-item w3-button w3-padding-large w3-hide-small">POPULAR PARTICIPANTS</a>
    <a href="#photographic" class="w3-bar-item w3-button w3-padding-large w3-hide-small">PHOTOGRAPHIC FILM</a>
    </div>
    <a href="javascript:void(0)" class="w3-padding-large w3-hover-red w3-hide-small w3-right"><i class="fa fa-search"></i></a>
</div>

<!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
<div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
  <a href="#gang" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">BAND</a>
  <a href="#participants" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">POPULAR PARTICIPANTS</a>
  <a href="#photographic" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">PHOTOGRAPHIC FILM</a>
<!--   <a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">MERCH</a> -->
</div>

<!-- Page content -->
<div class="w3-content" style="max-width:2024px;margin-top:46px">

  <!-- Automatic Slideshow Images -->
  <div class="mySlides w3-display-container w3-center">
    <img src="https://cutt.ly/QnWjizA" style="width:100%">
    <div class="w3-display-bottommiddle w3-container w3-text-white w3-padding-32 w3-hide-small">
      <h3>Участники банди на з'їзді</h3>
    </div>
  </div>
  <div class="mySlides w3-display-container w3-center">
    <img src="https://cutt.ly/cnWjzOB" style="width:100%">
    <div class="w3-display-bottommiddle w3-container w3-text-white w3-padding-32 w3-hide-small">
      <h3>Обурення з'їзду на рішення голови</h3>   
    </div>
  </div>
  <div class="mySlides w3-display-container w3-center">
    <img src="https://cutt.ly/knWjEBw" style="width:100%">
    <div class="w3-display-bottommiddle w3-container w3-text-white w3-padding-32 w3-hide-small">
      <h3>Фото Карліона Гранде</h3>     
       </div>
  </div>
  <script>
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 4000);    
}
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
var modal = document.getElementById('ticketModal');
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>

  


  <!-- The Gang Section -->
  <div class="w3-container w3-content w3-center w3-padding-64" style="max-width:800px" id="band">
    <h2 class="w3-wide">Grove Street Families</h2>
    <p class="w3-opacity"><i>You still talk shit</i></p>
    <p class="w3-justify"> Банда сформувалася в районі Гентон, приблизно в 60-х роках (можливо - раніше), і є найстарішою бандою в Лос-Сантосі. 
	Вони зайняли всі сусідні території, але в Східному Лос-Сантосі Grove Street Families зіткнулися з бандою Ballas, яка згодом стала їх кровним ворогом.
    <div class="w3-row w3-padding-64">


   
</body> 
  <div class="w3-black" id="participants">
    <!-- foto steak -->
<div class="w3-container">
 <h2 class="w3-center"> Найвідоміші учасники банди:</h2>
<div class="gallery">
  <a target="_blank" href="https://cutt.ly/0nWkhUq">
    <img src="https://cutt.ly/0nWkhUq" "width:100%">
  </a>
   <div class="w3-container w3-center">
   <div class="w3-serif">Права рука Мелвін Харріс</div></div>
</div>
<div class="gallery">
  <a target="_blank" href="https://cutt.ly/anWkvEF">
   <img src="https://cutt.ly/anWkvEF"  width="600" height="400">
  </a>
   <div class="w3-container w3-center">
  <div class="w3-serif">Колишній очільник Шон Джонссон</div> </div>
</div>
<div class="gallery">
  <a target="_blank" href="https://cutt.ly/TnWkYs2">
    <img src="https://cutt.ly/TnWkYs2"   width="600" height="400">
  </a>  
    <div class="w3-container w3-center">
  <div class="w3-serif">Лідер банди Карл Джонссон</div> </div>
  <div class="gallery">
  <a target="_blank" href="https://cutt.ly/cnWkFfp">
    <img src="https://cutt.ly/cnWkFfp"   width="600" height="400">
  </a>  
    <div class="w3-container w3-center">
  <div class="w3-serif">Ділер Ленс Уілсон</div> </div>
</div>
</div>
</div>
</div>
     
    
  <!-- Accordion -->
 <body>

</div>
<script>
function myFunction(id) {
  var x = document.getElementById(id);
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>
   
  </div>

  <!-- Найвідоміші учасники банди -->
  <div id="ticketModal" class="w3-modal">
    <div class="w3-modal-content w3-animate-top w3-card-4">
      <header class="w3-container w3-teal w3-center w3-padding-32"> 
        <span onclick="document.getElementById('ticketModal').style.display='none'" 
       class="w3-button w3-teal w3-xlarge w3-display-topright">×</span>
        <h2 class="w3-wide"><i class="fa fa-suitcase w3-margin-right"></i>Tickets</h2>
      </header>
         <!-- foto steak -->
<div class="w3-container">
 <h2 class="w3-center"> Найвідоміші учасники банди:</h2>
<div class="gallery">
  <a target="_blank" href="https://cutt.ly/0nWkhUq">
    <img src="https://cutt.ly/0nWkhUq" width="600" height="400">
  </a>
   <div class="w3-container w3-center">
   <div class="w3-serif">Права рука Мелвін Харріс</div></div>
</div>
<div class="gallery">
  <a target="_blank" href="https://cutt.ly/anWkvEF">
   <img src="https://cutt.ly/anWkvEF"  width="600" height="400">
  </a>
   <div class="w3-container w3-center">
  <div class="w3-serif">Колишній очільник Шон Джонссон</div> </div>
</div>
<div class="gallery">
  <a target="_blank" href="https://cutt.ly/TnWkYs2">
    <img src="https://cutt.ly/TnWkYs2"   width="600" height="400">
  </a>  
    <div class="w3-container w3-center">
  <div class="w3-serif">Лідер банди Карл Джонссон</div> </div>
  <div class="gallery">
  <a target="_blank" href="https://cutt.ly/cnWkFfp">
    <img src="https://cutt.ly/cnWkFfp"   width="600" height="400">
  </a>  
    <div class="w3-container w3-center">
  <div class="w3-serif">Ділер Ленс Уілсон</div> </div>
</div>
</div>
</div>
</div>
     
    </div>
  </div>

  <!-- The Contact Section -->
  <div class="w3-container w3-content w3-padding-64" style="max-width:100%" id="photo">
    <h2 class="w3-wide w3-center">Фотоплівка Карліона Гранде</h2>
    <!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main w3-content" style="max-width:2024px;margin-top:83px">
  

  
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}
</style>
<body class="w3-light-grey w3-content" style="max-width:1600px">
  <!-- First Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://cutt.ly/0nWlTuL" alt="Norway" style="width:100%" class="w3-hover-opacity">
           <div class="w3-container w3-white"> 
      <p><b></b></p>
        <p></p> 
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://cutt.ly/DnWlOBC" alt="Norway" style="width:100%" class="w3-hover-opacity">
           <div class="w3-container w3-white"> 
      <p><b></b></p>
        <p></p> 
      </div>
    </div>
    <div class="w3-third w3-container">
      <img src="https://cutt.ly/knWlKMj" alt="Norway" style="width:100%" class="w3-hover-opacity">
        <div class="w3-container w3-white"> 
      <p><b></b></p>
        <p></p> 
      </div>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://cutt.ly/bnWlNeg" alt="Norway" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
        <p><b></b></p>
        <p></p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="https://cutt.ly/FnWl9u5" alt="Norway" style="width:100%" class="w3-hover-opacity">
    <div class="w3-container w3-white"> 
      <p><b></b></p>
        <p></p> 
      </div>
    </div>
    <div class="w3-third w3-container">
      <img src="https://cutt.ly/EnWl7C2" alt="Norway" style="width:100%" class="w3-hover-opacity">
       <div class="w3-container w3-white"> 
      <p><b></b></p>
        <p></p> 
  </div>
    </div>
  </div>
