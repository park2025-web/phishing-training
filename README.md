<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>⚠ 警告！ウイルス感染 ⚠</title>
    <style>
        body {
            background-color: black;
            color: red;
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 100px;
        }
        .warning {
            font-size: 32px;
            font-weight: bold;
            animation: blink 0.8s infinite alternate;
        }
        @keyframes blink {
            0% { opacity: 1; }
            100% { opacity: 0; }
        }
    </style>
    <script>
        window.onload = function() {
            setInterval(() => { 
                alert("⚠ ウイルスに感染しました！ すぐに管理者へ報告してください！"); 
            }, 5000);
        };
    </script>
</head>
<body>
    <h1 class="warning">⚠ あなたのPCはウイルスに感染しました！</h1>
    <p>重要なデータが流出する可能性があります。すぐに対応してください！</p>
</body>
</html>
