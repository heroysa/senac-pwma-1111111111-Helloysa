//Senac - Tecnologia em Análise e Desenvolvimento de Sistemas
//
//programa Web - Prof Veríssimo
//
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css" type="text/css">
    <title>NBA 2023</title>
</head>
<body>
    <header>
        <h1>NBA 2023</h1>
    </header>
    <nav>
        <a href="noticias.html" target="centro">Notícias</a>
        <a href="calendario.html" target="centro">Calendário</a>
        <a href="times.html" target="centro">Times</a>
        <a href="destaques.html" target="centro">Destaques</a>
    </nav>
    <main>
        <iframe src="apresentacao.html" name="centro"></iframe>
        
    </main>
    <footer>
        NBA 2023 &copy; Todos os direitos reservados
    </footer>
</body>
</html>
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    font-size: 16px;
    background-color: #f4f4f4;
}

header {
    background-color: #002855;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 36px;
}

nav {
    background-color: #ff8800;
    text-align: center;
    padding: 10px 0;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    font-weight: bold;
}

main {
    background-color: #fff;
    padding: 20px;
}

footer {
    background-color: #002855;
    color: white;
    text-align: center;
    padding: 10px 0;
}

iframe {
    border: 0;
    width: 100%;
    height: 500px;
}
