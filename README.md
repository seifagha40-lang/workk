<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>صفحة سيارات</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Tahoma;
            background-color: #5e073f;
        }

        /* الشريط العلوي */
        .top-bar {
            background-color: #222;
            padding: 10px;
            display: flex;
            justify-content: flex-end;
            gap: 10px;
        }

        .top-bar input {
            width: 140px;
            padding: 6px;
            border-radius: 4px;
            border: none;
            font-size: 13px;
        }

        .top-bar button {
            padding: 6px 10px;
            border: none;
            border-radius: 4px;
            background-color: #ff9800;
            color: #000;
            font-size: 13px;
            cursor: pointer;
        }

        .top-bar button:hover {
            background-color: #e68900;
        }

        /* محتوى الصفحة */
        .content {
            max-width: 900px;
            margin: 80px auto;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            line-height: 1.9;
        }

        .content h1 {
            text-align: center;
            color: #333;
        }

        .content p {
            font-size: 17px;
            color: #444;
        }
    </style>
</head>
<body>

    <!-- الشريط العلوي -->
    <div class="top-bar">
        <!-- تسجيل دخول -->
        <input type="email" placeholder="البريد الإلكتروني">
        <input type="password" placeholder="كلمة المرور">
        <button>تسجيل دخول</button>

        <!-- تسجيل جديد -->
        <input type="text" placeholder="اسم المستخدم">
        <input type="password" placeholder="كلمة مرور جديدة">
        <button>تسجيل جديد</button>

        <!-- تغيير كلمة المرور -->
        <input type="password" placeholder="كلمة المرور القديمة">
        <input type="password" placeholder="كلمة المرور الجديدة">
        <button>تغيير</button>
    </div>

    <!-- المحتوى -->
    <div class="content">
        <h1>عالم السيارات</h1>

        <p>
            السيارات هي واحدة من أهم وسائل النقل في العصر الحديث، وتعتمد بشكل أساسي
            على مجموعة من المكونات الميكانيكية والكهربائية التي تعمل معًا بانسجام
            لتوفير أداء قوي وآمن.
        </p>

        <p>
            يتكون هيكل السيارة من الشاسيه، المحرك، نظام نقل الحركة، نظام التعليق،
            المكابح، والعجلات. ويُعد المحرك هو قلب السيارة، حيث يقوم بتحويل الطاقة
            الناتجة من الوقود أو الكهرباء إلى حركة ميكانيكية.
        </p>

        <p>
            تمر صناعة السيارات بعدة مراحل تبدأ من التصميم الهندسي، ثم تصنيع الأجزاء،
            وبعدها التجميع داخل المصانع باستخدام تقنيات حديثة وروبوتات دقيقة لضمان
            أعلى مستويات الجودة والأمان.
        </p>

        <p>
            ومع التطور التكنولوجي، أصبحت السيارات أكثر ذكاءً من خلال أنظمة الأمان،
            التحكم الإلكتروني، والمحركات الكهربائية التي تساعد في تقليل استهلاك
            الوقود والحفاظ على البيئة.
        </p>
    </div>

</body>
</html>
