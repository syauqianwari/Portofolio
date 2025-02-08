<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Syauqi Anwari - Linktree</title>
    <style>
        /* Reset margin dan padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Style untuk body */
        body {
            background-color: #f9f9f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            text-align: center;
        }

        /* Foto profil */
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #ff8c8c;
            margin-bottom: 10px;
        }

        /* Nama heading */
        h1 {
            font-size: 24px;
            color: #333;
            margin-bottom: 10px;
        }

        /* Deskripsi singkat */
        p {
            color: #666;
            margin-bottom: 20px;
        }

        /* Style untuk tombol link */
        .link-container {
            width: 100%;
            max-width: 300px;
        }

        .link {
            display: block;
            background: salmon;
            color: white;
            text-decoration: none;
            padding: 12px;
            margin: 8px 0;
            border-radius: 25px;
            font-size: 16px;
            font-weight: bold;
            transition: 0.3s;
        }

        .link:hover {
            background: #ff6f61;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <!-- Foto Profil -->
    <img src="https://via.placeholder.com/120" alt="Foto Syauqi" class="profile-pic">

    <!-- Nama -->
    <h1>Syauqi Anwari</h1>
    <p>Animator | Penulis | Kreator</p>

    <!-- Link Container -->
    <div class="link-container">
        <a href="https://www.youtube.com" class="link" target="_blank">YouTube</a>
        <a href="https://www.instagram.com" class="link" target="_blank">Instagram</a>
        <a href="https://www.tiktok.com" class="link" target="_blank">TikTok</a>
        <a href="https://www.syauqianwari.com" class="link" target="_blank">Website</a>
    </div>

</body>
</html>
