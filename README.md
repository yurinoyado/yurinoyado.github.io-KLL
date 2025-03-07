<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guesthouse Rakuen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFFAF0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #FF6347;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 10px 0;
        }
        nav button {
            margin: 5px;
            padding: 10px 20px;
            background-color: #FF7F50;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        nav button:hover {
            background-color: #FF4500;
        }
        .content {
            display: none;
            padding: 20px;
        }
        .content.active {
            display: block;
        }
        .image-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
            padding: 10px;
        }
        .image-gallery img {
            width: 100%;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #FF6347;
            color: white;
        }
    </style>
    <script>
        function switchLanguage(lang) {
            document.querySelectorAll('.content').forEach(div => {
                div.classList.remove('active');
            });
            document.getElementById(lang).classList.add('active');
        }
    </script>
</head>
<body>
    <header>
        <h1>百合の宿(桃谷駅前館）</h1>
    </header>

    <nav>
        <button onclick="switchLanguage('english')">English</button>
        <button onclick="switchLanguage('chinese')">中文</button>
        <button onclick="switchLanguage('japanese')">日本語</button>
    </nav>

    <div id="english" class="content active">
        <h2>Guesthouse Yurinoyado</h2>
        <p>Experience the charm of traditional Japanese culture in a private house located within walking distance to Tsutenkaku and Tennoji. Just a 5-minute trip to Namba or Nipponbashi!</p>
        <p>Designed by a renowned Japanese designer, this exquisite guesthouse is near bustling shopping streets and can accommodate up to 4 guests.</p>
        <p>Address: 3-6-18 Sanno, Nishinari-ku, Osaka-shi</p>
        <p>Reservation Requirement: Minimum stay of 3 days and 2 nights.</p>
        <p>Languages: English, Chinese, Japanese</p>
        <p>Contact: +81 070-2610-9074 | Email: xuping201013@gmail.com</p>

        <div class="image-gallery">
            <img src="https://imgur.com/3z9EafB.jpg" alt="Guesthouse Image 1">
            <img src="https://imgur.com/B26RgM0.jpg" alt="Guesthouse Image 2">
            <img src="https://imgur.com/G9PpEOT.jpg" alt="Guesthouse Image 3">
            <img src="https://imgur.com/7sSF1wW.jpg" alt="Guesthouse Image 4">
        </div>
    </div>

    <div id="chinese" class="content">
        <h2>百合の宿</h2>
        <p>深度体验日本传统文化的独栋民居，步行圈内即达通天阁、天王寺，5分钟直达难波、日本桥！</p>
        <p>由日本知名设计师打造的精装民宿，邻近繁华商业街，可容纳最多4人。</p>
        <p>地址：大阪市西成区山王3-6-18</p>
        <p>预定要求：2泊3日以上</p>
        <p>对应语言：英语、中文、日语</p>
        <p>联系方式：+81 070-2610-9074 | 邮箱: xuping201013@gmail.com</p>

        <div class="image-gallery">
            <img src="https://imgur.com/3z9EafB.jpg" alt="民宿图片 1">
            <img src="https://imgur.com/B26RgM0.jpg" alt="民宿图片 2">
            <img src="https://imgur.com/G9PpEOT.jpg" alt="民宿图片 3">
            <img src="https://imgur.com/7sSF1wW.jpg" alt="民宿图片 4">
        </div>
    </div>

    <div id="japanese" class="content">
        <h2>百合の宿</h2>
        <p>日本の伝統文化を深く体験できる一戸建ての宿泊施設です。徒歩圏内には通天閣や天王寺があり、なんばや日本橋へも5分で行けます。</p>
        <p>日本の有名なデザイナーによって設計された洗練された民宿で、最大4名まで宿泊可能です。</p>
        <p>住所：大阪市西成区山王3-6-18</p>
        <p>予約条件：2泊3日以上</p>
        <p>対応言語：英語、中国語、日本語</p>
        <p>連絡先：+81 070-2610-9074 | メール: xuping201013@gmail.com</p>

        <div class="image-gallery">
            <img src="https://imgur.com/3z9EafB.jpg" alt="ゲストハウス画像 1">
            <img src="https://imgur.com/B26RgM0.jpg" alt="ゲストハウス画像 2">
            <img src="https://imgur.com/G9PpEOT.jpg" alt="ゲストハウス画像 3">
            <img src="https://imgur.com/7sSF1wW.jpg" alt="ゲストハウス画像 4">
        </div>
    </div>

    <footer>
        <p>Contact us at: +81 070-2610-9074 | Email: 2629842378@qq.com</p>
    </footer>
</body>
</html>
