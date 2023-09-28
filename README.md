<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Martian+Mono:wght@500&display=swap" rel="stylesheet">
    <style>
        body {
            background-image: url(annie-tohill-street-scroll-update.gif);
            background-repeat: no-repeat;
            background-position-x: 470px;
            background-position-y: 200px;
            background-color: beige;
            
            
        }
        
        div {
            position: absolute;
            left: 800px;
            top: 500px;
            
            width: 70px;
            height: 55px;
            background-image: url(walk-cycle.png);
            
            animation: moveX .5s steps(8) infinite;
            
            }
        footer {
            margin-top: 750px;
            text-align: center;
        }
        
            @keyframes moveX {
                from{background-position-x:5px;}
                to{background-position-x: -500px;}
            }
            h1 {
                font-family: 'Martian Mono', monospace;
                text-align: center;
                font-size: 4em;
                text-shadow: black 5px 5px;
                color: red;

                
            }
            
                
                
                
            

                


    </style>
</head>
<body>
    <h1>CSS ANIMATION SCROLLING IMAGE</h1>
    
    <footer>
        <p>Develop by: Jonathan Enriquez,Alrights Reserved 2023</p>
        <a href="mailto:enriquezj1976@gmail.com">enriquezj1976@gmail.com</a>
    </footer>
    


</body>
</html>
