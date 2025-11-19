<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Элитный частный дом | Продажа</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#1a365d',
                        secondary: '#2c5282',
                        accent: '#e53e3e',
                        light: '#f8fafc'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif']
                    }
                }
            }
        }
    </script>
    <style>
        .fade-in { opacity: 0; animation: fadeIn 1s forwards; }
        @keyframes fadeIn {
            to { opacity: 1; }
        }
        .feature-card:hover { transform: translateY(-5px); transition: transform 0.3s ease; }
        .gallery-img { transition: transform 0.5s ease; }
        .gallery-img:hover { transform: scale(1.03); }
    </style>
</head>
<body class="bg-gray-50 font-sans text-gray-800 overflow-x-hidden">
    <!-- Hero Section -->
    <section class="relative bg-gray-900">
        <div class="absolute inset-0 bg-gradient-to-r from-black/70 to-transparent z-10"></div>
        <img src="https://i.imgur.com/3VYkqQO.jpg" alt="Вид на дом с воздуха" class="w-full h-[85vh] object-cover">
        <div class="absolute inset-0 z-20 flex flex-col justify-center items-start pl-8 md:pl-16">
            <h1 class="text-4xl md:text-6xl font-serif font-bold text-white mb-4 fade-in" style="animation-delay: 0.2s">Элитный частный дом</h1>
            <p class="text-xl md:text-2xl text-gray-200 mb-6 fade-in" style="animation-delay: 0.4s">Современный дизайн в престижном районе</p>
            <div class="bg-white/90 backdrop-blur-sm p-4 rounded-lg shadow-xl fade-in" style="animation-delay: 0.6s">
                <div class="flex flex-wrap gap-6">
                    <div class="text-center">
                        <div class="text-3xl font-bold text-primary">30 млн ₽</div>
                        <div class="text-sm text-gray-600">Цена</div>
                    </div>
                    <div class="text-center">
                        <div class="text-2xl font-bold text-primary">258 м²</div>
                        <div class="text-sm text-gray-600">Площадь дома</div>
                    </div>
                    <div class="text-center">
                        <div class="text-2xl font-bold text-primary">1162 м²</div>
                        <div class="text-sm text-gray-600">Площадь участка</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Info Section -->
    <section class="py-16 px-4 md:px-8 bg-white">
        <div class="max-w-6xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl md:text-4xl font-serif font-bold mb-6 text-primary">Современный дом для ценителей стиля</h2>
                    <p class="text-lg mb-6 text-gray-700 leading-relaxed">
                        Представляем уникальную возможность приобрести роскошный частный дом с современным архитектурным дизайном, расположенный в экологически чистом районе. Этот дом сочетает в себе элегантность, функциональность и высокое качество исполнения.
                    </p>
                    <p class="text-lg mb-8 text-gray-700 leading-relaxed">
                        Просторные светлые помещения, панорамные окна, уютная терраса и продуманная планировка создают идеальную атмосферу для жизни и отдыха. Участок полностью благоустроен с ландшафтным дизайном от ведущих специалистов.
                    </p>
                    <a href="#contact" class="inline-block bg-accent hover:bg-red-700 text-white font-semibold py-3 px-8 rounded-lg transition duration-300 transform hover:scale-105 shadow-lg">Записаться на просмотр</a>
                </div>
                <div class="grid grid-cols-2 gap-4">
                    <img src="https://i.imgur.com/3VYkqQO.jpg" alt="Фасад дома" class="rounded-lg shadow-md gallery-img">
                    <img src="https://i.imgur.com/7RgZvzJ.jpg" alt="Гостиная" class="rounded-lg shadow-md gallery-img mt-8">
                    <img src="https://i.imgur.com/1oCmWxH.jpg" alt="Кухня" class="rounded-lg shadow-md gallery-img">
                    <img src="https://i.imgur.com/5jKXZyI.jpg" alt="Спальня" class="rounded-lg shadow-md gallery-img mt-8">
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 px-4 md:px-8 bg-gray-50">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-serif font-bold text-center mb-12 text-primary">Преимущества дома</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-md feature-card">
                    <div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 text-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Премиальное расположение</h3>
                    <p class="text-gray-600">Экологически чистый район, развитая инфраструктура, 20 минут до центра города.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-md feature-card">
                    <div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 text-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Продуманная планировка</h3>
                    <p class="text-gray-600">5 спален, 4 санузла, просторная гостиная, кухня-столовая, кабинет, кинозал.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-md feature-card">
                    <div class="w-14 h-14 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 text-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Благоустроенный участок</h3>
                    <p class="text-gray-600">Ландшафтный дизайн, зона барбекю, бассейн, гараж на 2 машины, система автоматического полива.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="py-16 px-4 md:px-8 bg-white">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-serif font-bold text-center mb-12 text-primary">Фотогалерея</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="aspect-video overflow-hidden rounded-xl">
                    <img src="https://i.imgur.com/3VYkqQO.jpg" alt="Вид на участок" class="w-full h-full object-cover gallery-img">
                </div>
                <div class="aspect-video overflow-hidden rounded-xl">
                    <img src="https://i.imgur.com/7RgZvzJ.jpg" alt="Терраса" class="w-full h-full object-cover gallery-img">
                </div>
                <div class="aspect-video overflow-hidden rounded-xl">
                    <img src="https://i.imgur.com/1oCmWxH.jpg" alt="Каминная зона" class="w-full h-full object-cover gallery-img">
                </div>
                <div class="aspect-video overflow-hidden rounded-xl">
                    <img src="https://i.imgur.com/5jKXZyI.jpg" alt="Ванная комната" class="w-full h-full object-cover gallery-img">
                </div>
                <div class="aspect-video overflow-hidden rounded-xl">
                    <img src="https://i.imgur.com/3VYkqQO.jpg" alt="Кабинет" class="w-full h-full object-cover gallery-img">
                </div>
                <div class="aspect-video overflow-hidden rounded-xl">
                    <img src="https://i.imgur.com/7RgZvzJ.jpg" alt="Вид из окна" class="w-full h-full object-cover gallery-img">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 px-4 md:px-8 bg-gradient-to-r from-primary to-secondary">
        <div class="max-w-4xl mx-auto">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden">
                <div class="md:flex">
                    <div class="md:w-2/5 bg-gray-900 p-8 text-white">
                        <h2 class="text-2xl font-serif font-bold mb-6">Свяжитесь с нами</h2>
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-accent mt-1 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                                </svg>
                                <div>
                                    <div class="font-semibold">Телефон</div>
                                    <div>+7 (999) 123-45-67</div>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-accent mt-1 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                                </svg>
                                <div>
                                    <div class="font-semibold">Email</div>
                                    <div>info@luxhome.ru</div>
                                </div>
                            </div>
                            <div class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-accent mt-1 mr-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                                </svg>
                                <div>
                                    <div class="font-semibold">Адрес</div>
                                    <div>Московская область, Рублёвское шоссе</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="md:w-3/5 p-8">
                        <h3 class="text-2xl font-serif font-bold text-primary mb-6">Записаться на просмотр</h3>
                        <form class="space-y-4">
                            <div>
                                <label class="block text-gray-700 mb-2">Ваше имя</label>
                                <input type="text" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Иван Иванов">
                            </div>
                            <div>
                                <label class="block text-gray-700 mb-2">Телефон</label>
                                <input type="tel" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="+7 (999) 123-45-67">
                            </div>
                            <div>
                                <label class="block text-gray-700 mb-2">Удобное время</label>
                                <input type="text" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Например: завтра после 15:00">
                            </div>
                            <button type="submit" class="w-full bg-accent hover:bg-red-700 text-white font-semibold py-3 px-4 rounded-lg transition duration-300 transform hover:scale-105 shadow-lg">
                                Отправить заявку
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8 px-4">
        <div class="max-w-6xl mx-auto text-center">
            <p class="mb-2">© 2025 Элитная недвижимость. Все права защищены.</p>
            <p class="text-gray-400 text-sm">Любая информация, представленная на данном сайте, носит исключительно информационный характер и ни при каких условиях не является публичной офертой.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Simple form submission handling
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Спасибо за заявку! Мы свяжемся с вами в ближайшее время.');
            this.reset();
        });
    </script>
</body>
</html>

