# AlexandriaProject
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: "Times New Roman", Times;
}


.header {
  background-color: #f1f1f1;
  padding: 30px;
  text-align: center;
  font-size: 35px;
}

.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  height: 300px; 
}


.row:after {
  content: "";
  display: table;
  clear: both;
}


.footer {
  background-color: #f1f1f1;
  padding: 10px;
  text-align: center;
}

@media (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Who Destroyed The Library of Alexandria?</h2>
<p>Click on an image to see the evidence against each suspect</p>


<div class="header">
  <h2>The Suspects</h2>
</div>

<div class="row">
  
<div class="column" style="background-color:#aaa;"> <a href="file:///C:/Users/Charlie/Desktop/Latin%20Project/Caesar.html">
<img alt="Caesar" src="https://bit.ly/3iq8ezp" width=610" height="280"> 
</a> <p>Julius Caesar</p> </div>
 
<div class="column" style="background-color:#bbb;"><a href="file:///C:/Users/Charlie/Desktop/Latin%20Project/Christians.html">
<img alt="Christians" src="https://bit.ly/3qAHiQ8" width=610" height="280"> </a> <p>The fourth century Christians</p> </div>
  
<div class="column" style="background-color:#ccc;"> <a href="file:///C:/Users/Charlie/Desktop/Latin%20Project/Omar.html">
<img alt="Omar" src="https://bit.ly/35SQrf0" width=610" height="280"> </a> <p>Omar</p> </div>
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<style>
.button {
  background-color: #4CAF50;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
</style>

<center>
<a href="file:///C:/Users/Charlie/Desktop/Latin%20Project/BackgroundInfo.html" class="button">Click here for background information</a>
</center>



</body>
</html>
