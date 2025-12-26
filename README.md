<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chanfainita Con fruta y refresco bajo en azúcar | Receta Premium</title>
    
    <!-- Google Fonts para una tipografía moderna -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@400;600&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
    
    <!-- Font Awesome para iconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        /* --- ESTILOS GENERALES Y FONDO --- */
        :root {
            --bg-color: #121212;
            --surface-color: #1e1e1e;
            --primary-text: #f0f0f0;
            --secondary-text: #a0a0a0;
            --accent-color: #f0c808; /* Dorado/Amarillo premium */
            --accent-color-glow: rgba(240, 200, 8, 0.5);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: var(--bg-color);
            color: var(--primary-text);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* --- SECCIÓN HERO CON LA IMAGEN --- */
        .hero-section {
            position: relative;
            width: 100%;
            height: 70vh;
            background-image: url('https://z-cdn-media.chatglm.cn/files/c9eb0eac-eacf-43c1-a6b3-db9f984a27f3_pasted_image_1763925225573.png?auth_key=1863925236-efbdcc62829945f0923eec6be946db41-0-4050c5d766a11a8385fef96649135675');
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .hero-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to top, rgba(18, 18, 18, 0.9) 0%, rgba(18, 18, 18, 0.4) 50%, rgba(18, 18, 18, 0.1) 100%);
        }

        .hero-content {
            position: relative;
            z-index: 1;
            padding: 20px;
            animation: fadeIn 1.5s ease-in-out;
        }

        .hero-title {
            font-family: 'Bebas Neue', cursive;
            font-size: 4rem;
            font-weight: 400;
            color: #ffffff;
            text-shadow: 0 0 20px rgba(0, 0, 0, 0.7);
            letter-spacing: 2px;
            margin-bottom: 10px;
        }

        .hero-subtitle {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.2rem;
            font-weight: 400;
            color: var(--primary-text);
            text-transform: uppercase;
            letter-spacing: 5px;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.8);
        }

        /* --- SECCIÓN DE CONTENIDO (INGREDIENTES) --- */
        .content-section {
            max-width: 900px;
            margin: -50px auto 0;
            padding: 40px 60px;
            background-color: var(--surface-color);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            position: relative;
            z-index: 2;
            animation: slideUp 1s ease-out 0.5s both;
        }

        .section-title {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.5rem;
            font-weight: 600;
            color: var(--primary-text);
            margin-bottom: 40px;
            text-align: center;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background-color: var(--accent-color);
            margin: 10px auto 0;
            border-radius: 2px;
        }

        /* --- LISTA DE INGREDIENTES ESTILIZADA --- */
        .ingredients-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            list-style-type: none;
        }

        .ingredient-card {
            background-color: var(--bg-color);
            border-radius: 12px;
            padding: 20px;
            display: flex;
            align-items: center;
            border-left: 4px solid var(--accent-color);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .ingredient-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }

        .ingredient-card i {
            font-size: 1.5rem;
            color: var(--accent-color);
            margin-right: 20px;
            min-width: 30px;
            text-align: center;
        }

        .ingredient-text {
            font-size: 1rem;
            font-weight: 300;
            color: var(--primary-text);
        }
        
        /* --- ANIMACIONES --- */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* --- RESPONSIVE DESIGN --- */
        @media (max-width:768px) {
            .hero-title {
                font-size: 2.5rem;
            }
            .content-section {
                padding: 30px 25px;
                margin-top: -30px;
            }
            .section-title {
                font-size: 2rem;
            }
            .ingredients-grid {
                grid-template-columns: 1fr;
            }
        }

    </style>
</head>
<body>

    <!-- SECCIÓN PRINCIPAL CON IMAGEN Y TÍTULO -->
    <section class="hero-section">
        <div class="hero-content">
            <h1 class="hero-title">Chanfainita Con fruta y refresco bajo en azúcar</h1>
            <p class="hero-subtitle">Un plato tradicional reconfortante</p>
        </div>
    </section>

    <!-- SECCIÓN DE INGREDIENTES -->
    <main class="content-section">
        <h2 class="section-title">Ingredientes para 4 porciones</h2>
        <ul class="ingredients-grid">
            <li class="ingredient-card">
                <i class="fas fa-bowl-rice"></i>
                <span class="ingredient-text">1 1/2 taza de arroz</span>
            </li>
            <li class="ingredient-card">
                <i class="fas fa-drumstick-bite"></i>
                <span class="ingredient-text">1/2 kg de bofe de res</span>
            </li>
            <li class="ingredient-card">
                <i class="fas fa-circle-notch"></i>
                <span class="ingredient-text">1/2 kg de papa blanca</span>
            </li>
            <!-- ÍCONO CAMBIADO A 'fa-wheat-awn' PARA GARANTIZAR QUE SE VEA -->
            <li class="ingredient-card">
                <i class="fas fa-wheat-awn"></i>
                <span class="ingredient-text">1/4 kg de maíz mote</span>
            </li>
            <li class="ingredient-card">
                <i class="fas fa-circle-notch"></i>
                <span class="ingredient-text">1 cebolla mediana</span>
            </li>
            <li class="ingredient-card">
                <i class="fas fa-apple-alt"></i>
                <span class="ingredient-text">2 tomates medianos</span>
            </li>
            <li class="ingredient-card">
                <i class="fas fa-leaf"></i>
                <span class="ingredient-text">8 hojas de lechuga</span>
            </li>
            <li class="ingredient-card">
                <i class="fas fa-oil-can"></i>
                <span class="ingredient-text">4 cucharadas de aceite vegetal</span>
            </li>
            <li class="ingredient-card">
                <i class="fas fa-mortar-pestle"></i>
                <span class="ingredient-text">Hierba buena, ají colorado molido, ají amarillo molido, ajo molido, sal yodada, comino, pimienta, orégano</span>
            </li>
        </ul>
    </main>

</body>
</html>
