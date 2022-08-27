<!DOCTYPE html>

<html>

<head>
	<title>NITR ICS PROJECT</title>

	<style>
		footer {
    width: 100%;
    background-color: #121619;
    color: #fff;
}

:root {
    --color-primary: #0073ff;
    --color-white: #e9e9e9;
    --color-black: #141d28;
    --color-black-1: #212b38;
}
.social_media_part {
    width: 100%;
    height: 200px
}
	:root {
    --color-primary: #0073ff;
    --color-white: #e9e9e9;
    --color-black: #141d28;
    --color-black-1: #212b38;}
		hr {
    display: block;
    unicode-bidi: isolate;
    margin-block-start: 0.5em;
    margin-block-end: 0.5em;
    margin-inline-start: auto;
    margin-inline-end: auto;
    overflow: hidden;
    border-style: inset;
    border-width: 1px;
}
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
			
			justify-content: center;
			align-items: center;
		}

		.logo img {
			width: 48px;
			height: 50px;
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
			background-color:white;
			height: 400px;
		}

		.secondsection {
			background-color:white;
			height: 400px;
		}

		.box-main {
			display: flex;
			justify-content: center;
			align-items: center;
			color: black;
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
			font-family: 'Piazzolla', serif;
			font-weight: bold;
			font-size: 27px;
			color: #28a745;
		}

		.text-small {
			
			font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";
            font-size: 1rem;
            font-weight: 400;
            line-height: 1.5;
            color: #212529;
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
			height: 400px;
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
		*, ::after, ::before {
    box-sizing: border-box;
}
.top_header, .top_header section {
    display: flex;
    align-items: center;
    justify-content: center;
}

.top_header {
    padding: 2rem;
    position: relative;
}
		
	</style>
</head>

<body>
	<nav class="navbar background">
		<ul class="nav-list">
			<div class="logo">
				<img src= "https://clashoftesters.herokuapp.com/images/pics.png">
			</div>
			<li><a href="https://clashoftesters.herokuapp.com/">Home</a></li>
			<li><a href="https://clashoftesters.herokuapp.com/about">About</a></li>
			<li><a href="https://clashoftesters.herokuapp.com/members">Members</a></li>
			<li><a href="https://clashoftesters.herokuapp.com/contact">Contact-us</a></li>
			<li><a href="https://clashoftesters.herokuapp.com/events#">Events</a></li>
			<li><a href="https://clashoftesters.herokuapp.com/mritika">Mrittika</a></li>
			
		</ul>

		<div class="rightNav">
			<input type="text" name="search" id="search">
			<button class="btn btn-sm">Search</button>
		</div>
	</nav>
	<div class="gallery_div">
		<img src="https://clashoftesters.herokuapp.com/static/media/imgb2.bb66c212.jpg" alt="NITR ICS">
	</div>

	<section class="firstsection">
		<div class="box-main">
			<div class="firstHalf">
				<h1 class="text-big" id="web">OUR OBJECTIVES</h1>
				<hr>
				<p class="text-small">
					To provide a platform for delegates and professionals from the fields of material science and technology to gather and advance their knowledge and ideas about the materials. It also works to provide exposure to students on material science & technology and to assist them throughout their journey in this field.
				</p>


			</div>
		</div>
	</section>

	<section class="secondsection">
		<div class="box-main">
			<div class="firstHalf">
				<h1 class="text-big" id="program">
					FLASHBACK FRIDAY
				</h1>
				<hr>
				<p class="text-small">
					Memories are meant to be remembered, because even the bad memories are usually part of something we once thought was good.
					Memory is more indelible than ink. Life must be lived forwards, but it can only be understood backwards, through the experience of oneself and others. There is no definitive roadmap to follow for success, while the road is a huge game of Tetris. The inputs that we manage to get, must be arranged in a suitable way to make them advantageous to us. But it is the inputs that are sometimes very difficult to get owing to certain reasons. To help everyone in this regard, NITR-ICS is going to collect such experiences and words of wisdom from successful ceramists, 
					material scientists and industrialists who have excelled in their fields. It will be a conglomeration of important events in their journey from college to where they are now. All the information will be shared fortnightly through the label “Flashback Friday”.
					Stay tuned for further information.
				</p>


			</div>
		</div>
	</section>

	<section class="section">
		<div class="paras">
			<h1 class="sectionTag text-big">MONDAY MATTER</h1>
			<hr>

			<p class="sectionSubTag text-small">
				Memories are meant to be remembered, because even the bad memories are usually part of something we once thought was good.
				Memory is more indelible than ink. Life must be lived forwards, but it can only be understood backwards, through the experience of oneself and others. 
				There is no definitive roadmap to follow for success, while the road is a huge game of Tetris. The inputs that we manage to get, must be arranged in a suitable way to make them advantageous to us. 
				But it is the inputs that are sometimes very difficult to get owing to certain reasons. To help everyone in this regard, NITR-ICS is going to collect such experiences and words of wisdom from successful ceramists, 
				material scientists and industrialists who have excelled in their fields. 
				It will be a conglomeration of important events in their journey from college to where they are now. All the information will be shared fortnightly through the label “Flashback Friday”. 
				Stay tuned for further information.
			</p>
		</div>
	</section>
	<section class="section">
		<div class="paras">
			<h1 class="sectionTag text-big">INCERS NITR</h1>
			<hr>

			<p class="sectionSubTag text-small">
				Indian Ceramic Society (InCerS) is a non-profit organization established in 1928 under the guidance of Pandit Madan Mohan Malviya with an objective of establishing a network & relationship among all material enthusiasts, industrial professionals and any other people connected to this field. The primary objective of InCerS is to promote advancement in ceramic science, arts and technologies, by bringing into close contact those who are engaged in these pursuits, publishing scientific and technical books and journals, holding annual sessions, discussions, meetings, symposia and exhibitions on the subjects of interest. InCerS, NITR is the student chapter of Indian Ceramic Society which organizes annual events like Mrittika. To be a part of InCerS student chapter one needs to pay a membership amount. Being a part of InCerS student chapter has many benefits like getting huge amount of funds to organize events like MRITTIKA whose budget is more than the annual tech fest of NITR NITR-ICS is the student chapter of InCerS at NIT Rourkela with a total strength of 50+ active members. The club is presided over by Shivam Sharma (3rd year B Tech student) from the Department of Ceramic Engineering, NIT Rourkela. Prof. Shantanu Behera from the Department of Ceramic Engineering who is an esteemed alumnus of NIT Rourkela as well as the current Associate Dean of Alumni relations is the club faculty advisor. The club comes under the Technical society of SAC and is responsible for organising fests and sessionals related to materials science.
			</p>
		</div>
	</section>
	
		
	
	
	 

	
		
		<footer class="background">
			<p class="text-footer">
				Copyright © 2021 NITRICS - All rights reserved
			</p>

	</footer>
</body>

</html>
