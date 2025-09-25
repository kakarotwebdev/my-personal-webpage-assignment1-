html 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MY PERSONAL WEBPAGE</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1> My Personal Webpage </h1>
<div class="image">
  <img src="image 1/Pictures/paspport.jpg" alt="profile">
</div>
<div class="details">
  <div>
  <h3>Name </h3>
  <p> Sameer </p>
  <h3> Program</h3>
  <p>ADCS</p>
  <h3> Semester </h3>
  <p> 3</p>
  
  </div>
</div>
<hr>
<h2>Favourite Movies</h2>
<ul>
<li>Journey to the center of earth</li>
<li>harrpy potter chamber of secrets</li>
<li>Spider Man</li>

</ul>
<hr>
<a href="https://proteinfactory.com/">Favourite Link</a>
</body>
</html>



CSS


body{
  background-color: beige;
}

.image{
  display: inline-flex;
  align-self:inherit;
  height: 50px;
  width: 50px;
  border-radius: 15px;
}

.details{
  display: inline-flex;
}

a{
  font-style: oblique;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  cursor: pointer;
  border: none;
  
}


