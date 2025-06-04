```html
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>顧問弁護士サービス [サイト名未定]</title>
    <meta name="description" content="中小企業・個人事業主様向けの24時間対応可能な顧問弁護士サービス。">
    <meta name="keywords" content="顧問弁護士, リーガルチェック, 24時間, 中小企業, 個人事業主, 法律相談">
    <style>
        /* CSS Reset */
        *,
        *::before,
        *::after {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* CSS Custom Properties (Color Palette) */
        :root {
            --primary-color: #0A2463; /* Deep Blue */
            --secondary-color: #3D3D3D; /* Dark Gray */
            --accent-color: #D4AF37; /* Gold-ish */
            --text-color: #333333;
            --text-color-light: #FFFFFF;
            --bg-color: #FFFFFF;
            --light-gray-bg: #f8f9fa;
            --header-height: 70px;
        }

        body {
            font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: 0 auto;
        }

        /* Header */
        header {
            background-color: var(--bg-color);
            border-bottom: 1px solid #e0e0e0;
            padding: 0 20px;
            height: var(--header-height);
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
        }

        .site-title {
            font-size: 1.8em;
            color: var(--primary-color);
            font-weight: bold;
            text-decoration: none;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 25px;
        }

        nav ul li a {
            text-decoration: none;
            color: var(--primary-color);
            font-weight: 500;
            transition: color 0.3s ease;
        }

        nav ul li a:hover,
        nav ul li a.active {
            color: var(--accent-color);
        }

        /* Hamburger Menu for Mobile */
        .hamburger-menu {
            display: none; /* Hidden on desktop */
            cursor: pointer;
            padding: 10px;
        }

        .hamburger-menu .bar {
            display: block;
            width: 25px;
            height: 3px;
            background-color: var(--primary-color);
            margin: 5px 0;
            transition: all 0.3s ease-in-out;
        }
        
        /* Main Content Placeholder Style to show scroll */
        main {
            padding-top: var(--header-height); /* Offset for fixed header */
        }

        section {
            padding: 80px 20px;
            min-height: 50vh; /* Placeholder height */
            border-bottom: 1px dashed #ccc;
        }
        section:nth-child(odd) {
            background-color: var(--light-gray-bg);
        }


        /* Footer Placeholder */
        footer {
            background-color: var(--secondary-color);
            color: var(--text-color-light);
            text-align: center;
            padding: 30px 20px;
        }

        /* Responsive (Mobile) */
        @media (max-width: 768px) {
            .site-title {
                font-size: 1.5em;
            }

            nav ul {
                display: none; /* Hide nav links */
                flex-direction: column;
                position: absolute;
                top: var(--header-height);
                left: 0;
                width: 100%;
                background-color: var(--bg-color);
                border-top: 1px solid #e0e0e0;
                padding: 10px 0;
            }

            nav ul.active {
                display: flex; /* Show when active */
            }

            nav ul li {
                margin: 10px 20px;
                text-align: center;
            }

            .hamburger-menu {
                display: block; /* Show hamburger */
            }
        }

    </style>
</head>
<body>
    <header>
        <div class="container">
            <a href="#" class="site-title">リーガルパートナー24</a>
            <div class="hamburger-menu">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
            <nav>
                <ul>
                    <li><a href="#hero">トップ</a></li>
                    <li><a href="#services">サービス概要</a></li>
                    <li><a href="#features">選ばれる理由</a></li>
                    <li><a href="#lawyers">弁護士紹介</a></li>
                    <li><a href="#legal-info">法令情報</a></li>
                    <li><a href="#contact">お問い合わせ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero">
            <div class="container">
                <h2>トップセクション (ヒーロー)</h2>
                <p>ここにキャッチコピーやメインビジュアルが入ります。</p>
            </div>
        </section>
        <section id="services">
            <div class="container">
                <h2>サービス概要</h2>
                <p>提供するサービスの詳細を説明します。</p>
            </div>
        </section>
        <section id="features">
            <div class="container">
                <h2>選ばれる理由</h2>
                <p>ユースケースや独自の強みを紹介します。</p>
            </div>
        </section>
        <section id="lawyers">
            <div class="container">
                <h2>弁護士紹介</h2>
                <p>所属弁護士の情報を掲載します。</p>
            </div>
        </section>
        <section id="legal-info">
            <div class="container">
                <h2>最新法令情報</h2>
                <p>関連法令のアップデートや解説を掲載します。</p>
            </div>
        </section>
        <section id="contact">
            <div class="container">
                <h2>お問い合わせ</h2>
                <p>24時間チャット受付のUIなどを配置します。</p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 リーガルパートナー24. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Smooth scroll for navigation links
            const navLinks = document.querySelectorAll('nav a[href^="#"]');
            navLinks.forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href');
                    const targetElement = document.querySelector(targetId);
                    if (targetElement) {
                        // Header height offset
                        const headerOffset = document.querySelector('header').offsetHeight;
                        const elementPosition = targetElement.getBoundingClientRect().top;
                        const offsetPosition = elementPosition + window.pageYOffset - headerOffset;
            
                        window.scrollTo({
                            top: offsetPosition,
                            behavior: 'smooth'
                        });
                        // Close mobile nav if open
                        if(document.querySelector('nav ul.active')){
                            document.querySelector('nav ul').classList.remove('active');
                            document.querySelector('.hamburger-menu').classList.remove('active');
                        }
                    }
                });
            });

            // Hamburger menu toggle
            const hamburger = document.querySelector('.hamburger-menu');
            const navUl = document.querySelector('nav ul');

            hamburger.addEventListener('click', function() {
                navUl.classList.toggle('active');
                this.classList.toggle('active'); // Optional: for styling the hamburger icon itself (e.g., transform to X)
                 // Change hamburger to X when active
                const bars = this.querySelectorAll('.bar');
                if (this.classList.contains('active')) {
                    bars[0].style.transform = 'rotate(-45deg) translate(-5px, 6px)';
                    bars[1].style.opacity = '0';
                    bars[2].style.transform = 'rotate(45deg) translate(-5px, -6px)';
                } else {
                    bars[0].style.transform = 'none';
                    bars[1].style.opacity = '1';
                    bars[2].style.transform = 'none';
                }
            });
            
            // Active link highlighting on scroll (simple version)
            const sections = document.querySelectorAll('main section');
            window.addEventListener('scroll', function() {
                let current = '';
                sections.forEach(section => {
                    const sectionTop = section.offsetTop - (document.querySelector('header').offsetHeight + 5); // 5px buffer
                    if (pageYOffset >= sectionTop) {
                        current = section.getAttribute('id');
                    }
                });

                navLinks.forEach(link => {
                    link.classList.remove('active');
                    if (link.getAttribute('href').includes(current)) {
                        link.classList.add('active');
                    }
                });
                // If at the top, activate "トップ"
                if (pageYOffset < sections[0].offsetTop - (document.querySelector('header').offsetHeight + 5) && current === '') {
                     navLinks.forEach(link => link.classList.remove('active'));
                     document.querySelector('nav a[href="#hero"]').classList.add('active');
                }
            });
             // Set initial active link for hero section if page loads at top
            if (window.pageYOffset < sections[0].offsetTop - (document.querySelector('header').offsetHeight + 5)) {
                document.querySelector('nav a[href="#hero"]').classList.add('active');
            }

        });
    </script>
</body>
</html>
