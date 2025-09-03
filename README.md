<!DOCTYPE html>
<head>

<title>Name</title>

<style type="text/css">
html {
    background: white;
    color: black;
    font: 14px 'Helvetica Neue', Arial, sans-serif;
}
body {
    margin: 2em auto;
    max-width: 760px;
    width: 65%;
}
section {
    clear: both;
    margin-top: 3em;
}
li {
    list-style-type: disc;
}
section > ul > li,
header > ul > li {
    list-style-type: none;
    margin-bottom: .5em;
}
.headline-name {
    border-bottom: 1px solid black;
    padding-bottom: .5em;
}
.contact-column {
    float: left;
    padding: 0 1px;
}
a,
a:link,
a:visited {
    border-bottom: 1px dotted rgb(0, 120, 180);
    color: rgb(0, 120, 180);
    padding: .2em .1em;
    text-decoration: none;
}
a:focus,
a:hover,
a:active {
    background-color: rgb(255, 245, 0);
    border-bottom: 1px solid rgb(0, 120, 180);
    color: rgb(0, 120, 180);
}
@media (min-width: 992px) {
    .contact-column {
        margin-left: 1em;
    }
    .contact-column.right {
        float: right;
    }
}
@media (max-width: 776px) {
    ul {
        margin-left: 0;
        margin-right: 0;
        padding-left: 0;
        padding-right: 0;
    }
}
@media print {
    html {
        color: black;
        font-size: 12px;
    }
    body {
        margin: 1.5em;
        width: 90%;
    }
    section {
        margin-top: 1em;
    }
    a,
    a:link,
    a:visited {
        border: none;
        color: black;
    }
}
</style>

</head>
<body>
	<header>
		<h2>Name</h2>
		<ul id="header-left" title="mail and phone">
      <li>Address</li>
			<li>City, State 55555</li>
			<li>Phone</li>
		</ul>
		<ul id="header-right" title="web">
			<li>Email</li>
			<li>Web</li>
			<li>LinkedIn</li>
		</ul>
	</header>
	<section id="education"><h3>Education</h3>
		<ul title="education">
		<li>
			<h4>Degree, Where, When</h4>
        		<ul>
        			<li>Stuff about your degree</li>
       		</ul>
       	</li>
		</ul>
	</section>
	<section id="skills"><h3>Skills</h3>
		<ul title="skills">
			<li>Skill 1</li>
      <li>Skill 2</li>
		</ul>
	</section>
	<section id="experience"><h3>Experience</h3>
	<ul title="experience">
		<li>
			<h4>Job Title, Place, Time</h4>
			<ul>
				<li>Stuff you did</li>
			</ul>
		</li>
	</ul>
	</section>
</body>
</html>
