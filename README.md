# smoketext
Smoke Text Animation using HTML5 and CSS3, Animation
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smoke text Animation</title>
    <style>
        body{
            font-family: sans-serif;
            background-color: black;
            overflow: hidden;
        }
        section{
            height: 10px;
        }
        h1{
            font-size: 100px;
            position: absolute;
            color: #ddd;
            padding: 0px;
            margin: 0px;
            top: 45%;
            text-align: center;
            width: 100%;
            text-transform: uppercase;
            letter-spacing: 2px;
            transform: rotateY(-100%);
        }
        h1 span{
            display: inline-block;
            opacity: 0;
            animation: amin 1s linear forwards;
        }
        @keyframes amin {
            0%{
                opacity: 0;
                transform: rotateY(-90deg);
                filter: blur(10px);
            }
            100%{
                opacity: 1;
                transform: rotateY(0deg);
                filter: blur(0);
                
            }
            
        }
        h1 span:nth-child(1)
        {
            animation-delay: 1s;
            color: #0095da;
        }
        h1 span:nth-child(2)
        {
            animation-delay: 1.5s;
            color: #0095da;
        }
        h1 span:nth-child(3)
        {
            animation-delay: 2s;
            color: #0095da;
        }
        h1 span:nth-child(4)
        {
            animation-delay: 2.5s;
            color: #0095da;
        }
        h1 span:nth-child(5)
        {
            animation-delay: 3s;
            
        }
        h1 span:nth-child(6)
        {
            animation-delay: 3.5s;
            
        }
        h1 span:nth-child(7)
        {
            animation-delay: 4s;
            
        }
        h1 span:nth-child(8)
        {
            animation-delay: 4.5s;
        
        }
        h1 span:nth-child(9)
        {
            animation-delay: 5s;
            
        }
        h1 span:nth-child(10)
        {
            animation-delay: 5.5s;
            
        }
    </style>
</head>


<body>
    <video src="smoke.mp4" muted="" autoplay="" width="100%"></video>
    <section>
     <h1>
        <span>r</span>
        <span>o</span>
        <span>n</span>
        <span>i</span>
        <span>p</span>
        <span>i</span>
        <span>p</span>
        <span>p</span>
        <span>a</span>
        <span>l</span>
     </h1>     
    </section>
</body>
</html>
