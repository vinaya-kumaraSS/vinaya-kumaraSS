<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css">
    <link rel="stylesheet" href="boostrap/css/font.css">
    <link rel="stylesheet" href="boostrap/css/bootstrap.css">
    <link rel="stylesheet" href="boostrap/css/mdb.css">
    <link rel="stylesheet" href="boostrap/css/style.css">
    <style>
        html{
            scroll-behavior: smooth;
        }
        body{
            background-color: black;
        }
        #cont_header{
            color: rgb(220, 189, 250);
            text-align: center;
            font-family: 'Times New Roman', Times, serif;
        }
        #hr{
            margin-top: 0px;
            height: 1px;
            background-color: rgb(220, 189, 250);
        }
        #container {
            max-width: 800px;
            background-color: black;
            margin: 0 auto;
            color: rgb(220, 189, 250);
            box-shadow: rgb(255, 255, 255) 0px 1px 4px, rgb(255, 255, 255) 0px 0px 0px 1px;
            text-align: center;
    }
        #skill_container{
            height: 100px;
            width: auto;
            box-shadow: rgb(220, 189, 250)  0px 3px 8px;        
        }
        #coding_profile_logo{
            height: 70px;
            width: 80px;
        }
        ul {
            list-style: none; /* Remove default bullets */
            display: flex; /* Display list items in a row */
            justify-content: center; /* Center the items horizontally */
            align-items: center; /* Center the items vertically */
        }
        li {
            margin-top: 15px;
            margin-right: 40px; /* Add some spacing between the images */
        }
        li img {
            display: block; /* Remove any default inline spacing */
            max-width: 100px; /* Limit the maximum width of images */
            height: auto; /* Maintain the aspect ratio of images */
        }
        </style>
</head>
<body>
    <!---ABOUT ME-->
    <div class="nav">

    </div>
    <hr id="hr"></hr>
    <h3 class="text-center" id="cont_header">ABOUT ME</h3>
        <hr id="hr" style="width: 100px;"></hr>
    <div class="card" id="container">
        <p>I am currently pursuing my Bachelor of Engineering specialized in Computer Science and Engineering with great interest in Data Structures, Algorithms and Optimization.I am a competitive programming enthusiast very interested in solving varieties of problem statements in an optimized way.I like and enjoy learning new technologies and take up challenges with creative problem solving abilities.Always ready to learn new things and apply them in my project.A good team player with an open mind and likes to brainstorm upon a problem to find the most optimal solution.</p>
    </div>
    <!-- HTML !-->
    <p class="text-center mt-4"><a href="#"><button class="button-85" role="button">RESUME</button></a><a href="https://www.linkedin.com/in/vinayakumara-s-s-01372a249/"><i class="fab fa-brands fa-linkedin fa-xl pl-3"></i></a></p>
    <!---END ABOUT ME-->

    <!---PROJECTS-->
    <h3 class="text-center mt-5" id="cont_header">PROJECTS</h3>
    <hr id="hr" style="width: 100px;"></hr>
    <!---END PROJECTS-->
    <!---ACHIEVEMENTS-->
    <h3 class="text-center mt-5" id="cont_header">ACHIEVEMENTS</h3>
    <hr id="hr" style="width: 175px;"></hr>
    <!---END ACHIEVEMENTS-->



    <!---CODING PROFILES-->
    <h3 class="text-center mt-5" id="cont_header">CODING PROFILES
    </h3>
    <hr id="hr" style="width: 200px;"></hr>
    <div class="container mt-5" id="skill_container">
        <ul>
            <a href="https://github.com/vinaya-kumaraSS"><li><img src="images/github.png" alt="" id="coding_profile_logo"></li></a>
            <a href=""><li><img src="images/Hacker rank.png" alt="" id="coding_profile_logo"></li></a>
            <a href="https://leetcode.com/Vinay_88/"><li><img src="images/leetcode.png" alt="" id="coding_profile_logo"></li></a>
            <a href=""><li><img src="images/leetcode.png" alt="" id="coding_profile_logo"></li></a>
        </ul>
    </div>
    <!---END CODING PROFILES-->

    <!--SKILLS--->
    <h3 class="text-center mt-5" id="cont_header">SKILLS</h3>
    <hr id="hr" style="width: 70px;"></hr>
    <!---END SKILLS-->
    
    <!--CERTIFICATION--->
    <h3 class="text-center mt-5" id="cont_header">CERTIFICATION</h3>
    <hr id="hr" style="width: 180px;"></hr>
    <!--END CERTIFICATION--->
    

</body>
</html>
