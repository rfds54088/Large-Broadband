[index.html](https://github.com/user-attachments/files/32217188/index.html)
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>大大寬頻｜苗栗信和｜黃紹軒專人申辦</title>

    <meta name="description"
          content="苗栗信和大大寬頻專人申辦服務，提供寬頻網路、數位有線電視及相關方案諮詢。">

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family:
                -apple-system,
                BlinkMacSystemFont,
                "Noto Sans TC",
                "Microsoft JhengHei",
                sans-serif;
            background: #f5f5f5;
            color: #222;
            line-height: 1.7;
        }

        /* 頂部 */
        header {
            background: #d71920;
            color: white;
            padding: 15px 20px;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.15);
        }

        .header-inner {
            max-width: 1100px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 20px;
            font-weight: bold;
        }

        .phone-top {
            background: white;
            color: #d71920;
            padding: 7px 14px;
            border-radius: 30px;
            font-weight: bold;
            text-decoration: none;
        }

        /* Hero */
        .hero {
            background:
                linear-gradient(
                    rgba(0,0,0,0.45),
                    rgba(0,0,0,0.45)
                ),
                linear-gradient(135deg, #d71920, #ff5a5f);

            color: white;
            padding: 70px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 36px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 19px;
            margin-bottom: 30px;
        }

        .main-button {
            display: inline-block;
            background: #fff;
            color: #d71920;
            padding: 14px 35px;
            border-radius: 40px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        /* 區塊 */
        section {
            max-width: 1100px;
            margin: auto;
            padding: 55px 20px;
        }

        .section-title {
            text-align: center;
            font-size: 28px;
            margin-bottom: 35px;
        }

        .section-title span {
            color: #d71920;
        }

        /* 卡片 */
        .cards {
            display: grid;
            grid-template-columns:
                repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 28px 20px;
            text-align: center;
            box-shadow: 0 3px 15px rgba(0,0,0,0.08);
        }

        .card-icon {
            font-size: 45px;
            margin-bottom: 10px;
        }

        .card h3 {
            font-size: 21px;
            margin-bottom: 8px;
        }

        .card p {
            color: #666;
        }

        /* 方案 */
        .plans {
            display: grid;
            grid-template-columns:
                repeat(auto-fit, minmax(240px, 1fr));
            gap: 20px;
        }

        .plan {
            background: white;
            border-radius: 15px;
            padding: 30px 20px;
            text-align: center;
            border: 2px solid transparent;
            box-shadow: 0 3px 15px rgba(0,0,0,0.08);
        }

        .plan:hover {
            border-color: #d71920;
        }

        .plan h3 {
            color: #d71920;
            font-size: 23px;
        }

        .plan .speed {
            font-size: 32px;
            font-weight: bold;
            margin: 15px 0;
        }

        .plan p {
            color: #666;
        }

        /* 服務區域 */
        .area {
            background: #fff;
            text-align: center;
        }

        .area-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 12px;
        }

        .area-list span {
            background: #f1f1f1;
            padding: 10px 18px;
            border-radius: 30px;
        }

        /* 業務 */
        .agent {
            background: #222;
            color: white;
            text-align: center;
            border-radius: 20px;
            padding: 45px 20px;
        }

        .agent h2 {
            font-size: 30px;
            margin-bottom: 10px;
        }

        .agent .name {
            font-size: 25px;
            color: #ff5252;
            font-weight: bold;
        }

        .agent .phone {
            display: inline-block;
            margin-top: 20px;
            font-size: 30px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        /* 底部 */
        footer {
            background: #111;
            color: #aaa;
            text-align: center;
            padding: 30px 20px 100px;
            font-size: 14px;
        }

        /* 手機底部固定按鈕 */
        .mobile-contact {
            display: none;
        }

        @media (max-width: 600px) {

            .hero {
                padding: 55px 20px;
            }

            .hero h1 {
                font-size: 29px;
            }

            .hero p {
                font-size: 17px;
            }

            .phone-top {
                font-size: 14px;
            }

            .mobile-contact {
                display: flex;
                position: fixed;
                bottom: 0;
                left: 0;
                right: 0;
                z-index: 999;
            }

            .mobile-contact a {
                flex: 1;
                text-align: center;
                padding: 14px;
                text-decoration: none;
                color: white;
                font-weight: bold;
                font-size: 17px;
            }

            .call {
                background: #d71920;
            }

            .line {
                background: #00b900;
            }
        }
    </style>
</head>

<body>

<!-- 頂部 -->
<header>
    <div class="header-inner">

        <div class="logo">
            大大寬頻｜苗栗信和
        </div>

        <a class="phone-top"
           href="tel:0923866992">
            📞 0923-866-992
        </a>

    </div>
</header>


<!-- 主視覺 -->
<div class="hero">

    <h1>大大寬頻・苗栗信和</h1>

    <p>
        寬頻網路｜數位有線電視｜專人申辦諮詢
    </p>

    <a class="main-button"
       href="tel:0923866992">
        📞 立即諮詢
    </a>

</div>


<!-- 服務 -->
<section>

    <h2 class="section-title">
        <span>一站式</span> 寬頻服務
    </h2>

    <div class="cards">

        <div class="card">
            <div class="card-icon">🌐</div>
            <h3>寬頻網路</h3>
            <p>
                提供家庭及各種使用需求的網路方案。
            </p>
        </div>

        <div class="card">
            <div class="card-icon">📺</div>
            <h3>數位電視</h3>
            <p>
                多元頻道內容，滿足全家娛樂需求。
            </p>
        </div>

        <div class="card">
            <div class="card-icon">📡</div>
            <h3>網路＋電視</h3>
            <p>
                依照需求搭配適合的組合方案。
            </p>
        </div>

        <div class="card">
            <div class="card-icon">👨‍💼</div>
            <h3>專人服務</h3>
            <p>
                有問題直接聯絡業務，協助方案諮詢。
            </p>
        </div>

    </div>

</section>


<!-- 網路方案 -->
<section>

    <h2 class="section-title">
        <span>大大寬頻</span> 光纖網路方案
    </h2>

    <p style="text-align:center; color:#666; margin-bottom:30px;">
        苗栗信和地區｜專人申辦諮詢
    </p>

    <div class="plans">

        <div class="plan">
            <h3>120M</h3>

            <div class="speed">
                $399
            </div>

            <p>／月</p>

            <p>高速光纖寬頻</p>

            <a class="main-button"
               href="tel:0923866992"
               style="margin-top:20px; font-size:16px; padding:10px 22px;">
                📞 立即詢問
            </a>
        </div>


        <div class="plan">
            <h3>200M</h3>

            <div class="speed">
                $499
            </div>

            <p>／月</p>

            <p>高速光纖寬頻</p>

            <a class="main-button"
               href="tel:0923866992"
               style="margin-top:20px; font-size:16px; padding:10px 22px;">
                📞 立即詢問
            </a>
        </div>


        <div class="plan">
            <h3>300M</h3>

            <div class="speed">
                $599
            </div>

            <p>／月</p>

            <p>高速光纖寬頻</p>

            <p style="color:#d71920; font-weight:bold;">
                🎁 免費租用 WiFi 6 AP
            </p>

            <a class="main-button"
               href="tel:0923866992"
               style="margin-top:20px; font-size:16px; padding:10px 22px;">
                📞 立即詢問
            </a>
        </div>


        <div class="plan">
            <h3>500M</h3>

            <div class="speed">
                $699
            </div>

            <p>／月</p>

            <p>高速光纖寬頻</p>

            <p style="color:#d71920; font-weight:bold;">
                🎁 免費租用 WiFi 6 AP
            </p>

            <a class="main-button"
               href="tel:0923866992"
               style="margin-top:20px; font-size:16px; padding:10px 22px;">
                📞 立即詢問
            </a>
        </div>

    </div>

    <p style="
        text-align:center;
        margin-top:25px;
        color:#888;
        font-size:14px;
    ">
        ※ 實際優惠、申辦資格及設備內容依申辦當期活動為準。
    </p>

</section>

<!-- 服務區域 -->
<section class="area">

    <h2 class="section-title">
        <span>苗栗地區</span> 專人服務
    </h2>

    <div class="area-list">

        <span>頭份</span>
        <span>竹南</span>
        <span>三灣</span>
        <span>造橋</span>
        <span>南庄</span>
        <span>苗栗地區</span>

    </div>

</section>


<!-- 業務聯絡 -->
<section>

    <div class="agent">

        <h2>📞 專人申辦服務</h2>

        <p>想了解目前優惠方案？</p>
        <p>歡迎直接聯絡我，我幫您說明。</p>

        <div class="name">
            黃紹軒
        </div>

        <a class="phone"
           href="tel:0923866992">
            0923-866-992
        </a>

    </div>

</section>


<!-- 頁尾 -->
<footer>

    <p>
        本頁為業務個人申辦資訊頁
    </p>

    <p>
        實際方案、費用及優惠內容依申辦當時官方公告與資格為準。
    </p>

</footer>


<!-- 手機固定按鈕 -->
<div class="mobile-contact">

    <a class="call"
       href="tel:0923866992">
        📞 立即電話
    </a>

    <a class="line"
   href="https://line.me/ti/p/WZyBc33Fz3"
   target="_blank">
    LINE 諮詢
</a>

</div>


</body>
</html>
