<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head><title>Saudi ARB ANSTA</title>
<meta name="description" content="موقع سعودي المحتوىANSTA المحتوى يقدم خدمات ...">
<meta name="keywords" content="Saudi, ARB, ANSTA, خدمات, موقع سعودي">
<meta name="robots" content="index, follow">

<meta property="og:title" content="Saudi ARB ANSTA">
<meta property="og:description" content="موقع سعودي ARB ANSTA يقدم خدمات ...">
<meta property="og:url" content="https://saudi-arb-ansta.netlify.app/">
<meta property="og:type" content="website">
<meta charset="UTF-8">
<title>Remon | خدمات الريموند</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body {
  margin: 0;
  background: #050816;
  font-family: "Tajawal", sans-serif;
  color: #fff;
  overflow-x: hidden;
}

/* اللوجو */
.logo {
  position: absolute;
  top: 25px;
  right: 25px;
  font-size: 2.4rem;
  font-weight: 800;
  color: #00ff88;
  text-shadow: 0 0 12px #00ff88, 0 0 25px #00ff88;
  letter-spacing: 1px;
  z-index: 10;
}

/* خلفية العلم */
.saudi-flag {
  position: fixed;
  top: -60px;
  left: 0;
  width: 100%;
  height: 130vh;
  background: url('https://upload.wikimedia.org/wikipedia/commons/0/0d/Flag_of_Saudi_Arabia.svg');
  background-size: 95%;
  background-repeat: no-repeat;
  background-position: center;
  opacity: 0.28;
  filter: drop-shadow(0 0 90px #00ff88);
  z-index: -3;
}

/* هالة الضوء */
.green-glow {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background: radial-gradient(circle at center, rgba(0,255,120,0.22), transparent 70%);
  z-index: -4;
}

/* خطوط ضوئية */
.light-lines {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background: repeating-linear-gradient(
    120deg,
    rgba(0,255,120,0.07) 0px,
    rgba(0,255,120,0.07) 2px,
    transparent 2px,
    transparent 6px
  );
  animation: moveLines 9s linear infinite;
  z-index: -2;
}

@keyframes moveLines {
  from { background-position: 0 0; }
  to { background-position: 400px 400px; }
}

/* المحتوى */
.hero {
  text-align: center;
  padding: 140px 20px 60px;
}

.hero h1 {
  font-size: 2.6rem;
  margin-bottom: 10px;
  color: #00ff88;
  text-shadow: 0 0 15px #00ff88;
}

.hero p {
  font-size: 1.2rem;
  color: #d1d5db;
  margin-bottom: 25px;
}

/* الأقسام */
.section {
  max-width: 900px;
  margin: 40px auto;
  padding: 0 20px;
}

.section h2 {
  color: #00ff88;
  font-size: 1.8rem;
  margin-bottom: 15px;
  border-right: 4px solid #00ff88;
  padding-right: 10px;
  display: flex;
  align-items: center;
  gap: 10px;
}

.section h2 img {
  width: 32px;
  height: 32px;
}

/* بطاقة الخدمة */
.service-card {
  background: rgba(255,255,255,0.05);
  padding: 18px;
  border-radius: 14px;
  margin-bottom: 16px;
  border: 1px solid rgba(255,255,255,0.08);
  backdrop-filter: blur(4px);
}

.service-card h3 {
  margin: 0 0 8px;
  color: #00ff88;
}

.service-card a {
  color: #22c55e;
  font-weight: 600;
  text-decoration: none;
}
</style>
</head>

<body>

<div class="logo">Remon</div>

<div class="saudi-flag"></div>
<div class="green-glow"></div>
<div class="light-lines"></div>

<div class="hero">
  <h1>🚀 خدمات الريموند</h1>
  <p>اختر منصتك – ثم اختر خدمتك – وسيتم تحويلك مباشرة للواتساب.</p>
</div>

<!-- ===================== تيك توك ===================== -->
<div class="section">
  <h2>
    <img src="https://cdn-icons-png.flaticon.com/512/3046/3046121.png">
    تيك توك
  </h2>

  <script>
  const tiktok = [
    "🔥 متابعين الأرخص",
    "🇸🇦 متابعين عرب بكج مشاهير",
    "💀 متابعين وهمي",
    "🌍 متابعين حقيقي عرب وأجانب",
    "👥 متابعين عرب حقيقي",
    "❤️ إعجابات فيديو",
    "📺 مشاهدات فيديو",
    "❤️📺 لايكات + مشاهدات فيديو",
    "🎯 مشاهدات لتحقيق شروط الدخل 100k",
    "💰 مشاهدات حقيقية لزيادة الربح",
    "🥊⚔️ زيادة سكور المباريات",
    "✅ مشاهدات بث مباشر",
    "⚡️🚨 مشاهدات بث مباشر مكس",
    "❤️📢 خدمات بث مباشر (إعجابات + تكبيس + تعليقات)",
    "↙️ اكسبلور فيديو",
    "📲 حفظ الفيديو",
    "💬 تعليقات فيديو متنوعة",
    "📍 إعلانات حسب الدولة",
    "🔹 توثيق الحساب"
  ];
  </script>

  <div id="tiktok-box"></div>
</div>

<!-- ===================== انستغرام ===================== -->
<div class="section">
  <h2>
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png">
    انستغرام
  </h2>

  <script>
  const instagram = [
    "⭐️ رفع اكسبلور فيديو عرب",
    "🔰 إزالة الحسابات واسترجاعها",
    "✅ متابعين عرب إعلان ممول",
    "🚀🏅 متابعين جودة عالية",
    "🇦🇪 إعجابات عربية",
    "🛡 إعجابات بضمان",
    "🌍 لايكات دول محددة",
    "🇦🇪 تعليقات عرب",
    "😍✍️🏻 تعليقات متنوعة",
    "🔰 حفظ فيديو",
    "👥 أعضاء قنوات",
    "🎞 مشاهدات ريلز",
    "💬 لايكات على تعليق",
    "📨 منشن / دايركت مسج",
    "🔄 مشاركة",
    "📊 خدمات ستوري + تصويت",
    "📦 باكجات تفاعل حسابات عربية",
    "📆 مشاهدات ستوري اشتراك شهري",
    "💀 مشاهدين بث مباشر وهمي",
    "📈 تصويت ستوري / وصول / لايكات"
  ];
  </script>

  <div id="instagram-box"></div>
</div>

<!-- ===================== تليغرام ===================== -->
<div class="section">
  <h2>
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png">
    تيليجرام
  </h2>

  <script>
  const telegram = [
    "📌 اشتراك توثيق",
    "🛡 تعزيز",
    "📊 تصويت",
    "💰 أعضاء قناة الأرخص",
    "🇦🇪 أعضاء قناة عرب حقيقي",
    "👁‍🗨 مشاهدات المنشور",
    "😍😂❤️ رد فعل منشورات",
    "🤖 بدء بوت",
    "🔗 إحالات بوت",
    "👑 إحالات نشطة وحقيقية",
    "🎖 بدء بوت بريميوم",
    "🔁 أعضاء + مشاهدات بريميوم",
    "😊 تفاعل بريميوم",
    "🔎 تحسين البحث 1",
    "⛔️ إزالة قنوات نهائي"
  ];
  </script>

  <div id="telegram-box"></div>
</div>

<!-- ===================== تويتر ===================== -->
<div class="section">
  <h2>
    <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png">
    تويتر
  </h2>

  <script>
  const twitter = [
    "⭐️💯 رفع هاشتاج ترند",
    "🌐 خدمات المجتمع",
    "👥 متابعين",
    "📊 تصويت",
    "👆🏻 نقرات",
    "🔁 ريتويت",
    "❤️ لايكات",
    "💬 تعليقات",
    "📣 منشن",
    "📨 دايركت مسج",
    "🎥 مشاهدات فيديو",
    "📝 مشاهدات تغريدات",
    "📺 مشاهدات بث مباشر",
    "🌍 لايكات + ريتويت (دول محددة)",
    "🎧 مستمعين Space",
    "🎧 مستمعين Space (سيرفر 2)",
    "🌐 مشاهدات مستهدفة (فيديو + تغريدة)"
  ];
  </script>

  <div id="twitter-box"></div>
</div>

<!-- ===================== فيسبوك ===================== -->
<div class="section">
  <h2>
    <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png">
    فيس بوك
  </h2>

  <script>
  const facebook = [
    "✅️ متابعين صفحة عامة",
    "👍🏻 إعجابات صفحة",
    "🫂 إعجابات + متابعين",
    "👥 أعضاء المجموعة",
    "🎥 مشاهدات",
    "💲 مشاهدات لتحقيق الأرباح",
    "❤️ إعجابات منشورات",
    "❤️👍🏻 إعجابات منشور رخيص",
    "❤️👍🏻 إعجابات منشور متنوعة",
    "🚀 إعجابات منشور سريع حقيقي",
    "💬 لايكات على تعليق",
    "🇸🇦 خدمات عربية",
    "🇸🇦 إعجابات منشور عرب",
    "🇵🇸 تعليقات عرب جديد",
    "🇸🇦 تعليقات عربية",
    "🎞 مشاهدات ستوري + تصويت",
    "⭐️ تقييمات - توصيات - طلبات صداقة",
    "⭐️ تقييمات صفحة عربية"
  ];
  </script>

  <div id="facebook-box"></div>
</div>

<!-- ===================== يوتيوب ===================== -->
<div class="section">
  <h2>
    <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png">
    يوتيوب
  </h2>

  <script>
  const youtube = [
    "💲 قناة جاهزة للربح",
    "🛡 خدمات تحقيق الدرع الفضي",
    "⏳ ساعات مشاهدة للدخل",
    "⏰️ مشتركين بطيء ورخيص",
    "🥇 مشتركين ضمان",
    "👍🏻 لايكات بدون ضمان",
    "✅️ لايكات بضمان",
    "🥇 مشاهدات بضمان",
    "🌍 مشاهدات دول محددة",
    "🇸🇦 مشاهدات Adwords عربية",
    "🎬 خدمات Shorts",
    "🌍 لايكات مستهدفة",
    "🇸🇦 خدمات عربية",
    "✅️ مشاهدين بث مباشر",
    "✍️🏻 تعليقات",
    "❤️ لايكات لتعليق",
    "🇦🇪✍️🏻 تعليقات عرب حسب البلد"
  ];
  </script>

  <div id="youtube-box"></div>
</div>

<script>
function render(list, id) {
  let box = document.getElementById(id);
  list.forEach(service => {
    box.innerHTML += `
      <div class="service-card">
        <h3>${service}</h3>
        <a href="https://wa.me/+963998832448?text=أريد%20خدمة:%20${service}">اطلب الآن</a>
      </div>
    `;
  });
}

render(tiktok, "tiktok-box");
render(instagram, "instagram-box");
render(telegram, "telegram-box");
render(twitter, "twitter-box");
render(facebook, "facebook-box");
render(youtube, "youtube-box");
</script>

</body>
</html>
