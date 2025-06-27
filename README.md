<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>A2A - Yapay Zekâ Asistanı</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #0d0d0d;
      color: #00ffee;
      font-family: 'Orbitron', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
    }

    h1 {
      font-size: 24px;
      white-space: nowrap;
      overflow: hidden;
      border-right: .15em solid #00ffee;
      width: 0;
      animation: typing 4s steps(40, end) forwards, blink .75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      50% { border-color: transparent }
    }

    .button {
      margin-top: 40px;
      padding: 12px 24px;
      font-size: 16px;
      background-color: #00ffee;
      color: #0d0d0d;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    .button:hover {
      background-color: #00c8c8;
    }

    footer {
      position: absolute;
      bottom: 20px;
      font-size: 12px;
      color: #555;
    }
  </style>
</head>
<body>
  <h1 id="a2aText">Merhaba Edanur. Ben A2A, hazır mısın?</h1>
  <button class="button" onclick="start()">A2A'yı Başlat</button>

  <footer>A2A © 2025 | İnsanazor tarafından geliştirildi</footer>

  <script>
    function start() {
      alert("A2A şu anda seni izliyor... :)");
    }
  </script>
</body>
</html>
