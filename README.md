<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">

</head>

<style>
  
body {
    background-color: rgb(50, 50, 50);
    margin: 0px;
    padding: 0px;
}

.first-page {
    position: absolute;
    background-position: center;
    height: 100vh;
    width: 100vw;
    background: linear-gradient(134.89deg, #030640 10.47%, #3f0652 98.32%);
}

.nav-container {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    position: relative;
    padding-top: 20px;
    display: flex;
    justify-content: space-around;
    gap: 50px;
    align-items: center;
}


.icon-text {
    padding-left: 12px;
    font-size: 19px;
    color: white;
}


.main-icon-container {
    align-items: center;
    display: flex;
    justify-content: space-around;
}

.nav-link-text {
    text-decoration: none;
    color: white;
}

.nav-link-container {
    padding: 16px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 50px;
}

.contact-button {
    background: none;
    border: solid;
    border-width: 1px;
    border-color: white;
    color: white;
    font-size: 22px;
    border-radius: 5px;
    padding: 11px 24px;
    cursor: pointer;
}

.modern-studio-fGB {
    position: relative;
    padding-top: 120px;
    font-size: 18px;
    font-family: system-ui, 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: red;
}

.were-help-to-build-XpB {
    font-size: 56px;
    color: white;
    font-family: system-ui, 'Arial Narrow', Arial, sans-serif;
}

.agency-provides-a-fu-C9d {
    font-size: 16px;
    color: rgb(193, 189, 189);
    padding-top: 50px;
    font-family: system-ui, 'Arial Narrow', Arial, sans-serif;
}

.first-page-right-image {
    padding-top: 120px;
    height: 50vh;
    width: 25vw;
    animation-name: floating;
    animation-duration: 4s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
}

@keyframes floating {
    0% {
        transform: translate(0, 0px);
    }

    50% {
        transform: translate(0, 15px);
    }

    100% {
        transform: translate(0, 0px);
    }
}

.firs-page-content {
    align-items: center;
    display: flex;
    justify-content: space-around;
    gap: 120px;
}

.second-page {
    background-color: #fdf0e9;
    position: absolute;
    margin-top: 51%;
    height: 30vh;
    width: 100vw;

    display: flex;
    flex-direction: column;
    align-items: center;
}

.second-page-text {
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 33px;
}

.second-page-icons {
    margin: 6vh;
    display: flex;
    justify-content: space-evenly;
    gap: 13vh;
}

.second-page-icon-image {
    height: 4vh;

}

#next-js {
    padding: 5px;
    height: 20px;
    width: 55px;
}

#ex {
    height: 21px;
    width: 29px;
    padding: 3px;
}
</style>

<body>
    <main>
        <div class="first-page">
            <div class="nav-container">

                <div class="main-icon-container">
                    <img class="main-icon" src="../resources/Isolation_Mode.png" alt="">

                    <h1 class="icon-text">PROGRAMMING ARENA</h1>
                </div>

                <div class="nav-link-container">
                    <a class="nav-link-text" href="">Home</a>
                    <a class="nav-link-text" href="">Portfolio</a>
                    <a class="nav-link-text" href="">About.me</a>
                    <a class="nav-link-text" href="">Blog</a>
                </div>

                <a href=""><button class="contact-button">contact</button></a>

            </div>

            <div class="firs-page-content">
                <div class="first-page-left-text">
                    <p class="modern-studio-fGB" id="12:50">Programming ARENA</p>
                    <p class="were-help-to-build-XpB">
                        We Help<br>To Build Your<br>Dream Project
                    </p>
                    <p class="agency-provides-a-fu-C9d">Lorem ipsum dolor sit amet. <br> Aut fugit delectus sed
                        dignissimos
                        fugiat eos
                        quia dignissimos qui libero</p>
                </div>
                <img class="first-page-right-image" src="../../image/WhatsApp Image 2023-11-17 a (2).png" alt="">
            </div>

        </div>


        <div class="second-page">
            <h1 class="second-page-text">Our Expertise</h1>

            <div class="second-page-icons">
                <img src="../resources/Group-1.png" alt="" class="second-page-icon-image">
                <img src="../resources/Group-2.png" alt="" class="second-page-icon-image" id="next-js">
                <img src="../resources/Group-3.png" alt="" class="second-page-icon-image">
                <img src="../resources/Clip path group.png" alt="" class="second-page-icon-image">
                <img src="../resources/Clip path group-1.png" alt="" class="second-page-icon-image">
                <img src="../resources/Clip path group-2.png" alt="" class="second-page-icon-image">
                <img src="../resources/Clip path group-3.png" alt="" class="second-page-icon-image">
                <img src="../resources/Clip path group-4.png" alt="" class="second-page-icon-image" id="ex">
            </div>

        </div>

        <div class="third-page">

        </div>

    </main>

    <footer></footer>

</body>

</html>
