Html file
<!DOCTYPE html>
<html>
<head>
   <title>TasteHub Restaurant</title>
   <link rel="stylesheet" href="style.css">
</head>
 
<body>
 
<header>
   <h1>TasteHub Restaurant</h1>
   <nav>
       <a href="#">Home</a>
       <a href="#menu">Menu</a>
       <a href="#gallery">Gallery</a>
       <a href="#booking">Booking</a>
       <a href="#contact">Contact</a>
   </nav>
</header>
 
<section class="hero">
   <h2>Welcome to TasteHub</h2>
   <p>Delicious Food, Cozy Place</p>
</section>
 
<section id="menu">
   <h2>Our Menu</h2>
   <img src="restaurant.jpg" alt="Menu" width="300">
</section>
 
<section id="gallery">
   <h2>Gallery</h2>
   <img src="gallery.jpg" alt="Restaurant Interior">
<selection id="burger">
<h4>burger</h4>
<img src="burger.jpg">
 
   
</section>
 
<section id="booking">
   <h2>Book a Table</h2>
   <form id="bookingForm">
       <input type="text" placeholder="Your Name" required>
       <input type="number" placeholder="Phone Number" required>
       <input type="date" required>
       <input type="time" required>
       <input type="number" placeholder="No. of People" required>
       <button type="submit">Book Now</button>
   </form>
</section>
 
<section id="contact">
   <h2>Contact Us</h2>
   <p>Email: tastehub@gmail.com</p>
   <p>Phone: 9876543210</p>
</section>
 
<script src="script.js"></script>
 
</body>
</html>
 
 
 
CSS file
body {
   font-family: Arial;
   margin: 0;
}
 
header {
   background: lightpink;
   color: white;
   padding: 15px;
   text-align: center;
}
 
nav a {
   margin: 10px;
   color: white;
   text-decoration: underline;
}
 
.hero {
   background: lightgreen;
   background-size: cover;
   background-position: center;
   color: white;
   padding: 100px;
   text-align: center;
}
 
section {
   padding: 20px;
   text-align: center;
}
 
#gallery img {
   width: 300px;
   height: 200px;
   margin: 10px;
   border-radius: 10px;
}
 
button {
   background: skyblue;
   border: none;
   color: white;
   padding: 10px;
}
 
 
Java script
document. getElementById("bookingForm"). addEventListener ("submit", function(e) {
   e.preventDefault();
   alert ("Table booked successfully!");
});
 
 
 
 # My-project
Web designing 
