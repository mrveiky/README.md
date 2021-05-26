<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Selinvictor&show_icons=true&count_private=true&include_all_commits=true&hide_border=true"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Selinvictor&layout=compact&count_private=true&include_all_commits=true&hide_border=true&langs_count=10"/>
</p>

<h1 align="center">Hello</h1>

I like minecraft

### Contact

<p>
  <img src="https://media.discordapp.net/attachments/738419713255931987/846505423669428227/20210525_004954.gif" width="32" /> <br />
  <b>Discord</b>: The Evil#7054 <br />
  <img src="https://icongr.am/fontawesome/envelope-o.svg?size=32&color=2198c0" width="32" /> <br />
  <b>Mail</b>: 
</p>
  text-decoration: none;
  font-size: 17px;
}
​
.navbar a:hover {
  background-color: #ddd;
  color: black;
}
​
.navbar a.active {
  background-color: #04AA6D;
  color: white;
}
​
.navbar .icon {
  display: none;
}
​
@media screen and (max-width: 600px) {
  .navbar a:not(:first-child) {display: none;}
  .navbar a.icon {
    float: right;
    display: block;
  }
}
​
@media screen and (max-width: 600px) {
  .navbar.responsive .icon {
    position: absolute;
    right: 0;
    bottom:0;
  }
  .navbar.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
​
}
</style>
</head>
<body>
​
<div class="navbar" id="myNavbar">
  <a href="#home" class="active">Home</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
  <a href="#about">About</a>
  <a href="javascript:void(0);" style="font-size:15px;" class="icon" onclick="myFunction()">&#9776;</a>
</div>
​
<div style="padding-left:16px">
  <h2>Responsive Bottom Navbar Example</h2>
  <p>Resize the browser window to see how it works.</p>
</div>
​
<script>
function myFunction() {
  var x = document.getElementById("myNavbar");
  if (x.className === "navbar") {
    x.className += " responsive";
  } else {
    x.className = "navbar";
  }
}
</script>
​
</body>
