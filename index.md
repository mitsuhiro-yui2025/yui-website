<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welfare×IT 結（Yui）- ホームページ</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700&family=Noto+Serif+JP:wght@400;700&family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
            background-color: #FFFDF5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .slide-container {
            width: 1280px;
            min-height: 720px;
            margin: 0 auto;
            position: relative;
            overflow: hidden;
            background-color: #FFFDF5;
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%"><defs><filter id="blur" x="0" y="0"><feGaussianBlur stdDeviation="10" /></filter></defs><rect width="100%" height="100%" fill="%23FFFDF5"/><g filter="url(%23blur)"><rect x="20%" y="20%" width="60%" height="60%" fill="%23F5F5F0" opacity="0.3"/><circle cx="70%" cy="30%" r="15%" fill="%23C5D86D" opacity="0.1"/><circle cx="30%" cy="70%" r="20%" fill="%23E86C3A" opacity="0.1"/></g></svg>');
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
        }
        .content-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(255,253,245,0.9) 0%, rgba(255,253,245,0.7) 100%);
            z-index: 1;
        }
        .slide-content {
            padding: 80px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: flex-start;
            height: 100%;
            position: relative;
            z-index: 2;
        }
        .title-container {
            margin-bottom: 60px;
        }
        .title {
            font-family: 'Montserrat', 'Noto Serif JP', serif;
            font-size: 6.5rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
            color: #333;
            line-height: 1.2;
            letter-spacing: -0.02em;
        }
        .title .highlight {
            color: #E86C3A;
        }
        .subtitle {
            font-size: 2.2rem;
            font-weight: 500;
            margin-bottom: 2rem;
            color: #4A4A4A;
            line-height: 1.4;
        }
        .accent-line {
            height: 6px;
            width: 180px;
            background-color: #E86C3A;
            margin: 2rem 0;
        }
        .caption {
            font-size: 1.5rem;
            font-weight: 300;
            line-height: 1.7;
            max-width: 80%;
            color: #555;
        }
        .logo {
            position: absolute;
            bottom: 40px;
            right: 50px;
            width: 180px;
            height: 180px;
            z-index: 3;
            border-radius: 50%;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            overflow: hidden;
            border: 3px solid #fff;
        }
        .logo img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
        .decoration {
            position: absolute;
        }
        .leaf-1 {
            top: 50px;
            right: 150px;
            transform: rotate(30deg);
            font-size: 5rem;
            color: #C5D86D;
            opacity: 0.2;
            z-index: 1;
        }
        .leaf-2 {
            bottom: 100px;
            left: 100px;
            transform: rotate(-15deg);
            font-size: 4rem;
            color: #E86C3A;
            opacity: 0.2;
            z-index: 1;
        }
        .welfare-icon {
            position: absolute;
            right: 280px;
            top: 220px;
            font-size: 8rem;
            color: rgba(197, 216, 109, 0.15);
            z-index: 1;
        }
        .tech-icon {
            position: absolute;
            right: 150px;
            top: 320px;
            font-size: 6rem;
            color: rgba(232, 108, 58, 0.15);
            z-index: 1;
        }
        .plus-sign {
            display: inline-block;
            font-size: 4rem;
            vertical-align: middle;
            margin: 0 1rem;
            color: #C5D86D;
        }
    </style>
</head>
<body>
    <div class="slide-container">
        <div class="content-overlay"></div>
        
        <!-- Decorative elements -->
        <i class="fas fa-leaf decoration leaf-1"></i>
        <i class="fas fa-leaf decoration leaf-2"></i>
        <i class="fas fa-hands-helping decoration welfare-icon"></i>
        <i class="fas fa-laptop-code decoration tech-icon"></i>
        
        <div class="slide-content">
            <div class="title-container">
                <h1 class="title"><span class="highlight">Welfare</span> <span class="plus-sign">×</span> IT</h1>
                <div class="accent-line"></div>
                <h2 class="subtitle">福祉の現場に、寄り添うDX支援を。</h2>
                <p class="caption">業務改善に悩む福祉現場へ、kintoneを活用した伴走支援を行います。</p>
            </div>
            
            <!-- Logo -->
            <div class="logo">
                <img src="https://page.genspark.site/v1/base64_upload/5e7dc3802331ee21ab494093df468d51" alt="結（Yui）ロゴ">
            </div>
        </div>
    </div>
</body>
</html>
