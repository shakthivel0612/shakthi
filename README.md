<!DOCTYPE html> 
<html> 
 <head> 
 <meta charset="utf-8"> 
 <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"> 
<title>BUS - Travel and Tour</title> 
 
 <meta name="description" content=""> 
 <meta name="viewport" content="width=device-width, initial-scale=1"> 
<link rel="apple-touch-icon" href="apple-touch-icon.png"> 
 <link rel="stylesheet" href="css/bootstrap.min.css"> 
 <link rel="stylesheet" href="css/bootstrap-theme.min.css"> 
 <link rel="stylesheet" href="css/fontAwesome.css"> 
 <link rel="stylesheet" href="css/hero-slider.css"> 
 <link rel="stylesheet" href="css/owl-carousel.css"> 
 <link rel="stylesheet" href="css/datepicker.css"> 
 <link rel="stylesheet" href="css/tooplate-style.css"> 
 <link 
href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700 
,800" rel="stylesheet"> 
 <script src="js/vendor/modernizr-2.8.3-respond-1.4.2.min.js"></script> 
</head> 
<body> 
 
 <section class="banner" id="top"> 
 <div class="container"> 
18 | P a g e
 <div class="row"> 
 <div class="col-md-5"> 
 <div class="left-side"> 
 <div class="logo"> 
 <img src="img/logo2.jpg" alt="BUS Template"> 
 </div> 
 <div class="tabs-content"> 
 <h4>Choose Your Direction:</h4> 
 <ul class="social-links"> 
 <li><a href="http://facebook.com">Find us on 
<em>Facebook</em><i class="fa fa-facebook"></i></a></li> 
 <li><a href="http://youtube.com">Our <em>YouTube</em> 
Channel<i class="fa fa-youtube"></i></a></li> 
 <li><a href="http://instagram.com">Follow our 
<em>instagram</em><i class="fa fa-instagram"></i></a></li> 
 </ul> 
 </div> 
 <div class="page-direction-button"> 
 <a href="contact.html"><i class="fa fa-phone"></i>Contact Us 
Now</a> 
 </div> 
 </div> 
 </div> 
 <div class="col-md-5 col-md-offset-1"> 
 <section id="first-tab-group" class="tabgroup"> 
 <div id="tab1"> 
 <div class="submit-form"> 
 <h4>Check availability for <em>direction</em>:</h4> 
 <form id="form-submit" action="" method="get"> 
 <div class="row"> 
 <div class="col-md-6"> 
 <fieldset> 
 <label for="from">From:</label> 
<select required name='from' 
19 | P a g e
onchange='this.form.()'> 
 <option value="">Select a location...</option> 
<option value="Tirupathi">Tirupathi</option> 
 <option value="Banglore">Banglore</option> 
<option value="Kerela">Kerela</option>
<option value="Delhi">Delhi</option> 
<option value="cochin">Cochin</option> 
<option value="Madurai">Madurai</option> 
<option value="Chennai">Chennai</option> 
<option value="Hydrabad">Hydrabad</option> 
<option value="Manglore">Manglore</option> 
<option value="Mysore">Mysore</option> 
 </select> 
 </fieldset> 
 </div> 
 <div class="col-md-6"> 
 <fieldset> 
 <label for="to">To:</label> 
<select required name='to' onchange='this.form.()'> 
 <option value="">Select a location...</option> 
<option value="Tirupathi">Tirupathi</option> 
<option value="Banglore">Banglore</option> 
 <option value="Kerela">Kerela</option> 
 <option value="Delhi">Delhi</option> 
<option value="Cochin">Cochin</option> 
 <option value="Madurai">Madurai</option> 
 <option value="Chennai">Chennai</option> 
<option value="Hydrabad">Hydrabad</option> 
<option value="Manglore">Manglore</option> 
<option value="Mysore">Mysore</option> 
 </select> 
 </fieldset> 
 </div> 
 <div class="col-md-6"> 
20 | P a g e
 <fieldset> 
 <label for="departure">Departure date:</label> 
<input name="deparure" type="text" class="formcontrol date" id="deparure" 
placeholder="Select date..." required="" onchange='this.form.()'> 
 </fieldset> 
 </div> 
 <div class="col-md-6"> 
 <fieldset> 
 <label for="return">Return date:</label> 
 <input name="return" type="text" 
class="formcontrol date" id="return" placeholder="Select date..." 
required="" onchange='this.form.()'> 
 </fieldset> 
 </div> 
 <div class="col-md-6"> 
 <div class="radio-select"> 
 <div class="row"> 
 <div class="col-md-6 col-sm-6 col-xs-6"> 
 <label for="round">Round</label> 
 <input type="radio" name="trip" id="round" 
value="round" required="required"onchange='this.form.()'> 
 </div> 
 <div class="col-md-6 col-sm-6 col-xs-6"> 
 <label for="oneway">Oneway</label> 
<input type="radio" name="trip" id="oneway" 
value="one-way" required="required"onchange='this.form.()'> 
 </div> 
 </div> 
 </div> 
 </div> 
 <div class="col-md-6"> 
 <fieldset> 
 <button type="submit" id="form-submit" 
21 | P a g e
class="btn" ><a 
href='C:\Users\ROKESH\Desktop\web\PNflight\login\index.html';">>Order 
Ticket Now</a></button> 
 </fieldset> 
 </div> 
 </div> 
 </form> 
 </div> 
 </div> 
 </section> 
 </div> 
 </div> 
 </div> 
 </section> 
 <div class="tabs-content" id="weather"> 
 <div class="container"> 
 <div class="row"> 
 <div class="col-md-12"> 
 <div class="section-heading"> 
 <h2>Check Weather For 5 NEXT Days</h2> 
 </div> 
 </div> 
 <div class="wrapper"> 
 <div class="col-md-12"> 
 <div class="weather-content"> 
 <div class="row"> 
 <div class="col-md-12"> 
 <ul class="tabs clearfix" data-tabgroup="second-tabgroup"> 
 <li><a href="#monday" class="active">Monday</a></li> 
 <li><a href="#tuesday">Tuesday</a></li> 
22 | P a g e
 <li><a href="#wednesday">Wednesday</a></li> 
 <li><a href="#thursday">Thursday</a></li> 
 <li><a href="#friday">Friday</a></li> 
 </ul> 
 </div> 
 <div class="col-md-12"> 
 <section id="second-tab-group" class="weathergroup"> 
 <div id="monday"> 
 <div class="row"> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>TIRUPATHI</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-03.png" alt=""> 
</div> 
 <span>32&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>26&deg;</span></li> 
<li>12PM <span>32&deg;</span></li> 
<li>6PM <span>28&deg;</span></li> 
<li>12AM <span>22&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
<div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>BANGLORE</h6> 
<div class="weather-icon"> 
 <img src="img/weather-icon-02.png" alt=""> 
</div> 
 <span>28&deg;C</span> 
 <ul class="time-weather"> 
 <li>6AM <span>20&deg;</span></li> 
<li>12PM <span>28&deg;</span></li> 
23 | P a g e
 <li>6PM <span>26&deg;</span></li> 
 <li>12AM <span>18&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
<div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>KERALA</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-01.png" alt=""> 
</div> 
 <span>33&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>26&deg;</span></li> 
<li>12PM <span>33&deg;</span></li> 
<li>6PM <span>29&deg;</span></li> 
<li>12AM <span>27&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
 </div> 
 </div> 
 <div id="tuesday"> 
 <div class="row"> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>TIRUPATHI</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-02.png" alt=""> 
</div> 
 <span>28&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>18&deg;</span></li> 
 <li>12PM <span>27&deg;</span></li> 
24 | P a g e
 <li>6PM <span>25&deg;</span></li>
<li>12AM <span>17&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
<h6>BANGLORE</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-03.png" alt=""> 
</div> 
 <span>31&deg;C</span> 
 <ul class="time-weather"> 
 <li>6AM <span>19&deg;</span></li> 
<li>12PM <span>28&deg;</span></li> 
 <li>6PM <span>22&deg;</span></li> 
 <li>12AM <span>18&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
<div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>KERALA</h6> 
<div class="weather-icon"> 
 <img src="img/weather-icon-01.png" alt=""> 
</div> 
 <span>26&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>19&deg;</span></li> 
 <li>12PM <span>26&deg;</span></li> 
<li>6PM <span>22&deg;</span></li> 
<li>12AM <span>20&deg;</span></li> 
 </ul> 
 </div> 
25 | P a g e
 </div> 
 </div> 
 </div> 
 <div id="wednesday"> 
 <div class="row"> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>TIRUPATHI</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-03.png" alt=""> 
</div> 
 <span>31&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>19&deg;</span></li> 
<li>12PM <span>28&deg;</span></li> 
<li>6PM <span>22&deg;</span></li> 
 <li>12AM <span>18&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>BANGLORE</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-01.png" alt=""> 
</div> 
 <span>34&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>28&deg;</span></li> 
<li>12PM <span>34&deg;</span></li> 
<li>6PM <span>30&deg;</span></li> 
<li>12AM <span>29&deg;</span></li> 
 </ul> 
 </div> 
26 | P a g e
 </div> 
<div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>KERALA</h6> 
<div class="weather-icon"> 
 <img src="img/weather-icon-02.png" alt=""> 
</div> 
 <span>28&deg;C</span> 
<ul class="time-weather"> 
<li>6AM <span>18&deg;</span></li> 
 <li>12PM <span>27&deg;</span></li> 
<li>6PM <span>25&deg;</span></li> 
 <li>12AM <span>17&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
 </div> 
 </div> 
 <div id="thursday"> 
 <div class="row"> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>TIRUPATHI</h6> 
<div class="weather-icon"> 
 <img src="img/weather-icon-01.png" alt=""> 
</div> 
 <span>27&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>21&deg;</span></li> 
<li>12PM <span>27&deg;</span></li> 
<li>6PM <span>22&deg;</span></li> 
<li>12AM <span>18&deg;</span></li> 
 </ul> 
 </div> 
27 | P a g e
 </div> 
<div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>BANGLORE</h6> 
<div class="weather-icon"> 
 <img src="img/weather-icon-02.png" alt=""> 
</div> 
 <span>28&deg;C</span> 
<ul class="time-weather"> 
 <li>6AM <span>18&deg;</span></li> 
<li>12PM <span>27&deg;</span></li> 
 <li>6PM <span>25&deg;</span></li> 
 <li>12AM <span>17&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>KERELA</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-03.png" alt=""> 
</div> 
 <span>31&deg;C</span> 
 <ul class="time-weather"> 
 <li>6AM <span>19&deg;</span></li> 
<li>12PM <span>28&deg;</span></li> 
<li>6PM <span>22&deg;</span></li> 
<li>12AM <span>18&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
 </div> 
 </div> 
 <div id="friday"> 
28 | P a g e
 <div class="row"> 
 <div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>TIRUPATHI</h6> 
 <div class="weather-icon"> 
 <img src="img/weather-icon-03.png" alt=""> 
</div> 
 <span>33&deg;C</span> 
 <ul class="time-weather"> 
 <li>6AM <span>28&deg;</span></li> 
 <li>12PM <span>33&deg;</span></li> 
<li>6PM <span>29&deg;</span></li> 
 <li>12AM <span>27&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
<div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>BANGLORE</h6> 
<div class="weather-icon"> 
 <img src="img/weather-icon-02.png" alt=""> 
</div> 
 <span>31&deg;C</span> 
 <ul class="time-weather"> 
 <li>6AM <span>24&deg;</span></li> 
<li>12PM <span>31&deg;</span></li> 
<li>6PM <span>26&deg;</span></li> 
<li>12AM <span>23&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
<div class="col-md-4"> 
 <div class="weather-item"> 
 <h6>KERELA</h6> 
29 | P a g e
 <div class="weather-icon"> 
 <img src="img/weather-icon-01.png" alt=""> 
</div> 
 <span>28&deg;C</span> 
 <ul class="time-weather"> 
 <li>6AM <span>24&deg;</span></li> 
 <li>12PM <span>28&deg;</span></li> 
 <li>6PM <span>26&deg;</span></li> 
<li>12AM <span>22&deg;</span></li> 
 </ul> 
 </div> 
 </div> 
 </div> 
 </div> 
 </section> 
 </div> 
 </div> 
 </div> 
 </div> 
 </div> 
 </div> 
 </div> 
 </div> 
 <section id="most-visited"> 
 <div class="container"> 
 <div class="row"> 
 <div class="col-md-12"> 
 <div class="section-heading"> 
 <h2>Most Visited Places</h2> 
 </div> 
 </div> 
 <div class="col-md-12"> 
 <div id="owl-mostvisited" class="owl-carousel owl-theme"> 
 <div class="item col-md-12"> 
30 | P a g e
 <div class="visited-item"> 
 <img src="img/taj.jfif" alt=""> 
 <div class="text-content"> 
 <h4>Taj Mahal</h4> 
 <span>New Delhi</span> 
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/tirupathi1.jpg" alt=""> 
 <div class="text-content"> 
 <h4>Tirumal Temple</h4> 
<span>Tirupathi</span>
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/cubbon.jpg" alt=""> 
 <div class="text-content"> 
<h4>Cubbon Park</h4> 
 <span>Bangalore</span> 
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/mp1.jpg" alt=""> 
 <div class="text-content"> 
 <h4>Mysore Palace</h4> 
 <span>Mysore</span> 
 </div> 
 </div> 
31 | P a g e
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/marina.jpg" alt=""> 
 <div class="text-content"> 
 <h4>Marina Beach</h4> 
 <span>Chennai</span> 
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/hs.jpg" alt=""> 
 <div class="text-content"> 
<h4>HussainSagar Statue</h4> 
 <span>Hydrabad</span> 
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/mm.jpg" alt=""> 
 <div class="text-content"> 
 <h4>Menatchi Amman koil</h4> 
 <span>Madurai</span> 
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/ernakulam.jpg" alt=""> 
 <div class="text-content"> 
 <h4>Ernakulam Beach</h4> 
 <span>kochi</span> 
32 | P a g e
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/pb1.jpg" alt=""> 
 <div class="text-content"> 
 <h4>Panambur Beach</h4> 
 <span>MANGLORE</span> 
 </div> 
 </div> 
 </div> 
 <div class="item col-md-12"> 
 <div class="visited-item"> 
 <img src="img/ap fall.jpg" alt=""> <div 
class="text-content">
 <h4>Athirapalli Water Fall</h4> 
 <span>kerala</span> 
 </div> 
 </div> 
 </div> 
 </div> 
 </div> 
 </div> 
 </div> 
 </section> 
 <footer> 
 <div class="container"> 
 <div class="row"> 
 <div class="col-md-12"> 
 <div class="primary-button"> 
33 | P a g e
 <a href="#" class="scroll-top">Back To Top</a> 
 </div> 
 </div> 
 <div class="col-md-12"> 
 <ul class="social-icons"> 
 <li><a href="https://www.facebook.com/tooplate"><i class="fa 
fafacebook"></i></a></li> 
 <li><a href="#"><i class="fa fa-twitter"></i></a></li> 
 <li><a href="#"><i class="fa fa-linkedin"></i></a></li> 
 <li><a href="#"><i class="fa fa-rss"></i></a></li> 
 <li><a href="#"><i class="fa fa-behance"></i></a></li> 
 </ul> 
 </div> 
 <div class="col-md-12"> 
 <p>Copyright &copy; vishnu 
 
 | Design: <a href="#" target="_parent"><em>vishnu</em></a></p> 
 </div> 
 </div> 
 </div> 
 </footer> 
 
 <script 
src="//ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script> 
 <script>window.jQuery || document.write('<script src="js/vendor/jquery1.11.2.min.js"><\/script>')</script> 
 <script src="js/vendor/bootstrap.min.js"></script> 
 
 <script src="js/datepicker.js"></script> 
34 | P a g e
 <script src="js/plugins.js"></script> 
 <script src="js/main.js"></script> 
 <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js" 
type="text/javascript"></script> 
 <script type="text/javascript"> 
 $(document).ready(function() { 
 
 // navigation click actions 
 $('.scroll-link').on('click', function(event){ 
event.preventDefault(); var sectionID = 
$(this).attr("data-id"); 
 scrollToID('#' + sectionID, 750); 
 }); 
 // scroll to top action 
 $('.scroll-top').on('click', function(event) { 
event.preventDefault(); 
 $('html, body').animate({scrollTop:0}, 'slow'); 
 }); 
 // mobile nav toggle 
 $('#nav-toggle').on('click', function (event) { 
event.preventDefault(); 
 $('#main-nav').toggleClass("open"); 
 }); 
 }); 
 // scroll function 
 function scrollToID(id, speed){ 
 var offSet = 0; 
 var targetOffset = $(id).offset().top - offSet; 
 var mainNav = $('#main-nav'); 
 $('html,body').animate({scrollTop:targetOffset}, speed); 
if (mainNav.hasClass("open")) { 
35 | P a g e
 mainNav.css("height", "1px").removeClass("in").addClass("collapse"); 
mainNav.removeClass("open"); 
 } 
 } 
 if (typeof console === "undefined") { 
 console = { 
 log: function() { } 
 }; 
 } 
 </script> 
</body> 
</html>
