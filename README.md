<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Manideep Vadlakonda</title>
  <style>
    body{
      margin:0;font-family:sans-serif;display:flex;align-items:center;justify-content:center;
      height:100vh;background:linear-gradient(135deg,#00d4ff,#7b61ff,#ff6ec7);color:#fff;
      animation:bgmove 10s infinite alternate;
    }
    @keyframes bgmove{
      0%{background-position:0% 50%}
      100%{background-position:100% 50%}
    }
    .card{
      background:rgba(0,0,0,0.6);padding:30px;border-radius:15px;text-align:center;
      box-shadow:0 8px 25px rgba(0,0,0,0.4);max-width:320px;
      transform:scale(0.95);opacity:0;animation:fadeIn 1s forwards;
    }
    @keyframes fadeIn{to{transform:scale(1);opacity:1}}
    h1{margin:0 0 10px;font-size:24px}
    p{margin:6px 0;color:#ddd}
    a{display:inline-block;margin-top:12px;padding:10px 16px;border-radius:8px;
      background:#fff;color:#000;font-weight:bold;text-decoration:none;
      transition:0.3s ease;}
    a:hover{background:#ff6ec7;color:#fff;box-shadow:0 0 15px #ff6ec7}
  </style>
</head>
<body>
  <div class="card">
    <h1>Manideep Vadlakonda</h1>
    <p>📞 123456789</p>
    <p>✉ manideepvadlakonda@gmail.com</p>
    <a href="mailto:manideepvadlakonda@gmail.com">Contact Me</a>
  </div>
</body>
</html>
