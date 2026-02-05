<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>love you❤ NoNo ❤</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
    body {
        margin: 0;
        font-family: 'Segoe UI', Tahoma, sans-serif;
        background: linear-gradient(135deg, #ff77c6, #8b5cf6);
        min-height: 100vh;
        overflow-x: hidden;
        color: #fff;
        text-align: center;
    }

    /* قلوب متحركة خلفية */
    .hearts {
        position: fixed;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        pointer-events: none;
        z-index: 0;
    }
    .heart {
        position: absolute;
        width: 10px;
        height: 10px;
        background: rgba(255,255,255,0.7);
        transform: rotate(45deg);
        animation: floatUp 6s linear infinite;
    }
    .heart:before, .heart:after {
        content: "";
        position: absolute;
        width: 10px;
        height: 10px;
        background: rgba(255,255,255,0.7);
        border-radius: 50%;
    }
    .heart:before { top: -5px; left: 0; }
    .heart:after { left: -5px; top: 0; }
    @keyframes floatUp {
        0% { transform: translateY(0) rotate(45deg); opacity:1;}
        100% { transform: translateY(-800px) rotate(45deg); opacity:0;}
    }

    .container {
        position: relative;
        z-index: 1;
        max-width: 800px;
        margin: auto;
        padding: 40px 20px;
    }

    h1 {
        font-size: 2.5em;
        margin-bottom: 20px;
    }

    .card {
        background: rgba(255, 255, 255, 0.15);
        backdrop-filter: blur(10px);
        border-radius: 20px;
        padding: 25px;
        margin: 20px 0;
        box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        line-height: 1.9;
        text-align: right;
        direction: rtl;
    }

    img {
        max-width: 100%;
        border-radius: 15px;
        margin: 20px 0;
        box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }

    audio {
        width: 100%;
        margin-top: 15px;
    }

    .question {
        font-size: 1.4em;
        margin: 20px 0;
        font-weight: bold;
    }

    .hidden {
        display: none;
    }

    .password-box {
        position: fixed;
        inset: 0;
        background: linear-gradient(135deg, #ff77c6, #8b5cf6);
        display: flex;
        align-items: center;
        justify-content: center;
        z-index: 999;
        color: white;
        text-align: center;
    }

    .password-card {
        background: rgba(255,255,255,0.15);
        backdrop-filter: blur(10px);
        padding: 30px;
        border-radius: 20px;
        width: 90%;
        max-width: 350px;
    }

    input {
        width: 100%;
        padding: 12px;
        margin-top: 15px;
        border-radius: 10px;
        border: none;
        font-size: 1em;
        text-align: center;
    }

    button {
        margin-top: 15px;
        padding: 10px 20px;
        border-radius: 10px;
        border: none;
        font-size: 1em;
        background: #fff;
        color: #8b5cf6;
        cursor: pointer;
        font-weight: bold;
        transition: transform 0.2s;
    }

    button:hover { transform: scale(1.1); }

    .question-buttons {
        margin: 15px 0;
    }

</style>
</head>

<body>

<!-- شاشة الباسورد -->
<div class="password-box" id="passwordBox">
    <div class="password-card">
        <h3>اكتبي الباسورد يا كتكوتي 🐣❤️</h3>
        <p>هتفضلي معايا يا حبيبتي؟ 🥹❤</p>
        <input type="password" id="passwordInput" placeholder="••••••">
        <button onclick="checkPassword()">دخول</button>
    </div>
</div>

<div class="hearts" id="heartsContainer"></div>

<!-- محتوى الصفحة بعد إدخال الباسورد -->
<div class="container hidden" id="content">
    <h1>love you❤ NoNo ❤</h1>

    <!-- الرسالة -->
    <div class="card">
        <p>
To Mernety🌸،<br>
يمكن اللينك ده بسيط بس الإحساس اللي وراه حقيقي ❤️<br><br>

ميرنا انا بجد بحبك اوي فوق ما تتصوري 😍✨<br><br>

و عايزك تعرفي اني جنبك ع طول و عمري ما هتخلي عنك ولا اسيبك ع نتي هديتي من ربنا و اغلي حاجة ف دنيتي و استحاله افرط فيكي 🌏❤<br><br>

عايزك تعرفي انك بالنسبالي حبيبتي و صحبتي و بنتي👧🏻 و مراتي 💍و امي و اختي و قلبي و عقلي و روحي و دنيتي🌏 و احلي حاجه شافتها عيوني 🥹❤<br><br>

ميرنا بجد انا ماما هقول عمري ما هقدر اوصف حبي ليكي و ماما قالت هيكون قليل ف حقك ع نتي متتوصفيش ب كلام 💗💗<br><br>

عايزك طول ما انا معاكي متحسيش انك لوحدك او تحسيش انك خايفه او ضعيفه ع انا جنبك و معاكي و ف ضهرك ف اي حاجه و اول واحد هيكون ف صفك مهما عملتي 🤍😘<br><br>

بجد م عايزك تزعلي من اي حاجه و متزعليش من نتيجتك نتي عملتي الي عليكي و هما ظلموكي ونا عارف انك المفروض تجيبي احسن من كد. بس الحمدلله ❤<br><br>

و بجد بحبك اوييييي و ربنا يخليكي ليا وميحرمنيش منك ابدا و تفضلي جنبي لاخر العمر و ربنا يجمعنا ف حلاله ❤🌍<br><br>

بحبك يا نونو 😍
        </p>
    </div>

    <!-- الصورة -->
    <img src="https://i.ibb.co/yBf1H5qp/image.jpg" alt="Love Image">

    <!-- السؤال + زرار Yes / No -->
    <div class="question">
        تعرفي إني بحبك؟ ❤️
    </div>

    <div class="question-buttons">
        <button onclick="answerYes()">Yes</button>
        <button onclick="answerNo()">No</button>
    </div>

    <!-- رسالة الرد تظهر بعد الضغط -->
    <div id="answerMessage" class="card hidden"></div>

    <!-- الأغنية -->
    <audio controls autoplay loop>
        <source src="https://causal-jade-3oort98erg.edgeone.app/مهرجان%20روح%20قلبى%20الكريمة%20-%20انا%20غايب%20بمزاجى%20-%20عصام%20صاصا%20-%20توزيع%20كيمو%20الديب%20-%20انتاج%20حبيشة(MP3_1.mp3" type="audio/mpeg">
    </audio>

    <!-- الخاتمة -->
    <div class="card" style="text-align:center;">
        <p>
            اللينك ده مش مجرد هدية 🎁<br><br>
            ده تذكير ليكي انك ع طول ف بالي<br>
            و هفضل احبك لاخر نفس ف عمري 💖💜✨<br><br>
            خليكي عارفه إنك تستاهلي اكتر من كل دا ❤️🌹
        </p>
    </div>
</div>

<script>
// Password check
function checkPassword() {
    const pass = document.getElementById("passwordInput").value;
    if (pass === "241109") {
        document.getElementById("passwordBox").style.display = "none";
        document.getElementById("content").classList.remove("hidden");
    } else {
        alert("الباسورد غلط يا كتكوتي 🥹");
    }
}

// إنشاء قلوب متحركة في الخلفية
const heartsContainer = document.getElementById("heartsContainer");
for(let i=0;i<40;i++){
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.style.left = Math.random()*100 + "vw";
    heart.style.animationDuration = (4 + Math.random()*4) + "s";
    heart.style.width = heart.style.height = (8 + Math.random()*12) + "px";
    heartsContainer.appendChild(heart);
}

// ردود زرار Yes / No
function answerYes() {
    const msg = document.getElementById("answerMessage");
    msg.innerHTML = "عرفتي إني بحبك أوي 😍💖";
    msg.classList.remove("hidden");
}

function answerNo() {
    const msg = document.getElementById("answerMessage");
    msg.innerHTML = "مش مهم… أنا هفضل أحبك دايمًا 🥹❤️";
    msg.classList.remove("hidden");
}
</script>

</body>
</html>
