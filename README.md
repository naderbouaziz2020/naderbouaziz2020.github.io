<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Template-lv1</title>
    <link rel="stylesheet" href="normalize.css">
    <link rel="stylesheet" href="master.css">
    <style>
      body{
  font-family: fantasy;
  height: 4000px;
}
.container{
  width: 1170px;
  margin: auto;
}
.clearfix{
  clear: both;
}

/* start header*/


.header .slider{
  background-color: #fff;
  height: 650px;
}
.header .navbar{
  background-color: #252f31;
  color: #fff;
  overflow: hidden;
  text-transform: uppercase;

}
.header .navbar h2{
  float: left;
}
.header .navbar h2 span{
  color: #2ecc71;
}
.header .navbar ul{
  list-style: none;
  padding-left: 0;
  overflow: hidden;
  float: right;
}

.header .navbar ul li{
  float: left;
  padding: 10px;
}

/*end header */



/*start features*/

.features{
  overflow: hidden;
  padding-top: 20px;
  padding-bottom: 20px;
}

.features .feat{
  float: left;
  width: 33.33333%;
  height: 150px;
  background-color: #ddd;
}
.features .feat h2{
  text-transform: uppercase;
}


/*end features*/

/* start about me */

.about-me{
  background-color: #f2f2f2;
  overflow: hidden;
}

.about-me .image{
  float: left;
  width: 40%;
}

.about-me .image img{
  width: 100%;
}
.about-me .info{
  float: left;
  width: 60%;
}

.about-me .info .hobbies{
  margin: 20px;
}

.about-me .info .hobbies > div{
  float: left;
  width: 50%;
  min-height: 100px;
}



/* end about me */




/* start my skills */

.my-skills{
  padding-top: 30px;
  padding-bottom: 30px;
  overflow: hidden;
}
 .my-skills .skills, .my-skills .progress{
   width: 50%;
   float: left;
 }

/* end my skills */


.resume {
text-align: center;
padding-top: 30px;
padding-bottom: 30px;
background-color: #ddd;
}




/* start my education */

.my-education{
  padding-top: 30px;
  padding-bottom: 30px;
  overflow: hidden;
}
 .my-education .education, .my-education .progress{
   width: 50%;
   float: left;
 }
 .my-education .education{
   margin-right: 20px;
 }

/* end my education */

    </style>
  </head>
  <body>



    <!-- header -->

    <div class="header">
      <div class="slider">
        <div class="container">
          slider
        </div>
      </div>
      <div class="navbar">
        <div class="container">
          <h2>Fo<span>cal</span></h2>
          <ul>
            <li>Home</li>
            <li>About us</li>
            <li>Skills</li>
            <li>Resume</li>
            <li>Testemonials</li>
            <li>Portfolio</li>
            <li>Contact Me</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- start features-->

    <div class="features">
      <div class="container">
        <div class="feat">
          <h2>values</h2>
          <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few </p>
        </div>
        <div class="feat">
          <h2>goals</h2>
          <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few </p>
        </div>
        <div class="feat">
          <h2>hobbies</h2>
          <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few </p>
        </div>
      </div>
    </div>

    <!-- start about me -->

    <div class="about-me">
      <div class="container">
        <div class="image">
          <img src="http://placehold.it/300/300" alt="test">
        </div>
        <div class="info">
          <h2>About me</h2>
          <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few </p>
          <div class="hobbies">
            <div class="">
              Web Design
            </div>
            <div class="">
              Graphic Design
            </div>
            <div class="">
              Online Marketing
            </div>
            <div class="">
              Seo
            </div>
          </div>
        </div>
      </div>
    </div>


    <!-- end about me -->

    <!-- start my skills -->



    <div class="my-skills">
      <div class="container">
        <div class="skills">
          <h2>Skills</h2>
          <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia.</p>
          <button>Contact Me</button>
        </div>
        <div class="progress">
          some progress
        </div>
      </div>
    </div>



    <!-- end my skills -->

    <!-- start Resume -->

      <div class="resume">
        <div class="container">
          <div class="">
            <h2>Resume</h2>
            <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few Animals (also referred to as metazoa) are multicellula</p>
            <button type="" name="button">Download Resume</button>
          </div>
        </div>
      </div>


    <!-- end Resume -->

    <!-- start my education -->



    <div class="my-education">
      <div class="container">
        <div class="education">
          <h2>education</h2>
          <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia.</p>
        </div>
        <div class="exp">
          <p>eukaryotic organisms that form the biological</p>
        </div>
        <div class="clearfix"></div>
        <hr>
        <div class="education">
          <h2>education</h2>
          <p>Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia. With few Animals (also referred to as metazoa) are multicellular eukaryotic organisms that form the biological kingdom Animalia.</p>
        </div>
        <div class="exp">
          <p>eukaryotic organisms that form the biological</p>
        </div>
      </div>
    </div>



    <!-- end my education -->

  </body>
</html>

