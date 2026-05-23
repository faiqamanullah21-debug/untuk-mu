# untuk-mu<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Buat Kamu</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe6e6;
            font-family: 'Poppins', sans-serif;
        }
        .btn-gombal {
            padding: 15px 30px;
            font-size: 18px;
            background-color: #ff4d6d;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(255, 77, 109, 0.4);
            transition: 0.3s;
        }
        .btn-gombal:hover {
            transform: scale(1.1);
            background-color: #ff758f;
        }
    </style>
</head>
<body>

    <button class="btn-gombal" onclick="jalankanGombal()">Klik Dong</button>

    <script>
        function jalankanGombal() {
            alert("Tahu gak kenapa pelangi itu indah?");
            alert("Karena warna-warninya mirip hari-hariku...");
            alert("Sejak ada kamu di dalamnya. Eaaa~ 🤍");
        }
    </script>

</body>
</html>
