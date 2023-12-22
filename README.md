
# Html webpage

Basic html code to create httpd/Apache website.



## Main

To Deploy simple webpage.

```bash
<!DOCTYPE html>

<html>

<head>
	<title>Simple web Development Template</title>

	<style>
		* {
			margin: 0;
			padding: 0;
		}

		.navbar {
			display: flex;
			align-items: center;
			justify-content: center;
			position: sticky;
			top: 0;
			cursor: pointer;
		}

		.background {
			background: black;
			background-blend-mode: darken;
			background-size: cover;
		}

		.nav-list {
			width: 70%;
			display: flex;
			align-items: center;
		}

		.logo {
			display: flex;
			justify-content: center;
			align-items: center;
		}

		.logo img {
			width: 180px;
			border-radius: 50px;
		}

		.nav-list li {
			list-style: none;
			padding: 26px 30px;
		}

		.nav-list li a {
			text-decoration: none;
			color: white;
		}

		.nav-list li a:hover {
			color: grey;
		}

		.rightnav {
			width: 30%;
			text-align: right;
		}

		#search {
			padding: 5px;
			font-size: 17px;
			border: 2px solid grey;
			border-radius: 9px;
		}

		.firstsection {
			background-color: green;
			height: 600px;
		}

		.secondsection {
			background-color: black;
			height: 600px;
		}

		.box-main {
			display: flex;
			justify-content: center;
			align-items: center;
			color: white;
			max-width: 80%;
			margin: auto;
			height: 80%;
		}

		.firsthalf {
			width: 100%;
			display: flex;
			flex-direction: column;
			justify-content: center;
		}

		.secondhalf {
			width: 30%;
		}

		.secondhalf img {
			width: 70%;
			border: 4px solid white;
			border-radius: 150px;
			display: block;
			margin: auto;
		}

		.text-big {
			font-family: 'Roboto', serif;
			font-weight: bold;
			font-size: 35px;
		}

		.text-small {
			font-size: 18px;
		}

		.btn {
			padding: 8px 20px;
			margin: 7px 0;
			border: 2px solid white;
			border-radius: 8px;
			background: none;
			color: white;
			cursor: pointer;
		}

		.btn-sm {
			padding: 6px 10px;
			vertical-align: middle;
		}

		.section {
			height: 600px;
			display: flex;
			align-items: center;
			justify-content: center;
			max-width: 90%;
			margin: auto;
		}

		.section-Left {
			flex-direction: row-reverse;
		}

		.paras {
			padding: 0px 65px;
		}

		.thumbnail img {
			width: 250px;
			border: 2px solid black;
			border-radius: 26px;
			margin-top: 19px;
		}

		.center {
			text-align: center;
		}

		.text-footer {
			text-align: center;
			padding: 30px 0;
			font-family: 'Ubuntu', sans-serif;
			display: flex;
			justify-content: center;
			color: white;
		}
	</style>
</head>

<body>
	<nav class="navbar background">
		<ul class="nav-list">
			<div class="logo">
				<img src= "logo.png">
			</div>
			<li><a href="#AWS">AWS</a></li>
			<li><a href="#Devops">Devops</a></li>
			<li><a href="#Scripting">Scripting</a></li>
		</ul>

		<div class="rightNav">
			<input type="text" name="search" id="search">
			<button class="btn btn-sm">Search</button>
		</div>
	</nav>

	<section class="firstsection">
		<div class="box-main">
			<div class="firstHalf">
				<h1 class="text-big" id="web">Web Technology</h1>
				<p class="text-small">
					Amazon Web Services (AWS) is a comprehensive and widely-used
					cloud computing platform provided by Amazon. It offers a broad
					set of on-demand computing services and resources, allowing 
					businesses and individuals to build and scale applications
					without the need to invest in and maintain physical hardware.
					AWS provides a vast array of services, including computing
					power, storage options, databases, machine learning,
					analytics, security, and more.
				</p>


			</div>
		</div>
	</section>

	<section class="secondsection">
		<div class="box-main">
			<div class="firstHalf">
				<h1 class="text-big" id="Devops">
					Devops
				</h1>
				<p class="text-small">
					DevOps, short for Development and Operations,is a set of
					practices, principles, and cultural philosophies that aim to
					enhance collaboration and communication between software 
					development and IT operations teams. The primary goal of 
					DevOps is to automate and streamline the software development
					lifecycle, enabling organizations to deliver high-quality 
					software applications more quickly, reliably, and efficiently.
				</p>


			</div>
		</div>
	</section>

	<section class="section">
		<div class="paras">
			<h1 class="sectionTag text-big">Scripting</h1>

			<p class="sectionSubTag text-small">
				A scripting language is a type of programming language designed
				for the development of scripts, which are sets of instructions that
				automate the execution of tasks. Unlike compiled languages, where
				code is translated into machine code before execution, scripts are
				typically interpreted at runtime. Scripting languages are often
				used for tasks such as automation, system administration, and rapid
				application development.
			</p>


		</div>

		<div class="thumbnail">
			<img src= "img.png" alt="laptop image">
		</div>
	</section>

	<footer class="background">
		<p class="text-footer">
			Copyright ©2023 privacy policy- Raja Prasad all write reserve.
		</p>


	</footer>
</body>

</html>


```

## Get Into Devops

To Deploy simple "Get Into Devops" page.

```bash
<!doctype html>
<title>Main page</title>
<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,700" rel="stylesheet">
<style>
  html, body { padding: 0; margin: 0; margin-top: 0; margin-bottom: 50px ; margin-left: 80px ; width: 80%; height: 100%; }
  * {border-radius: 30px;}
  body { text-align: left; padding: 30px; background: black; color: greenyellow; font-family: Ubuntu; }
  h1 { font-size: 150px; font-weight: bold; text-align: left; color: greenyellow; font-style: normal;}
  body { font-family: Open sans; font-weight: 300; font-size: 20px; font-style: italic; color: #fff; text-align: left; display: -webkit-box; display: -ms-flexbox; display: flex; -webkit-box-pack: left; -ms-flex-pack: left; justify-content: left; -webkit-box-align: left; -ms-flex-align: left; align-items: left;}
  article { display: block; width: 800px; padding: 0; margin: 0; margin-top: 1em; margin-bottom: 50px ; margin-left: 50px ;}
  a { color: #fff; font-weight: bold;}
  a:hover { text-decoration: none; }
  svg { width: 75px; margin-top: 1em; }
  p {
      line-height: 1.5; /* You can adjust this value */
    }
    h1, h2, h3, h4, h5, h6 {
      line-height: 0.3; /* You can adjust this value */
    }
</style>

<article>
    
    <h1>Get</h1>
    <h1>Into</h1>
    <h1>Devops</h1>
    <div>
        <p>Simplify and automate and streamline the software development lifecycle, enabling organizations to deliver high-quality software applications more quickly, reliably, and efficiently.</p>
        <p>Thank you for visiting! my website .... </p>
        <p>&mdash; The [ prasad.devops.com ] & Team</p>
    </div>
</article>

```
## Error 404

To Deploy 404 error page.

```bash
<!doctype html>
<title>Site Maintenance</title>
<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,700" rel="stylesheet">
<style>
  html, body { padding: 0; margin: 0; width: 100%; height: 100%; }
  * {box-sizing: border-box;}
  body { text-align: center; padding: 0; background: #272929; color: #fff; font-family: Open sans; }
  h1 { font-size: 60px; font-weight: 200; text-align: center;}
  body { font-family: Open sans; font-weight: 200; font-size: 20px; color: #fff; text-align: center; display: -webkit-box; display: -ms-flexbox; display: flex; -webkit-box-pack: center; -ms-flex-pack: center; justify-content: center; -webkit-box-align: center; -ms-flex-align: center; align-items: center;}
  article { display: block; width: 700px; padding: 50px; margin: 0 auto; }
  a { color: #fff; font-weight: bold;}
  a:hover { text-decoration: none; }
  svg { width: 75px; margin-top: 1em; }
</style>

<article>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 202.24 202.24"><defs><style>.cls-1{fill:#fff;}</style></defs><title>Asset 3</title><g id="Layer_2" data-name="Layer 2"><g id="Capa_1" data-name="Capa 1"><path class="cls-1" d="M101.12,0A101.12,101.12,0,1,0,202.24,101.12,101.12,101.12,0,0,0,101.12,0ZM159,148.76H43.28a11.57,11.57,0,0,1-10-17.34L91.09,31.16a11.57,11.57,0,0,1,20.06,0L169,131.43a11.57,11.57,0,0,1-10,17.34Z"/><path class="cls-1" d="M101.12,36.93h0L43.27,137.21H159L101.13,36.94Zm0,88.7a7.71,7.71,0,1,1,7.71-7.71A7.71,7.71,0,0,1,101.12,125.63Zm7.71-50.13a7.56,7.56,0,0,1-.11,1.3l-3.8,22.49a3.86,3.86,0,0,1-7.61,0l-3.8-22.49a8,8,0,0,1-.11-1.3,7.71,7.71,0,1,1,15.43,0Z"/></g></g></svg>
    <h1>404</h1>
    <h1>We&rsquo;ll be back soon!</h1>
    <div>
        <p>Sorry for the inconvenience. we&rsquo;re performing some maintenance at the moment. if you need to you can always follow us on <a href="http://www.twitter.com/">Twitter</a> for further updates, we&rsquo;ll be back up shortly !</p>
        <p>Thanks for visiting!</p>
        <p>&mdash; The [ prasad.devops.com ] Team</p>
        
    </div>
</article>

```
