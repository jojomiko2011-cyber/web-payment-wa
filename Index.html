<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Upload Bukti Pembayaran</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f7f7f7;
    }
    .container {
      max-width: 480px;
      margin: auto;
      background: #fff;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    button {
      background-color: #4CAF50;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }
    #result, #kontakAdmin {
      margin-top: 20px;
      text-align: left;
    }
    #qris {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Upload Bukti Pembayaran</h2>
    <img id="qris" src="https://files.catbox.moe/ls0xww.png" alt="QRIS">
    <input type="file" id="fileInput"><br>
    <button onclick="uploadFile()">Kirim Bukti ke Telegram</button><div id="result"></div>
<div id="kontakAdmin" style="display:none">
  <p>Hubungi Admin:</p>
  <a id="linkTelegram" href="#" target="_blank">
    <button style="background-color:#0088cc">Chat Telegram</button>
  </a>
  <a id="linkWA" href="#" target="_blank">
    <button style="background-color:#25D366">Chat WhatsApp</button>
  </a>
</div>

  </div>  <script>
    function getRandomNomor() {
      return Math.floor(Math.random() * (5790 - 120 + 1)) + 120;
    }

    async function uploadFile() {
      const fileInput = document.getElementById('fileInput');
      if (!fileInput.files.length) return alert("Pilih file dulu!");

      const formData = new FormData();
      formData.append("photo", fileInput.files[0]);

      const nomor = getRandomNomor();
      const caption = `Bukti Pembayaran\nNomor: ${nomor}`;
      formData.append("caption", caption);

      const token = "7958174608:AAGs5VOadimZhj_o9FBoevNhDxHlkSucGLk";
      const chat_id = "7111518511";

      const response = await fetch(`https://api.telegram.org/bot${token}/sendPhoto?chat_id=${chat_id}`, {
        method: 'POST',
        body: formData
      });

      if (response.ok) {
        document.getElementById("result").innerHTML = `
          <div style='background:#d4f9d4; padding:15px; border-radius:8px;'>
            ✅ Bukti pembayaran berhasil dikirim ke Telegram!<br>
            📌 Nomor kamu: <b>${nomor}</b><br>
            Tunggu konfirmasi admin ya.
          </div>`;
        document.getElementById("linkTelegram").href = `https://t.me/SILENTSTR`;
        document.getElementById("linkWA").href = `https://wa.me/6283898743012?text=Halo%20admin%2C%20saya%20dengan%20nomor%20${nomor}%20sudah%20kirim%20bukti.`;
        document.getElementById("kontakAdmin").style.display = "block";
      } else {
        document.getElementById("result").innerHTML = "❌ Gagal mengirim bukti ke Telegram.";
      }
    }
  </script></body>
</html>
