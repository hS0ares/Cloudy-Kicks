<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salesforce Cloudy Kicks | Sneaker Store</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary: #1798c1;
            --secondary: #f1f1f1;
            --accent: #ff6b6b;
        }

        body {
            background-color: #f5f5f5;
        }

        .header {
            background-color: white;
            padding: 1rem 2rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: var(--primary);
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            align-items: center;
        }

        .nav-links a {
            color: #333;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        .login-btn {
            background-color: var(--primary);
            color: white;
            padding: 0.5rem 1.5rem;
            border-radius: 25px;
            cursor: pointer;
            border: none;
            transition: background-color 0.3s;
        }

        .login-btn:hover {
            background-color: #147a9c;
        }

        .hero {
            margin-top: 80px;
            height: 500px;
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/api/placeholder/1200/600');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }

        .hero-content h1 {
            font-size: 48px;
            margin-bottom: 1rem;
        }

        .hero-content p {
            font-size: 20px;
            margin-bottom: 2rem;
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            align-items: center;
            justify-content: center;
            z-index: 1001;
        }

        .modal-content {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            width: 90%;
            max-width: 400px;
        }

        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.5rem;
        }

        .close-btn {
            cursor: pointer;
            font-size: 24px;
            color: #666;
        }

        .form-group {
            margin-bottom: 1rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: #333;
        }

        .form-group input {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }

        .submit-btn {
            width: 100%;
            padding: 0.75rem;
            background-color: var(--primary);
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 1rem;
        }

        .products {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .product-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .product-info {
            padding: 1.5rem;
        }

        .user-welcome {
            color: var(--primary);
            font-weight: 500;
        }

        @media (max-width: 768px) {
            .nav {
                flex-direction: column;
                gap: 1rem;
            }

            .hero-content h1 {
                font-size: 36px;
            }

            .products-grid {
                grid-template-columns: 1fr;
            }
        }

        .hero {
            margin-top: 80px;
            height: 600px;
            position: relative;
            overflow: hidden;
        }

        .carousel {
            width: 100%;
            height: 100%;
            position: relative;
        }

        .carousel-inner {
            width: 100%;
            height: 100%;
            position: relative;
        }

        .carousel-slide {
            position: absolute;
            width: 100%;
            height: 100%;
            opacity: 0;
            transition: opacity 0.5s ease-in-out;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }

        .carousel-slide.active {
            opacity: 1;
        }

        .carousel-slide:nth-child(1) {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/api/placeholder/1200/600');
            background-size: cover;
            background-position: center;
        }

        .carousel-slide:nth-child(2) {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/api/placeholder/1200/600');
            background-size: cover;
            background-position: center;
        }

        .carousel-slide:nth-child(3) {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('/api/placeholder/1200/600');
            background-size: cover;
            background-position: center;
        }

        .carousel-content {
            max-width: 800px;
            padding: 2rem;
        }

        .carousel-content h1 {
            font-size: 48px;
            margin-bottom: 1rem;
        }

        .carousel-content p {
            font-size: 20px;
            margin-bottom: 2rem;
        }

        .carousel-controls {
            position: absolute;
            bottom: 2rem;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 1rem;
        }

        .carousel-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.5);
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .carousel-dot.active {
            background-color: white;
        }

        .carousel-arrow {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background-color: rgba(255, 255, 255, 0.3);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: background-color 0.3s;
            font-size: 24px;
            border: none;
        }

        .carousel-arrow:hover {
            background-color: rgba(255, 255, 255, 0.5);
        }

        .carousel-arrow.prev {
            left: 2rem;
        }

        .carousel-arrow.next {
            right: 2rem;
        }

        /* ... (restante dos estilos permanece igual) ... */
    </style>
</head>

<body>
    <header class="header">
        <nav class="nav">
            <div class="logo">Cloudy Kicks</div>
            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#sneakers">Sneakers</a>
                <a href="#releases">Lançamentos</a>
                <a href="#contato">Contato</a>
                <span class="user-welcome" id="userWelcome"></span>
                <button class="login-btn" id="loginBtn">Login</button>
            </div>
        </nav>
    </header>

    <div class="modal" id="loginModal">
        <div class="modal-content">
            <div class="modal-header">
                <h2>Login</h2>
                <span class="close-btn" id="closeModal">&times;</span>
            </div>
            <form id="loginForm">
                <div class="form-group">
                    <label for="username">Usuário:</label>
                    <input type="text" id="username" required>
                </div>
                <div class="form-group">
                    <label for="password">Senha:</label>
                    <input type="password" id="password" required>
                </div>
                <button type="submit" class="submit-btn">Entrar</button>
            </form>
        </div>
    </div>

    <section class="hero">
        <div class="carousel">
            <div class="carousel-inner">
                <div class="carousel-slide active">
                    <div class="carousel-content">
                        <h1>Bem-vindo à Cloudy Kicks</h1>
                        <p>Descubra os melhores sneakers para seu estilo</p>
                        <button class="login-btn">Explorar Coleção</button>
                    </div>
                </div>
                <div class="carousel-slide">
                    <div class="carousel-content">
                        <h1>Novos Lançamentos</h1>
                        <p>Conheça nossa nova coleção de verão</p>
                        <button class="login-btn">Ver Lançamentos</button>
                    </div>
                </div>
                <div class="carousel-slide">
                    <div class="carousel-content">
                        <h1>Ofertas Especiais</h1>
                        <p>Até 40% de desconto em produtos selecionados</p>
                        <button class="login-btn">Ver Ofertas</button>
                    </div>
                </div>
            </div>
            <button class="carousel-arrow prev">&lt;</button>
            <button class="carousel-arrow next">&gt;</button>
            <div class="carousel-controls">
                <div class="carousel-dot active"></div>
                <div class="carousel-dot"></div>
                <div class="carousel-dot"></div>
            </div>
        </div>
    </section>

    <section class="products">
        <h2>Destaques</h2>
        <div class="products-grid">
            <div class="product-card">
                <img src="/api/placeholder/300/200" alt="Sneaker 1" class="product-image">
                <div class="product-info">
                    <h3>Air Cloud Max</h3>
                    <p>R$ 899,99</p>
                </div>
            </div>
            <div class="product-card">
                <img src="/api/placeholder/300/200" alt="Sneaker 2" class="product-image">
                <div class="product-info">
                    <h3>Thunder Force</h3>
                    <p>R$ 799,99</p>
                </div>
            </div>
            <div class="product-card">
                <img src="/api/placeholder/300/200" alt="Sneaker 3" class="product-image">
                <div class="product-info">
                    <h3>Lightning Boost</h3>
                    <p>R$ 699,99</p>
                </div>
            </div>
        </div>
    </section>

    <script>
        // Elementos do DOM
        const loginBtn = document.getElementById('loginBtn');
        const loginModal = document.getElementById('loginModal');
        const closeModal = document.getElementById('closeModal');
        const loginForm = document.getElementById('loginForm');
        const userWelcome = document.getElementById('userWelcome');

        // Exibir modal de login
        loginBtn.addEventListener('click', () => {
            loginModal.style.display = 'flex';
        });

        // Fechar modal
        closeModal.addEventListener('click', () => {
            loginModal.style.display = 'none';
        });

        // Fechar modal ao clicar fora dele
        window.addEventListener('click', (e) => {
            if (e.target === loginModal) {
                loginModal.style.display = 'none';
            }
        });

        // Processar formulário de login
        loginForm.addEventListener('submit', (e) => {
            e.preventDefault();

            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;

            if (username && password) {
                // Salvar username na sessão
                sessionStorage.setItem('username', username);
                // Redirecionar para a página de pedidos
                window.location.href = 'orders-page.html';
            }
        });

        // Adicionar script do carrossel
        const slides = document.querySelectorAll('.carousel-slide');
        const dots = document.querySelectorAll('.carousel-dot');
        const prevBtn = document.querySelector('.carousel-arrow.prev');
        const nextBtn = document.querySelector('.carousel-arrow.next');
        let currentSlide = 0;

        function showSlide(index) {
            // Remover classe active de todos os slides e dots
            slides.forEach(slide => slide.classList.remove('active'));
            dots.forEach(dot => dot.classList.remove('active'));

            // Adicionar classe active ao slide e dot atual
            slides[index].classList.add('active');
            dots[index].classList.add('active');
        }

        function nextSlide() {
            currentSlide = (currentSlide + 1) % slides.length;
            showSlide(currentSlide);
        }

        function prevSlide() {
            currentSlide = (currentSlide - 1 + slides.length) % slides.length;
            showSlide(currentSlide);
        }

        // Event listeners para os botões de navegação
        nextBtn.addEventListener('click', nextSlide);
        prevBtn.addEventListener('click', prevSlide);

        // Event listeners para os dots
        dots.forEach((dot, index) => {
            dot.addEventListener('click', () => {
                currentSlide = index;
                showSlide(currentSlide);
            });
        });

        // Autoplay do carrossel
        setInterval(nextSlide, 5000);
    </script>
</body>

</html>