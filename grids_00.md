<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic</title>
    <style>
        .on {
            background: orange;
        }

        div {
            padding: 50px;
            text-align: center;
            border-style: solid;
            font-size: 2em;            
        }
    </style>
</head>
<body>
    <button onclick="off()">Off</button>
    <button onclick="on()">On</button>
    <div id="target">Target</div>
    <script>
        function on(){
            const element = document.getElementById("target");
            element.classList.add("on");
        }

        function off(){
            const element = document.getElementById("target");
            element.classList.remove("on");
        }



    </script>
</body>
</html>