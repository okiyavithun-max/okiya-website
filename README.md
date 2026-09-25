# okiya-website
හිනාව මගෙ රස්සාව
<!DOCTYPE html>
<html lang="si">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>AI පොඩ්ඩා</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #080018, #160044, #001d3d);
    color: white;
    min-height: 100vh;
    overflow-x: hidden;
}

/* Header */
header {
    text-align: center;
    padding: 35px 15px 20px;
}

header h1 {
    font-size: 48px;
    color: #00eaff;
    text-shadow: 0 0 20px #00eaff;
}

header p {
    margin-top: 10px;
    font-size: 18px;
    color: #ddd;
}

/* Main */
.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

/* Profile */
.profile {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 40px;
    margin-top: 30px;
    flex-wrap: wrap;
}

.photo-box {
    width: 280px;
    height: 280px;
    border-radius: 50%;
    border: 5px solid #00eaff;
    box-shadow: 0 0 35px #00eaff;
    overflow: hidden;
    background: #111;
}

.photo-box img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

/* Text */
.intro {
    max-width: 600px;
}

.intro h2 {
    font-size: 32px;
    color: #ff4fd8;
    margin-bottom: 15px;
}

.intro p {
    font-size: 18px;
    line-height: 1.8;
    color: #eee;
}

/* Cards */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 20px;
    margin-top: 45px;
}

.card {
    background: rgba(255,255,255,0.08);
    border: 1px solid rgba(0,234,255,0.5);
    border-radius: 20px;
    padding: 25px;
    text-align: center;
    backdrop-filter: blur(10px);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-8px);
    box-shadow: 0 0 25px #00eaff;
}

.card h3 {
    color: #00eaff;
    margin-bottom: 12px;
}

.card p {
    line-height: 1.6;
    color: #ddd;
}

/* Moving OKINDU */
.moving-area {
    width: 100%;
    overflow: hidden;
    margin-top: 50px;
    border-top: 2px solid #ff4fd8;
    border-bottom: 2px solid #ff4fd8;
    padding: 15px 0;
    background: rgba(255, 0, 200, 0.08);
}

.moving-text {
    display: inline-block;
    white-space: nowrap;
    font-size: 35px;
    font-weight: bold;
    color: #ff4fd8;
    text-shadow: 0 0 15px #ff4fd8;
    animation: moveText 8s linear infinite;
}

@keyframes moveText {
    from {
        transform: translateX(100vw);
    }
    to {
        transform: translateX(-100%);
    }
}

/* Footer */
footer {
    text-align: center;
    padding: 35px 15px;
    margin-top: 50px;
    color: #aaa;
}

footer strong {
    color: #00eaff;
}

/* Mobile */
@media (max-width: 600px) {
    header h1 {
        font-size: 38px;
    }

    .photo-box {
        width: 220px;
        height: 220px;
    }

    .intro {
        text-align: center;
    }

    .intro h2 {
        font-size: 27px;
    }

    .intro p {
        font-size: 16px;
    }

    .moving-text {
        font-size: 28px;
    }
}
</style>
</head>

<body>

<header>
    <h1>AI පොඩ්ඩා</h1>
    <p>AI තාක්ෂණය සහ AI වීඩියෝ ලෝකය</p>
</header>

<div class="container">

    <section class="profile">

        <!-- ඔයාගේ Photo එක මෙතනට දාන්න -->
        <div class="photo-box">
            <img src="photo.jpg" alt="AI පොඩ්ඩා">
        </div>

        <div class="intro">
            <h2>AI පොඩ්ඩා වෙත සාදරයෙන් පිළිගනිමු!</h2>

            <p>
                AI පොඩ්ඩා හරහා නවීන AI තාක්ෂණය,
                AI වීඩියෝ නිර්මාණය සහ AI භාවිතයෙන්
                සිදු කළ හැකි අලුත් දේවල් ගැන
                සරලව හා පහසුවෙන් දැනගන්න පුළුවන්.
            </p>
        </div>

    </section>

    <section class="cards">

        <div class="card">
            <h3>🎬 AI වීඩියෝ</h3>
            <p>
                AI භාවිතයෙන් ලස්සන වීඩියෝ
                නිර්මාණය කරන ආකාරය ගැන
                තොරතුරු ලබාගන්න.
            </p>
        </div>

        <div class="card">
            <h3>🤖 AI තාක්ෂණය</h3>
            <p>
                නවීන Artificial Intelligence
                තාක්ෂණය ගැන සරලව ඉගෙනගන්න.
            </p>
        </div>

        <div class="card">
            <h3>✨ AI Tools</h3>
            <p>
                වැඩ පහසු කරගැනීමට භාවිතා කළ හැකි
                විවිධ AI tools ගැන දැනගන්න.
            </p>
        </div>

    </section>

</div>

<!-- OKINDU ගමන් කරන කොටස -->
<div class="moving-area">
    <div class="moving-text">
        O-K-I-N-D-U &nbsp;&nbsp;&nbsp; • &nbsp;&nbsp;&nbsp;
        ඔක්කිතූ &nbsp;&nbsp;&nbsp; • &nbsp;&nbsp;&nbsp;
        O-K-I-N-D-U
    </div>
</div>

<footer>
    © 2026 <strong>AI පොඩ්ඩා</strong> — AI තාක්ෂණය සමඟ ඉදිරියට 🚀
</footer>

</body>
</html>
