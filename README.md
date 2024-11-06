<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Franquia de Hamburgueria</title>
    <style>
        /* Estilos gerais */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        
        body {
            color: #333;
            line-height: 1.6;
            background-color: #fdfdfd;
        }

        /* Container principal */
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Cabeçalho */
        header {
            background-color: #FF4B2B;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            color: #fff;
            font-size: 2.5em;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        header h1 img {
            width: 200px; /* Ajuste o tamanho conforme necessário */
            height: auto;
        }

        /* Banner principal */
        .banner {
            background-image: url('https://source.unsplash.com/1600x900/?burger');
            background-size: cover;
            background-position: center;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }

        .banner h2 {
            font-size: 2.5em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        /* Seção de apresentação */
        .presentation {
            padding: 40px 0;
            text-align: center;
        }

        .presentation h2 {
            font-size: 2em;
            color: #FF4B2B;
            margin-bottom: 20px;
        }

        .presentation p {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.1em;
            color: #555;
        }

        /* Benefícios da franquia */
        .benefits {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 40px;
        }

        .benefit-item {
            flex: 1;
            min-width: 250px;
            background-color: #f4f4f4;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
        }

        .benefit-item h3 {
            font-size: 1.5em;
            color: #333;
            margin-bottom: 10px;
        }

        .benefit-item p {
            font-size: 1em;
            color: #666;
        }

        /* Chamada para ação */
        .cta {
            background-color: #FF4B2B;
            color: #fff;
            padding: 30px 0;
            text-align: center;
            margin-top: 40px;
            border-radius: 8px;
        }

        .cta h2 {
            font-size: 2em;
            margin-bottom: 15px;
        }

        .cta a {
            display: inline-block;
            padding: 10px 30px;
            background-color: #fff;
            color: #FF4B2B;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 4px;
            transition: 0.3s;
        }

        .cta a:hover {
            background-color: #333;
            color: #fff;
        }

        /* Rodapé */
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Cabeçalho -->
    <header>
        <h1>
            <img src="logo haven.png" alt="Logo da Hamburgueria">
            Haven Burger
        </h1>
    </header>

    <!-- Banner Principal -->
    <section class="banner">
        <h2>Transforme sua paixão em um negócio de sucesso</h2>
    </section>

    <!-- Seção de Apresentação -->
    <section class="presentation container">
        <h2>Sobre a Franquia</h2>
        <p>Se você é apaixonado por hambúrgueres e quer levar essa experiência para sua cidade, junte-se à Haven Burger e faça parte de uma rede de franquias de sucesso. Oferecemos suporte completo para que você tenha uma operação lucrativa e se destaque no mercado.</p>
    </section>

    <!-- Benefícios da Franquia -->
    <section class="benefits container">
        <div class="benefit-item">
            <h3>Treinamento Completo</h3>
            <p>Receba todo o treinamento necessário para operar a franquia com eficiência.</p>
        </div>
        <div class="benefit-item">
            <h3>Marca Reconhecida</h3>
            <p>Aproveite a força de uma marca já consolidada e atrativa para o público.</p>
        </div>
        <div class="benefit-item">
            <h3>Suporte Contínuo</h3>
            <p>Tenha suporte em marketing, operações e finanças para o sucesso do seu negócio.</p>
        </div>
    </section>

    <!-- Chamada para Ação -->
    <section class="cta">
        <h2>Pronto para abrir sua franquia?</h2>
        <a href="mailto:contato@hamburgueriagourmet.com">Entre em contato</a>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2023 Hamburgueria Gourmet. Todos os direitos reservados.</p>
    </footer>

</body>
</html>

