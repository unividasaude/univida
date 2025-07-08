<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UniVida Saúde - Home Care</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #d8ebe9;
            color: #00333a;
            background-image: url('636138ac-960c-48b9-ad2c-37d9aafe989a.png');
            background-size: contain;
            background-repeat: no-repeat;
            background-position: bottom right;
        }

        header {
            background-color: #ffffff;
            padding: 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .top-bar {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 20px 40px;
            background-color: #e3f4f1;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            height: 50px;
            margin-right: 10px;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #00333a;
            font-weight: 600;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #f0a400;
        }

        .hero {
            background: linear-gradient(135deg, #f3fbfa 60%, #f0a4001f 100%);
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            padding: 80px 40px 60px;
        }

        .hero-text {
            flex: 1 1 400px;
            padding: 20px;
        }

        .hero h1 {
            font-size: 42px;
            color: #00333a;
            margin-bottom: 20px;
        }

        .hero h1 strong {
            color: #f0a400;
        }

        .hero p {
            font-size: 20px;
            font-family: 'Georgia', serif;
            color: #f0a400;
        }

        .hero-image {
            flex: 1 1 300px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .hero-image img {
            max-width: 300px;
            height: auto;
        }

        .section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }

        .section h2 {
            color: #00333a;
            margin-bottom: 30px;
            text-align: center;
        }

        .services-list {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .service-box {
            background-color: #ffffff;
            border-left: 5px solid #f0a400;
            padding: 30px 20px;
            border-radius: 12px;
            width: 250px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .service-box:hover {
            transform: translateY(-5px);
        }

        .service-box h3 {
            margin-top: 0;
            color: #00333a;
        }

        .service-enfermeiro::before {
            content: '\1F489';
            font-size: 24px;
            display: block;
            margin-bottom: 10px;
        }

        .service-tecnico::before {
            content: '\1F48A';
            font-size: 24px;
            display: block;
            margin-bottom: 10px;
        }

        .service-fisio::before {
            content: '\1F493';
            font-size: 24px;
            display: block;
            margin-bottom: 10px;
        }

        .service-multi::before {
            content: '\1FA7A';
            font-size: 24px;
            display: block;
            margin-bottom: 10px;
        }

        .contact, .trabalhe {
            background-color: #ffffff;
            padding: 60px 20px;
            text-align: center;
            border-radius: 10px;
            max-width: 900px;
            margin: 40px auto;
        }

        .contact a, .trabalhe a {
            color: #f0a400;
            font-weight: bold;
        }

        footer {
            background-color: #00333a;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <div class="top-bar">
            <div class="logo">
                <img src="logo.png" alt="UniVida Saúde Logo">
                <h1>UniVida Saúde</h1>
            </div>
            <nav>
                <a href="#servicos">Serviços</a>
                <a href="#trabalhe">Trabalhe Conosco</a>
                <a href="#contato">Entre em Contato</a>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h1><strong>Cuidando</strong> de você no conforto do seu lar</h1>
            <p>Atendimento humanizado e especializado em Home Care</p>
        </div>
        <div class="hero-image">
            <img src="blocos-saude.png" alt="Blocos com ícones de saúde">
        </div>
    </section>

    <section class="section" id="servicos">
        <h2>Nossos Serviços</h2>
        <div class="services-list">
            <div class="service-box service-enfermeiro">
                <h3>Enfermeiros</h3>
                <p>Profissionais capacitados para cuidados clínicos e acompanhamento contínuo.</p>
            </div>
            <div class="service-box service-tecnico">
                <h3>Técnicos de Enfermagem</h3>
                <p>Suporte técnico qualificado para as necessidades diárias de saúde.</p>
            </div>
            <div class="service-box service-fisio">
                <h3>Fisioterapeutas</h3>
                <p>Reabilitação e fisioterapia domiciliar com qualidade e atenção individualizada.</p>
            </div>
            <div class="service-box service-multi">
                <h3>Equipe Multidisciplinar</h3>
                <p>Atendimento integrado com nutricionistas, terapeutas ocupacionais e mais.</p>
            </div>
        </div>
    </section>

    <section class="trabalhe" id="trabalhe">
        <h2>Trabalhe Conosco</h2>
        <p>Se você é um profissional da saúde e quer fazer parte da nossa equipe, envie seu currículo para:</p>
        <p><a href="mailto:instituto.unividasaude@gmail.com">instituto.unividasaude@gmail.com</a></p>
    </section>

    <section class="contact" id="contato">
        <h2>Entre em Contato</h2>
        <p>Tem dúvidas ou deseja saber mais sobre nossos serviços? Fale conosco por e-mail:</p>
        <p><a href="mailto:instituto.unividasaude@gmail.com">instituto.unividasaude@gmail.com</a></p>
    </section>

    <footer>
        <p>&copy; 2025 UniVida Saúde - Cooperativa de Trabalho de Profissionais de Saúde</p>
    </footer>
</body>
</html>
