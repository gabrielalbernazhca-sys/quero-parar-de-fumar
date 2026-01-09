[index.html](https://github.com/user-attachments/files/24535902/index.html)
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description"
        content="Método 21 Dias – Como Parar de Fumar Sem Sofrer. Um guia passo a passo para reduzir a ansiedade e quebrar o hábito.">
    <title>Método 21 Dias – Como Parar de Fumar Sem Sofrer</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <style>
        /* Reset & Base Styles */
        :root {
            --primary-color: #2E8B57;
            /* SeaGreen - Calming, Health */
            --primary-hover: #27774A;
            --accent-color: #FFA500;
            /* Subtle urgency/warmth */
            --text-color: #e5e7eb;
            /* Light text for dark mode */
            --text-light: #9ca3af;
            --bg-light: #111827;
            /* Very dark gray (almost black) page background */
            --white: #1f2937;
            /* Dark gray for cards/sections */
            --white-text: #f3f4f6;
            /* Explicit light text variable */
            --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.3);
            --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.4), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
            --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.4), 0 4px 6px -2px rgba(0, 0, 0, 0.2);
            --font-main: 'Inter', sans-serif;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: var(--font-main);
            color: var(--text-color);
            background-color: var(--bg-light);
            line-height: 1.6;
            -webkit-font-smoothing: antialiased;
        }

        h1,
        h2,
        h3 {
            line-height: 1.2;
            font-weight: 700;
            color: var(--white-text);
        }

        p {
            margin-bottom: 1rem;
        }

        .container {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Typography & Utilities */
        .text-center {
            text-align: center;
        }

        /* Buttons */
        .btn-cta {
            display: inline-block;
            background-color: var(--primary-color);
            color: #ffffff;
            /* Always white text on button */
            padding: 18px 36px;
            font-size: 1.25rem;
            font-weight: 600;
            text-decoration: none;
            border-radius: 50px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 14px 0 rgba(46, 139, 87, 0.39);
            text-align: center;
            width: 100%;
            max-width: 400px;
            position: relative;
            z-index: 10;
        }

        .btn-cta:hover {
            background-color: var(--primary-hover);
            transform: translateY(-2px);
            box-shadow: 0 6px 20px 0 rgba(46, 139, 87, 0.23);
        }

        .pulse {
            animation: pulse-animation 2s infinite;
        }

        @keyframes pulse-animation {
            0% {
                box-shadow: 0 0 0 0 rgba(46, 139, 87, 0.4);
            }

            70% {
                box-shadow: 0 0 0 10px rgba(46, 139, 87, 0);
            }

            100% {
                box-shadow: 0 0 0 0 rgba(46, 139, 87, 0);
            }
        }

        /* Hero Section with Animated Background */
        .hero {
            padding: 100px 0 100px;
            background-color: var(--bg-light);
            /* Changed from #000 to match page bg */
            position: relative;
            overflow: hidden;
            color: #ffffff;
            text-align: center;
        }

        /* Pseudo-element for the background image to animate it */
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            /* Gradient adapted to Dark Gray (#111827) instead of pure black */
            background: linear-gradient(rgba(17, 24, 39, 0.7), rgba(17, 24, 39, 0.95)), url('bg_smoke.png') no-repeat center center/cover;
            background-size: 120%;
            z-index: 1;
            animation: pan-background 20s infinite alternate linear;
        }

        @keyframes pan-background {
            0% {
                background-position: 50% 50%;
            }

            100% {
                background-position: 50% 60%;
                transform: scale(1.1);
            }
        }

        .hero .container {
            position: relative;
            z-index: 2;
        }

        .hero .headline {
            color: #ffffff;
            text-shadow: 0 4px 6px rgba(0, 0, 0, 0.5);
            font-size: 2.5rem;
            /* Better mobile default */
            margin-bottom: 1.5rem;
            letter-spacing: -0.02em;
            font-weight: 700;
        }

        .hero .subheadline {
            color: #e5e7eb;
            font-size: 1.15rem;
            /* Better mobile default */
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
            margin-bottom: 2.5rem;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }

        @media (min-width: 768px) {
            .hero .headline {
                font-size: 2.8rem;
            }

            .hero .subheadline {
                font-size: 1.3rem;
            }
        }

        /* Identification Section */
        .identification {
            padding: 60px 0;
            background-color: var(--white);
        }

        .identification h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
        }

        .id-grid-vertical {
            display: flex;
            flex-direction: column;
            gap: 20px;
            margin-top: 20px;
        }

        .id-item-row {
            display: flex;
            align-items: flex-start;
            gap: 15px;
            background: var(--bg-light);
            padding: 15px;
            border-radius: 10px;
        }

        .id-item-row .icon {
            font-size: 1.8rem;
            line-height: 1;
        }

        .id-item-row p {
            margin: 0;
            font-size: 1rem;
            text-align: left;
        }

        /* Method Explanation */
        .method-explanation {
            padding: 60px 0;
            background-color: #161e2e;
            /* Slightly different dark gray/green */
            text-align: center;
        }

        .method-explanation .lead {
            font-size: 1.2rem;
            color: var(--primary-color);
            font-weight: 600;
            margin-bottom: 40px;
        }

        .method-features {
            display: grid;
            gap: 30px;
            grid-template-columns: 1fr;
            /* Mobile default */
        }

        @media (min-width: 768px) {
            .method-features {
                grid-template-columns: repeat(3, 1fr);
            }
        }

        .feature {
            background: var(--white);
            padding: 30px;
            border-radius: 16px;
            box-shadow: var(--shadow-sm);
            transition: transform 0.2s;
        }

        .feature:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-md);
        }

        .feature h3 {
            margin-bottom: 12px;
            color: var(--white-text);
        }

        /* Benefits */
        .benefits {
            padding: 60px 0;
            background-color: var(--white);
        }

        .benefits h2 {
            text-align: center;
            margin-bottom: 40px;
        }

        .benefits-list {
            list-style: none;
            max-width: 600px;
            margin: 0 auto;
        }

        .benefits-list li {
            font-size: 1.15rem;
            margin-bottom: 16px;
            padding-left: 32px;
            position: relative;
            color: var(--text-color);
        }

        .benefits-list li span {
            position: absolute;
            left: 0;
            top: 2px;
        }

        /* Target Audience */
        .target-audience {
            padding: 60px 0;
            background: var(--bg-light);
        }

        .audience-grid {
            display: grid;
            gap: 30px;
            max-width: 900px;
            margin: 0 auto;
            grid-template-columns: 1fr;
            /* Mobile default */
        }

        @media (min-width: 768px) {
            .audience-grid {
                grid-template-columns: 1fr 1fr;
            }
        }

        .audience-card {
            padding: 40px;
            border-radius: 16px;
            color: #ffffff;
            /* Force white text on colored cards */
        }

        .audience-card h3 {
            color: #ffffff;
            margin-bottom: 16px;
            font-size: 1.4rem;
        }

        .audience-card.yes {
            background: linear-gradient(145deg, #10b981 0%, #059669 100%);
        }

        .audience-card.no {
            background: linear-gradient(145deg, #ef4444 0%, #dc2626 100%);
        }

        /* Social Proof */
        .social-proof {
            padding: 40px 0;
            background-color: var(--white);
            text-align: center;
            border-top: 1px solid #374151;
            border-bottom: 1px solid #374151;
        }

        .proof-text {
            font-style: italic;
            font-size: 1.1rem;
            color: var(--text-color);
            max-width: 600px;
            margin: 0 auto 10px;
        }

        .proof-sub {
            font-size: 0.9rem;
            color: var(--text-light);
            font-weight: 500;
        }

        /* Offer Section */
        .offer {
            padding: 80px 0;
            background: linear-gradient(180deg, #111827 0%, #1f2937 100%);
            text-align: center;
        }

        .offer-card {
            background: var(--white);
            padding: 50px 30px;
            border-radius: 24px;
            box-shadow: var(--shadow-lg);
            max-width: 500px;
            margin: 0 auto;
            border: 1px solid rgba(255, 255, 255, 0.05);
            position: relative;
            overflow: hidden;
        }

        .offer-tag {
            background: var(--accent-color);
            color: #ffffff;
            display: inline-block;
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 20px;
        }

        .price {
            margin-bottom: 30px;
            color: #ffffff;
            /* Force white for price */
        }

        .currency {
            font-size: 1.5rem;
            vertical-align: top;
            font-weight: 600;
        }

        .amount {
            font-size: 4rem;
            font-weight: 800;
            line-height: 1;
            color: var(--primary-color);
        }

        .payment-type {
            display: block;
            color: var(--text-light);
            font-size: 0.9rem;
            margin-top: 5px;
        }

        .offer-features {
            list-style: none;
            margin-bottom: 30px;
            text-align: left;
            display: inline-block;
        }

        .offer-features li {
            margin-bottom: 10px;
            font-size: 1rem;
            color: var(--text-color);
            display: flex;
            align-items: center;
        }

        .offer-features li::before {
            content: "✔️";
            margin-right: 10px;
            color: var(--primary-color);
            font-size: 0.8rem;
        }

        .security-badges {
            margin-top: 30px;
            display: flex;
            flex-direction: column;
            gap: 8px;
            font-size: 0.85rem;
            color: var(--text-light);
        }

        /* Footer */
        footer {
            padding: 40px 0;
            background-color: #111827;
            text-align: center;
            color: var(--text-light);
            font-size: 0.85rem;
            border-top: 1px solid #374151;
        }

        .disclaimer {
            margin-top: 20px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.5;
        }

        /* Updated Split Layout & Image Styles */
        /* Flexbox for Mobile First - Default is Column */
        .split-layout {
            display: flex;
            flex-direction: column;
            gap: 40px;
            align-items: center;
        }

        @media (min-width: 768px) {
            .split-layout {
                flex-direction: row;
                align-items: center;
                text-align: left;
            }

            .split-layout.reverse {
                flex-direction: row-reverse;
            }

            .split-layout .image-box,
            .split-layout .content-box {
                flex: 1;
                width: 100%;
            }

            .identification h2,
            .benefits h2 {
                text-align: left;
            }
        }

        .responsive-img {
            width: 100%;
            height: auto;
            display: block;
            object-fit: cover;
        }

        .shadow-img {
            box-shadow: var(--shadow-lg);
        }

        .rounded {
            border-radius: 20px;
        }

        .image-box img {
            border-radius: 16px;
            transition: transform 0.3s ease;
        }

        .image-box img:hover {
            transform: scale(1.02);
        }

        .section-lead {
            font-size: 1.1rem;
            color: var(--text-light);
            margin-bottom: 2rem;
        }
    </style>
</head>

<body>

    <!-- Hero Section -->
    <header class="hero">
        <div class="container">
            <div style="max-width: 800px; margin: 0 auto; text-align: center;">
                <h1 class="headline">Você não fuma porque quer — o cigarro virou um hábito emocional</h1>
                <p class="subheadline">Um método simples de 21 dias para reduzir a ansiedade e quebrar o hábito do
                    cigarro, sem remédios e sem sofrimento.</p>
                <a href="https://pay.kiwify.com.br/4izXghX" class="btn-cta pulse">Quero parar de fumar</a>
            </div>
        </div>
    </header>

    <!-- Identificação (Empatia) -->
    <section class="identification">
        <div class="container">
            <div class="split-layout">
                <div class="image-box">
                    <img src="relief_woman.jpg" alt="Mulher respirando ar puro na natureza"
                        class="responsive-img shadow-img rounded">
                </div>
                <div class="content-box">
                    <h2>Você se identifica com isso?</h2>
                    <div class="id-grid-vertical">
                        <div class="id-item-row">
                            <div class="icon">😔</div>
                            <p><strong>Ciclo da Frustração:</strong> Você promete que vai parar, mas a ansiedade bate e
                                você recai.</p>
                        </div>
                        <div class="id-item-row">
                            <div class="icon">😰</div>
                            <p><strong>Hábito Automático:</strong> Acender o cigarro já virou um reflexo, você nem
                                percebe quando faz.</p>
                        </div>
                        <div class="id-item-row">
                            <div class="icon">💔</div>
                            <p><strong>Medo de Falhar:</strong> O medo de tentar e não conseguir te paralisa.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- O que é o Método -->
    <section class="method-explanation">
        <div class="container">
            <h2>O que é o Método 21 Dias?</h2>
            <p class="lead">Não é mágica. É um processo passo a passo.</p>
            <div class="method-features">
                <div class="feature">
                    <h3>📅 Passo a passo diário</h3>
                    <p>Orientações simples para aplicar um dia de cada vez.</p>
                </div>
                <div class="feature">
                    <h3>🧠 Mentalidade e Comportamento</h3>
                    <p>Exercícios focados em reprogramar o hábito e reduzir a ansiedade.</p>
                </div>
                <div class="feature">
                    <h3>📱 100% Digital</h3>
                    <p>Acesse pelo celular ou computador, no seu tempo.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefícios -->
    <section class="benefits">
        <div class="container">
            <div class="split-layout reverse">
                <div class="image-box">
                    <img src="family_happiness.png" alt="Família feliz e saudável no parque"
                        class="responsive-img shadow-img rounded">
                </div>
                <div class="content-box">
                    <h2>Recupere sua liberdade e viva mais pela sua família</h2>
                    <p class="section-lead">Imagine ter fôlego para brincar com seus filhos e netos, sem ser escravo do
                        vício.</p>
                    <ul class="benefits-list">
                        <li><span>✅</span> Reduz a ansiedade naturalmente</li>
                        <li><span>✅</span> Quebra o hábito automático do cigarro</li>
                        <li><span>✅</span> Melhora sua saúde e disposição</li>
                        <li><span>✅</span> Sem remédios caros ou efeitos colaterais</li>
                        <li><span>✅</span> Método 100% online e discreto</li>
                    </ul>
                </div>
            </div>

            <!-- Middle CTA -->
            <div class="text-center" style="margin-top: 40px;">
                <a href="https://pay.kiwify.com.br/4izXghX" class="btn-cta">Quero parar de fumar</a>
            </div>
        </div>
    </section>

    <!-- Para quem é / Não é -->
    <section class="target-audience">
        <div class="container">
            <div class="audience-grid">
                <div class="audience-card yes">
                    <h3>Para quem é ✔️</h3>
                    <p>Para homens e mulheres que decidiram que querem parar de fumar e buscam um caminho guiado e
                        emocionalmente inteligente.</p>
                </div>
                <div class="audience-card no">
                    <h3>Para quem não é ❌</h3>
                    <p>Para quem busca uma pílula mágica, uma solução milagrosa instantânea ou não está disposto a fazer
                        pequenas mudanças diárias.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Prova Inicial -->
    <section class="social-proof">
        <div class="container">
            <p class="proof-text">"Pessoas comuns já começaram o método hoje e estão dando o primeiro passo para a
                liberdade."</p>
            <p class="proof-sub">Método simples, direto e com linguagem humana.</p>
        </div>
    </section>

    <!-- Oferta e Preço -->
    <section class="offer">
        <div class="container">
            <div class="offer-card">
                <p class="offer-tag">Oferta Especial</p>
                <div class="price">
                    <span class="currency">R$</span>
                    <span class="amount">27</span>
                    <span class="payment-type">pagamento único</span>
                </div>

                <ul class="offer-features">
                    <li>🔒 Pagamento Seguro</li>
                    <li>⚡ Acesso Imediato</li>
                    <li>📖 Conteúdo Digital Completo</li>
                </ul>

                <a href="https://pay.kiwify.com.br/4izXghX" class="btn-cta pulse">Quero parar de fumar</a>

                <div class="security-badges">
                    <span>🔒 Compra 100% Segura</span>
                    <span>🛡️ Garantia de Satisfação</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Método 21 Dias. Todos os direitos reservados.</p>
            <p class="disclaimer">Este produto não substitui o parecer médico profissional. Se você tem problemas de
                saúde graves, consulte um médico. Os resultados podem variar de pessoa para pessoa.</p>
        </div>
    </footer>

</body>

</html>
