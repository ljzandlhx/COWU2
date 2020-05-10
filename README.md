# COWU2
*{
    padding: 0;
    margin: 0;
}

body{
    background-color: #00a1a4;
    font-family: "Poppin",sans-serif;
}

.btn{
    text-decoration: none;
    width: 150px;
    height: 50px;
    position: absolute;
    left: 50%;
    top: 50%;
    /*transform: translate(-50%,-50%);*/
    margin-left: -75px;
    margin-top: 25px;
    line-height: 50px;
    text-align: center;
    color: white;
    font-size: 30px;
    background-color: #69afbb;
    border-radius: 25px;
}
.btn:hover{
    animation: a 0.5s;
}



.user{
    top: 30%;
}
.password{
    top: 40%;
}
input{
    position: absolute;
    border: none;
    left: 50%;
    border-radius: 25px;
    padding-left: 20px;
    width: 380px;
    height: 50px;
    margin-left: -200px;
    background-color: #4fa2a4;
    color: white;
    font-size: larger;
}

input:hover{
    animation: a 1s;
}

p{
    position: absolute;
    left: 50%;
    width: 200px;
    height: 50px;
    margin-left: -100px;
    top: 15%;
    color: white;
    font-size: 22px;
    text-align: center;
    letter-spacing: 5px;
    line-height: 50px;
}

p:hover{
    animation: b 1s;
}

@keyframes a {
    0%,100%{
        transform: scale(1,1);
    }
    75%,25%{
        transform: scale(0.9,1.1);
    }
    50%{
        transform: scale(1.1,0.9);
    }
}

@keyframes b {
    0%,100%{
        font-size: 22px;
    }
    25%,75%{
        font-size: 30px;
    }
    50%{
        font-size: 22px;
    }
}
