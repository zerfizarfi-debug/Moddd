<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI HOSHINO LOGIN - NARA STORE</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;800&display=swap');
        :root { --ai-pink: #ff4081; --dark-bg: #0d0d12; }
        body { background-color: var(--dark-bg); color: #ffffff; font-family: 'Plus Jakarta Sans', sans-serif; min-height: 100vh; display: flex; align-items: center; justify-content: center; }
        .gen-card { background: rgba(255, 255, 255, 0.05); border: 2px solid var(--ai-pink); border-radius: 25px; padding: 30px; backdrop-filter: blur(15px); width: 90%; max-width: 400px; text-align: center; box-shadow: 0 0 30px rgba(255, 64, 129, 0.2); }
        .profile-img { width: 100px; height: 100px; border-radius: 50%; border: 3px solid var(--ai-pink); margin-bottom: 15px; object-fit: cover; }
        .email-display { background: #16161a; padding: 15px; border-radius: 12px; font-weight: bold; color: #00ff88; border: 1px solid #333; margin: 20px 0; word-break: break-all; min-height: 55px; }
        .btn-gen { background: linear-gradient(45deg, #ff4081, #9c27b0); border: none; color: white; font-weight: 800; width: 100%; padding: 12px; border-radius: 12px; margin-bottom: 10px; }
        .btn-check { background: #25d366; border: none; color: white; font-weight: 800; width: 100%; padding: 12px; border-radius: 12px; display: none; text-decoration: none; }
    </style>
</head>
<body>
    <div class="gen-card">
        <img src="https://telegra.ph/file/bc3e3576359d9c82f05a1.jpg" class="profile-img" alt="Ai Hoshino">
        <h4 class="fw-bold">Ai Hoshino Login</h4>
        <p class="small text-secondary">Generator Email Login AM Premium</p>
        
        <div class="email-display" id="res">KLIK GENERATE...</div>
        
        <button class="btn-gen" onclick="gen()">GENERATE EMAIL</button>
        <button class="btn btn-outline-light btn-sm w-100 mb-2" onclick="copy()">Salin Email</button>
        
        <a href="#" id="checkLink" target="_blank" class="btn-check">
            <i class="fas fa-envelope-open"></i> CEK KOTAK MASUK
        </a>
        
        <p class="mt-3 small text-muted">Klik "Cek Kotak Masuk" buat ambil link login Alight Creative.</p>
    </div>

    <script>
        function gen() {
            const d = 'egc89vmz.sbs';
            const n = 'nara' + Math.floor(Math.random() * 899999 + 100000);
            const fullEmail = n + '@' + d;
            document.getElementById('res').innerText = fullEmail;
            
            // Link ke generator.email biar langsung buka inbox
            const inboxLink = "https://generator.email/" + fullEmail;
            const btnCheck = document.getElementById('checkLink');
            btnCheck.href = inboxLink;
            btnCheck.style.display = "block";
        }
        function copy() {
            const t = document.getElementById('res').innerText;
            if(t.includes('KLIK')) return;
            navigator.clipboard.writeText(t).then(() => alert('Tersalin!'));
        }
    </script>
</body>
</html>
