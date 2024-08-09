# Parallax-website
This is a parallax website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parallax Effect</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="th.jpeg" type="image/x-icon">


    <title>Hyperlink Generator</title>
	<style>
        *{  
    margin:0;
    padding:0;
    box-sizing: border-box;
}

#wrapper{
    height:100vh;
    overflow-x:hidden;
    overflow-y:auto;
    perspective:10px;
}

.container{
    position:relative;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    transform-style: preserve-3d;
    z-index:-1;
 
}
.background{
    transform: translatez(-40px)  scale(6);
   
    
}
.foreground{
    transform: translatez(-20x)  scale(3);
   
    
}
.background, .foreground{
    position: absolute;
    height: 100%;
    width:100%;
    object-fit: cover;
    z-index:-1;

}
h1{
    position: absolute;
    top:5rem; 
    font-size: 10rem;
    letter-spacing: 4px;
    color: white;
    text-shadow: 0 0 10px rgb(0,0,0,0.3);
}

section{
    background-color: rgb(45,45,45);
    color: white;
    padding: 5rem 0;

 }
.secheading{
    font-size: 5rem;
    padding:0 10rem;

}
.text{
    font-size:1.5rem;
    padding:0 10rem;
    margin:5rem 0;
}
.desc{
    position: absolute;
    background-color: white;
    padding: 0.5rem 2.5rem;
    top:50%;
    left:50%;
    transform: translatex(-50%) translatex(-50%);
    font-size: 3.5rem;
    color: black;
    font-weight: 600;


}
.bg{
    position: relative;
    width: 100%;
    background-attachment: fixed;
    background-size: cover;
    background-position: center;
    height: 500px;
}
 .bg1{
    background-image: url(sport-1.jpg);
 }
 .bg2{
    background-image: url(sport-2.jpg);
 }
 .bg3{
    background-image: url(sport-3.jpg);
 }
		
	</style>
</head>
<body>
   


    <div id="wrapper">

        <div class="container">
            <img src="background.png" class="background">
            <img src="foreground.png" class="foreground">
            <h1>ADVENTURE</h1>
        </div>
     <section>
        <h2 class="secheading">Adventure Time</h2>
        <p class="text">An adventure is an exciting experience or undertaking that is typically bold, sometimes risky.[1] Adventures may be activities with danger such as traveling, exploring, skydiving, mountain climbing, scuba diving, river rafting, or other extreme sports. Adventures are often undertaken to create psychological arousal or in order to achieve a greater goal, such as the pursuit of knowledge that can only be obtained by such activities
        <br><br>
        </p>
        <div class="bg bg1">
            <h2 class="desc">Biking</h2>
        </div>
        <p class="text">Adventure bikes inherently strive to offer equally good performance, handling, and comfort both on- and off-road. This is a complicated balance to strike, and there tend to be concessions one way or another. Choosing the best adventure motorcycle really means figuring out what qualities are most important to you.

            This is not an exhaustive list of all bikes that meet those general criteria or could be made to meet them with after-market upgrades. Instead, we chose these tried-and-true adventure motorcycles that come from the factory ready for long-distance riding. 
            <br><br>
            </p>
            <div class="bg bg2">
                <h2 class="desc">PARAGLIDING</h2>
            </div>
            <p class="text">Paragliding is the recreational and competitive adventure sport of flying paragliders: lightweight, free-flying, foot-launched glider aircraft with no rigid primary structure.[1] The pilot sits in a harness or in a cocoon-like 'pod' suspended below a fabric wing. Wing shape is maintained by the suspension lines, the pressure of air entering vents in the front of the wing, and the aerodynamic forces of the air flowing over the outside.
                Despite not using an engine, paraglider flights can last many hours and cover many hundreds of kilometres, though flights of one to five hours and covering some tens of kilometres are more the norm. By skillful exploitation of sources of lift, the pilot may gain height, often climbing to altitudes of a few thousand metres.
                <br><br>
                </p>
                <div class="bg bg3">
                    <h2 class="desc">SURFING</h2>
                </div>
                <p class="text">Surfing is a surface water sport in which an individual, a surfer (or two in tandem surfing), uses a board to ride on the forward section, or face, of a moving wave of water, which usually carries the surfer towards the shore. Waves suitable for surfing are primarily found on ocean shores, but can also be found as standing waves in the open ocean, in lakes, in rivers in the form of a tidal bore, or in wave pools.
                    <br><br>
                    </p>
     </section>


    </div>
    
</body>
</html>
