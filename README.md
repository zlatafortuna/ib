<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фінансове планування для стартапів</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
        .hero-bg {
            background: linear-gradient(to right, #1e3a8a, #3b82f6);
        }
    </style>
</head>
<body class="bg-gray-100">
    <!-- Header -->
    <header class="bg-white shadow">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-blue-900">Злата Фортуна</div>
            <div class="space-x-4">
                <a href="#home" class="text-blue-600 hover:text-blue-800">Головна</a>
                <a href="#tips" class="text-blue-600 hover:text-blue-800">Поради</a>
                <a href="#contact" class="text-blue-600 hover:text-blue-800">Контакти</a>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-bg text-white py-20">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Фінансове планування для стартапів</h1>
            <p class="text-lg md:text-xl mb-6">25.04.2025 | Експерти Злата Фортуна</p>
            <p class="text-base md:text-lg max-w-2xl mx-auto">Дізнайтесь, як ефективно управляти фінансами вашого стартапу з нашими професійними порадами.</p>
            <a href="#tips" class="mt-6 inline-block bg-white text-blue-600 font-semibold py-3 px-6 rounded-lg hover:bg-blue-100 transition">Читати поради</a>
        </div>
    </section>

    <!-- Tips Section -->
    <section id="tips" class="py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-blue-900 mb-12">Поради щодо фінансового планування</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold text-blue-900 mb-4">1. Складіть реалістичний бюджет</h3>
                    <p class="text-gray-600">Аналізуйте витрати та доходи, щоб створити бюджет, який враховує всі аспекти вашого стартапу.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold text-blue-900 mb-4">2. Плануйте грошовий потік</h3>
                    <p class="text-gray-600">Регулярно відстежуйте вхідні та вихідні кошти, щоб уникнути касових розривів.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold text-blue-900 mb-4">3. Залучайте інвестиції розумно</h3>
                    <p class="text-gray-600">Оцінюйте інвесторів не лише за розміром капіталу, а й за їх досвідом та мережею контактів.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold text-blue-900 mb-4">4. Використовуйте фінансові інструменти</h3>
                    <p class="text-gray-600">Автоматизуйте облік за допомогою сучасних інструментів, таких як QuickBooks чи Xero.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold text-blue-900 mb-4">5. Прогнозуйте на довгострокову перспективу</h3>
                    <p class="text-gray-600">Створюйте фінансові прогнози на 3-5 років, щоб бути готовими до змін на ринку.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
                    <h3 class="text-xl font-semibold text-blue-900 mb-4">6. Контролюйте витрати</h3>
                    <p class="text-gray-600">Регулярно переглядайте витрати та оптимізуйте їх, щоб підвищити ефективність.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-blue-900 text-white py-16">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-6">Зв’яжіться з нами</h2>
            <p class="text-lg mb-8 max-w-xl mx-auto">Маєте питання чи потребуєте консультації? Наші експерти готові допомогти вашому стартапу досягти успіху.</p>
            <a href="mailto:threecupsoftea@zlatafortuna.com" class="inline-block bg-white text-blue-900 font-semibold py-3 px-6 rounded-lg hover:bg-gray-200 transition">Написати нам</a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2025 Злата Фортуна. Усі права захищені.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
