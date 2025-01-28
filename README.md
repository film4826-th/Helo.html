<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ไม่บอก</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 20%;
            background-color: #f0f8ff;
            color: #333;
        }
        h1 {
            font-size: 2.5em;
            color: #ff6347;
        }
        p {
            font-size: 1.5em;
            color: #555;
        }
        button {
            font-size: 1em;
            padding: 10px 20px;
            background-color: #ff6347;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #e55347;
        }
    </style>
    <script>
        function showLove() {
            alert("ว้าย โดนหลอก โง่เกิ้น!");
        }
    </script>
</head>
<body>
    <h1>หวัดดีคับ</h1>
    <p>กดปุ่มข้างล่างสิ!</p>
    <button onclick="showLove()">คลิกเลย</button>
</body>
</html>
