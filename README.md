<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>إلى أمي الغالية</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: 'Arial', sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff6347;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
        }

        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #ff6347;
            font-size: 2em;
            margin-bottom: 15px;
        }

        p {
            font-size: 1.2em;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        .mom-image {
            max-width: 100%;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .button {
            background-color: #ff6347;
            color: white;
            padding: 10px 20px;
            font-size: 1em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #ff4500;
        }

        .hidden-message {
            display: none;
            font-size: 1.2em;
            margin-top: 20px;
            color: #ff6347;
        }

        footer {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }

        .quote {
            font-style: italic;
            margin-bottom: 20px;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        إلى أمي الغالية
    </header>

    <div class="container">
        <h2>مقدمة</h2>
        <p>أمي العزيزة، لا أستطيع أن أصف كم أحبك بكلمات. أنتِ مصدر القوة والمحبة في حياتي. مهما قلت وفعلت، لن أستطيع أن أوفيكِ حقك. هذه الصفحات مخصصة لكِ، لتعبر عن حبي وامتناني لكل ما قدمتيه لي.</p>

        <h2>رسائل المحبة</h2>
        <p>أنتِ النور الذي يضيء لي كل درب، وأنتِ الحنان الذي يلهمني كل يوم. أشكرك من أعماق قلبي على كل التضحيات التي قدمتيها من أجلي. بدونك، لن أكون ما أنا عليه اليوم.</p>

        <div>
            <img src="images/mother.jpg" alt="أمي" class="mom-image">
        </div>

        <h2>لحظات لا تُنسى</h2>
        <p>أتذكر كل لحظة عشناها معًا، من أيام الطفولة إلى الآن. كل لحظة كانت مليئة بالحب والضحك. لا شيء في هذا العالم يمكنه أن يعوض عن تلك الذكريات الجميلة.</p>
        <p class="quote">"الرب نوري وخلاصي؛ ممن أخاف؟" - مزمور 27: 1</p>

        <button class="button" onclick="showMessage('message1')">انقر لتعرف المزيد</button>
        <p class="hidden-message" id="message1">أنتِ النعمة التي أعطاها الله لي، وأدعو المسيح أن يحفظك لي دائماً. أحبك بلا حدود.</p>

        <button class="button" onclick="showMessage('message2')">انقر لتعرف المزيد</button>
        <p class="hidden-message" id="message2">شكراً لكل الأوقات التي قضيناها معًا، وللحكم التي علمتني إياها. سأظل ممتنًا لكِ إلى الأبد. "أكرم أباك وأمك" - خروج 20: 12</p>

        <button class="button" onclick="showMessage('message3')">انقر لتعرف المزيد</button>
        <p class="hidden-message" id="message3">أنتِ القوة التي أستمد منها طاقتي كل يوم. حبك غير مشروط ودائم، وأنا ممتن لذلك. "المحبة تتأنى وترفق، المحبة لا تحسد، المحبة لا تتفاخر ولا تنتفخ." - 1 كورنثوس 13: 4</p>

        <h2>رسائل أخيرة</h2>
        <p>أمي الحبيبة، هذا الموقع لا يمكنه أن يعبر بشكل كامل عن مشاعري تجاهك. لكنني أتمنى أن يكون تعبيرًا صغيرًا عن امتناني وحبي العميقين لكِ. أنتِ أفضل أم في العالم، ولا يمكنني تخيل حياتي بدونك.</p>
    </div>

    <footer>
        &copy; 2024 إلى أمي الغالية - كل الحب والتقدير لكِ. "الرب يحفظك من كل شر؛ يحفظ نفسك." - مزمور 121: 7
    </footer>

    <script>
        function showMessage(messageId) {
            var message = document.getElementById(messageId);
            message.style.display = "block";
        }
    </script>
</body>
</html>
