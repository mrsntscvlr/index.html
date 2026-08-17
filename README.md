<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog Personalizado</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: #ffffff;
            padding: 2rem 1rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        nav {
            background-color: #34495e;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            padding: 0.8rem;
        }

        nav a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #1abc9c;
        }

        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1rem;
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 2rem;
        }

        article {
            background: #ffffff;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        article h2 {
            color: #2c3e50;
            margin-bottom: 0.5rem;
        }

        .data-post {
            font-size: 0.85rem;
            color: #7f8c8d;
            margin-bottom: 1rem;
        }

        article p {
            margin-bottom: 1rem;
        }

        .btn-leia-mais {
            display: inline-block;
            background-color: #1abc9c;
            color: #ffffff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
        }

        .btn-leia-mais:hover {
            background-color: #16a085;
        }

        aside {
            background: #ffffff;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            height: fit-content;
        }

        aside h3 {
            color: #2c3e50;
            margin-bottom: 1rem;
            border-bottom: 2px solid #1abc9c;
            padding-bottom: 0.3rem;
        }

        aside ul {
            list-style: none;
        }

        aside li {
            margin-bottom: 0.5rem;
        }

        aside a {
            color: #34495e;
            text-decoration: none;
        }

        aside a:hover {
            color: #1abc9c;
        }

        footer {
            background-color: #2c3e50;
            color: #ffffff;
            text-align: center;
            padding: 1.5rem;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Blog de Tecnologia & Vida</h1>
        <p>Explorando ideias, rotinas e novidades do mundo digital</p>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Artigos</a>
        <a href="#">Sobre</a>
        <a href="#">Contato</a>
    </nav>

    <div class="container">
        <main>
            <article>
                <h2>Como Organizar sua Rotina de Estudos</h2>
                <div class="data-post">Publicado em 15 de Maio de 2026 por Ana Silva</div>
                <p>Manter a consistência nos estudos pode ser um desafio diário. Neste post, compartilhamos técnicas comprovadas como o método Pomodoro e o uso de mapas mentais para otimizar seu tempo e render mais...</p>
                <a href="#" class="btn-leia-mais">Ler mais</a>
            </article>

            <article>
                <h2>As Principais Tendências de Tecnologia para este Ano</h2>
                <div class="data-post">Publicado em 10 de Maio de 2026 por Carlos Souza</div>
                <p>A inteligência artificial e a automação continuam transformando o mercado de trabalho. Entenda quais habilidades valem a pena aprender agora para se manter atualizado no setor tecnológico...</p>
                <a href="#" class="btn-leia-mais">Ler mais</a>
            </article>
        </main>

        <aside>
            <h3>Sobre o Blog</h3>
            <p style="margin-bottom: 1.5rem;">Um espaço dedicado a compartilhar conhecimentos práticos sobre tecnologia, produtividade e desenvolvimento pessoal.</p>

            <h3>Categorias</h3>
            <ul>
                <li><a href="#">• Tecnologia</a></li>
                <li><a href="#">• Produtividade</a></li>
                <li><a href="#">• Tutoriais</a></li>
                <li><a href="#">• Estilo de Vida</a></li>
            </ul>
        </aside>
    </div>

    <footer>
        <p>&copy; 2026 Blog de Tecnologia & Vida. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
