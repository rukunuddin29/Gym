# Gym
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/b9e775a4c8.js" crossorigin="anonymous"></script>
</head>
<style>
    body{
    margin: 0px;
    padding: 0px;
}.navbar{
    display: flex;
    position: absolute;
    top: 15px;
   right: 550px;
}
.box
{
   border-bottom: 2px solid rgb(67, 
   67, 67);
   border-top: 2px solid rgb(67, 
   67, 67) ;
    height: 50px;
    top: 50px;
    width: 99%;
    position:absolute;
}
.navbar a {
    margin: 0px 20px;
    font-size: 18px;
    font-weight: 700;
    padding: 0px 10px;
    text-decoration: none;
    color: white;
}
.navbar a:hover{
    border-bottom: 4px solid  rgb(130, 159, 2);
    color: white;
    font-weight: 800;
}
/* .....................box..........., */
.pic{
    width: 100%;
    height:900px;
    top: 0px;
    left: 0px;
    background-size: cover;
}
.logo{
    position: absolute;
    z-index: 1;
    left:720px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    top:0px;
    font-weight: 1000;
    font-size: 20px;
    color: white;
}

.box h1{
position: absolute;
    right: 260px;
    color: white;
    top: 90px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 80px;
    text-shadow: 0 2px 3px #000000;
}
.box h4 {
    font-size: 20px;
    color: white;
  position: absolute;
    top: 100%;
    right: 17%;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    
}
.join{
    width: 130px;
    height: 40px;
    position: absolute;
    top: 480px;
    right: 484px;
    color: white;
    font-size: larger;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    border-radius: 40px;
    background-color: transparent ;
   border: 4px solid rgb(143, 175, 1);
}

@media only screen and (max-width: 600px) {
    .pic{
       width: 100%;
       height: 100%;
       position: relative;
       top: 0px;
    }
    .logo{
        position: absolute;
        z-index: 1;
        left:44%;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        top:0px;
        font-weight: 1000;
        font-size: 20px;
        color: white;
       
    }
    .box
{
   border-bottom:none;
   border-top: none;
    height: 0px;
    top: 0px;
    background-color: black;
    /* width: 50%;
    height: 1000px; */
}
.navbar a {
    margin: 0px 20px;
    font-size: 18px;
    font-weight: 700;
    padding: 0px 10px;
    text-decoration: none;
    color: black;
}
.navbar a:hover{
    border-bottom: 4px solid  rgb(130, 159, 2);
    color: white;
    font-weight: 800;
}

/* ............................. */

}

/* ....................................... */
/* .section
{
    width: 100%;
    height: 590px;
    position: relative;
    top: 0px;
    background-color: rgb(0, 0, 0);
}
.section img {
    width: 100%;
    height: 600px;
    position: relative;
    top: -5px;
    filter: opacity(20%);
}
.section h2 {
    font-size: 40px;
    align-items: center;
    position: absolute;
    top: 10px;
    left: 40%;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: white;
   
    padding: 10px;
    border-radius: 20px;
}
.section p {
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 15px;
    position: absolute;
    color: white;
    top: 130px;
    left: 27%;
} 
.section h1 {
    position: absolute;
    border-left: 150px;
    border-top: 150px;
    border-bottom: 150px;
    width: 170px;
    border-top-left-radius: 50%;
    border-color: rgb(130, 159, 2);
    height: 170px;
    left: 100px;
    margin: 50px;
    align-items: center;
    justify-content: center;
    top: 200px;
    color: white;
} */

/* ........................ring.................. */
/* h1 {
    text-align: center;
    color: #d4d4d4;
  }
  
  .rings {
    display: flex;
    flex-direction: row;
    margin-left: 40px;
  }
  
  .percent1, .percent2, svg, circle {
    width: 300px;
    height: 300px;
  }
  .percent1{
    position: absolute;
    top: 240px;
    left:250px;
    
  }
  .percent2 {
    position: absolute;
    top: 240px;
    left: 550px;
  }
  .percent3{
    position: absolute;
    top: 240px;
    left: 850px;
  }
  
  .percent4 {
    position: absolute;
    top: 240px;
    left: 1150px;
  }
  
  
  circle {
    position: absolute;
    fill: none;
    stroke-width: 10;
    transform: translate(10px, 10px);
    stroke-dasharray: 440;
    stroke-linecap: round;
  }
  
  circle:nth-child(1) {
    stroke-dashoffset: 0;
    stroke: #424242b3;
  }
  
  .percent1 circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 90) / 100);
    stroke:rgb(130, 159, 2);
    animation: percent 1.5s linear;
    animation-delay: 1s;
  }
  
  .percent2 circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 95) / 100);
    stroke:rgb(130, 159, 2);
    animation: percent 1.8s linear;
    animation-delay: 1.2s;
  }
  .percent3 circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 75) / 100);
    stroke:rgb(130, 159, 2);
    animation: percent 1.8s linear;
    animation-delay: 1.2s;
  }
  .percent4 circle:nth-child(2) {
    stroke-dashoffset: calc(440 - (440 * 80) / 100);
    stroke:rgb(130, 159, 2);
    animation: percent 1.8s linear;
    animation-delay: 1.2s;
  }
  .number {
    position: relative;
    bottom: 300px;
    right: 80px;
    color: #fff;
    border: none;
  }
  
  h2 {
    font-size: 48px;
  }
  
  span {
    font-size: 24px;
    opacity: .7;
  }
  
  .percent1 span ,.percent3 span, .percent4 span {
    color: rgb(130, 159, 2);
  }
  
  .percent2 span {
    color: rgb(130, 159, 2);
  }
  
  @keyframes percent {
    0% {
      stroke-dashoffset: 0;
      stroke-width: 0;
    }
  } */

/* -----------------service------------- */
/* .service{
    width: 100%;
    height: 450px;
    background-color: rgb(143, 175, 1);
    top: -10px;
    position: relative;
    display: flex;
}
.boxSer{
    width: 25%;
    height: 600px;
}
.textCardio{
  font-size: 24px;
}
.textBody{
    font-size: 24px;
    right: 80px;
    position: absolute;

}
.textRunning{
    font-size: 24px;
    width: 200px;
    position: absolute;
    left: 470px;
}
#boxSer1, #boxSer2 , #boxSer3 {
    background-color: rgb(130, 159, 2);
    height: 450px;
}
.fa-person-running , .fa-dumbbell,.fa-heart-circle-bolt{
    color: antiquewhite;
    font-size: 100px;
    margin: 90px 127px;
} */

/* ..............................club image ...................... */
.clubText{
    font-size: 50px;
    width: 4em;
    border: 2px solid black ;
    margin: 2em 2.2em;
    color: rgb(130, 159, 2);
    position: absolute;
    right: 2.2em;
    font-weight: bold;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.clubImg{
     width: 60%;
     height: 12em;
     position: relative;
     margin:1.4em 2em;
}
@media only screen and (max-width: 600px) {
    .clubText{
        font-size: 2em;
        color: rgb(130, 159, 2);
        position: absolute;
        right: -10%;
        font-weight: bold;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
    .clubImg{
         width: 60%;
         height:200px;
         position: relative;
         margin: 20px 30px;
    }
}
/* '''''''''''''''''''''''imagesGrid''''''''''''''''''''''' */

.imageGrid{
    width: 100%;
    height: 500px;
    /* background-color: aquamarine; */
    display: flex;
    flex-wrap: wrap;

}

.imageGrid img {
    width: 379.81px;
    height: 250px;
    margin: 0px;
    padding: 0px;

}

.fitnessTrainer {
     width: 100%;
     height: 800px;
     background-color: rgb(130, 159, 2);
     margin: -13px 0px;
}
.fitnessTrainer h2{
    font-size: 70px;
    color: black;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    margin: 0px 450px;
    padding: 50px 50px;
    width: 50%;
}
.fitnessTrainer p{
    font-size: large;
    width: 90%;
}
.trainerImgBox{
    width: 100%;
    height: 500px;
    display: flex;
    margin: 0px 0px;
}
.trainerImg {
    width: 19% ;
    height: 500px;
    margin: 100px 40px;
   border: 2px solid black ;
}
.trainerImg img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin: -10px 60px ;
}
.trainerImg h3 {
    font-size: 30px;
    text-align: center;
}
.trainerImg span {
    font-size: 20px;
    text-align: center;
}
.fa-brands{
    font-size: 23px;
    text-align: center;
    padding: 0px 10px;
}
.map{
  width: 100%;
}

@media only screen and (max-width: 600px) {
    .map{
        width: 100%;
        height: 60%;
      }
      /* ..............mao............ */

    .imageGrid{
        width: 100%;
        height: 200px;
        /* background-color: aquamarine; */
        display: flex;
        flex-wrap: wrap;
    
    }
    
    .imageGrid img {
        width:25%;
        height: 100px ;
        margin: 0px;
        padding: 0px;
        transition: smooth 0.5s;
    }
    /* ..................imgGrid............ */
    .fitnessTrainer {
        width: 100%;
        height: 600px;
        background-color: rgb(130, 159, 2);
        margin: -13px 0px;
   }
   .fitnessTrainer h2{
       font-size: 40px;
       color: black;
       font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
       margin: 0px 5%;
       padding: 50px 50px;
       width: 90%;
   }
   .fitnessTrainer p{
       font-size:small;
       margin: -3em 4em;
   
   }
   .trainerImgBox{
       width: 70%;
       height: 500px;
       margin: 10% 15%;
       display: flex;
       flex-wrap: nowrap; 
       overflow-x: auto; 
       max-width: 100%;
   }
   .trainerImg {
       width: 100% ;
       height: 300px;
       margin: 40px 70px;
      border: 2px solid rgba(232, 230, 230, 0) ;
   }
   .trainerImg img {
       width: 10em;
       height: 10em;
       border-radius: 50%;
       margin: -1em 1em ;
   }
   .trainerImg h3 {
       font-size: 2em;
       text-align: center;
   }
   .trainerImg span {
       font-size: 0.5em;
       text-align: center;
   }
   .fa-brands{
       font-size: 23px;
       text-align: center;
       padding: 0px 10px;
   }
   
}
</style>
<body>
  
    <header>
        <div class="container">
        <div>
        <img src="https://img.redbull.com/images/c_limit,w_1500,h_1000,f_auto,q_auto/redbullcom/2016/04/28/1331791773515_1/ross-tyre-push" alt="" class="pic">
        <div class="box2"></div>
        <h2 class="logo">GRIND</h2>
        <div class="box">
            <h1>LET'S <br> GET <br><span>MOVING.</span>
           <h4> the fitness factory</h4></span>
            </h1>
            <button class="join">join now</button>
        
        <nav class="navbar">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
            <a href="#">Login</a>
        </nav>
        </div>
        </div>
    </header>
<!-- <section class="service">
    <div class="boxSer" id="boxSer1"><i class="fa-solid fa-heart-circle-bolt"> <h3 class="textCardio">Cardio</h3></i></div>
    <div class="boxSer"><i class="fa-solid fa-person-running"><h3 class="textRunning">Weight Loss</h3></i></div>
    <div class="boxSer" id="boxSer2"></div>
    <div class="boxSer"><i class="fa-solid fa-dumbbell"><h3 class="textBody">Body Building</h3></i></div>
</section> -->

<section>
    <div class="clubText">THE <br>CLUB</div>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPI0WTB31Pzd_J7fwLp7tXLoInOize-0ueEQ&usqp=CAU" alt="" class="clubImg">
</section>
<div class="imageGrid">
    <img src="https://prod-ne-cdn-media.puregym.com/media/819394/gym-workout-plan-for-gaining-muscle_header.jpg?quality=80" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvQxkvW7LkTaFfiPTziZQiS2qjQ5pcCAwgXw&usqp=CAU" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOAtd6VQten06mbc8yfudKiaHiaazaE8zHkQ&usqp=CAU" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8TpsOi0CgMB6pT4pMshS69pnpe1M_eWvnTw&usqp=CAU" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIDjqifoMBxy52dDftREKKSW-oeaUp9C-SdQ&usqp=CAU" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDHa12YeyuIAitbEsifsFqF_E3XkKDMmTacg&usqp=CAU" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS6UBJ37mDSlrRTIDiDJXGEgSoIiLMHDigi0o6x3uuDdJwmZ3TVpSZYUU6OXMazpNvDNdQ&usqp=CAU" alt="">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPHbxwIMSTlfQka7BdGwXUIdJof2eC9L-5jQ&usqp=CAU" alt="">
</div>
<!-- <section>
    <div class="section">
     <img src="https://t4.ftcdn.net/jpg/02/08/23/45/360_F_208234580_l7Mmd38mMIQv7lB3pVSFYEtYjy7QLR5x.jpg" alt="">
     <h2> FITNESS GOALS</h2>
     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem natus maiores dolor consectetur debitis.</p>
     <div class="percent1">
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
        <h2>90<span>%</span></h2>
      </div>
</div> -->
  <!-- <div class="percent2">
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
        <h2>98<span>%</span></h2>
      </div>
    </div>

    <div class="percent3">
        <svg>
          <circle cx="70" cy="70" r="70"></circle>
          <circle cx="70" cy="70" r="70"></circle>
        </svg>
        <div class="number">
          <h2>75<span>%</span></h2>
        </div>
      </div>
      <div class="percent4">
        <svg>
          <circle cx="70" cy="70" r="70"></circle>
          <circle cx="70" cy="70" r="70"></circle>
        </svg>
        <div class="number">
          <h2>80<span>%</span></h2>
        </div>
      </div>
    </div>
</section> -->
<section>
    <div class="fitnessTrainer">
        <h2>Fitness Trainers</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate, quis.</p>
        <div class="trainerImgBox">
        <div class="trainerImg">
            <img src="https://img.freepik.com/free-photo/serious-afro-american-sports-man-looking-camera_171337-8256.jpg?size=626&ext=jpg&ga=GA1.1.702301594.1688586332&semt=ais" alt="">

            <h3>xxxxxxxx <br><span>Lorem ipsum, dolor sit amet consectetur adipisicing.</span></h3>
           
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-x-twitter"></i>
            <i class="fa-brands fa-youtube"></i>

            
        </div>

        <div class="trainerImg">
            <img src="https://img.freepik.com/free-photo/serious-afro-american-sports-man-looking-camera_171337-8256.jpg?size=626&ext=jpg&ga=GA1.1.702301594.1688586332&semt=ais" alt="">

            <h3>xxxxxxxx <br><span>Lorem ipsum, dolor sit amet consectetur adipisicing.</span></h3>
           
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-x-twitter"></i>
            <i class="fa-brands fa-youtube"></i>

            
        </div>

        <div class="trainerImg">
            <img src="https://img.freepik.com/free-photo/serious-afro-american-sports-man-looking-camera_171337-8256.jpg?size=626&ext=jpg&ga=GA1.1.702301594.1688586332&semt=ais" alt="">

            <h3>xxxxxxxx <br><span>Lorem ipsum, dolor sit amet consectetur adipisicing.</span></h3>
           
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-x-twitter"></i>
            <i class="fa-brands fa-youtube"></i>

            
        </div>

        <div class="trainerImg">
            <img src="https://img.freepik.com/free-photo/serious-afro-american-sports-man-looking-camera_171337-8256.jpg?size=626&ext=jpg&ga=GA1.1.702301594.1688586332&semt=ais" alt="">

            <h3>xxxxxxxx <br><span>Lorem ipsum, dolor sit amet consectetur adipisicing.</span></h3>
           
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-x-twitter"></i>
            <i class="fa-brands fa-youtube"></i>  
        </div>
    </div>
    </div>
</section>

<section>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d58950.197867519724!2d88.27116608619689!3d22.564610950605093!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a02779ff7e5b9af%3A0x1d1b1884bdbbbd79!2sEden%20Gardens!5e0!3m2!1sen!2sin!4v1704739919492!5m2!1sen!2sin" width="1534" height="500" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="map"></iframe>
</section>


</body>
</html>
