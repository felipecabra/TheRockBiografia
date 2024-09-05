<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olimpíadas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <style>
        .banner {
    width: 100%;
    height: 800px;
    background: url(https://portalconteudoaberto.com.br/wp-content/uploads/2024/05/olimpiadas-paris-scaled.jpg) no-repeat center center;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center; /* Adicionado para centralizar o conteúdo verticalmente */
}

.banner div {
    width: 100px;
}

.banner img {
    max-width: 100%; /* Ajustado para manter a proporção da imagem */
    height: auto; 
}
table {
    width: 100%;
    border-collapse: collapse; /* Adicionado para evitar espaçamento entre células */
    margin: 20px 0; /* Adicionado para espaço acima e abaixo da tabela */
}

th, td {
    border: 1px solid #686868; /* Adicionado para bordas das células */
    padding: 8px; /* Adicionado para espaçamento interno das células */
}

th {
    background-color: #dee948; /* Adicionado para cor de fundo dos cabeçalhos */
}
td {
    text-align: center;
}

td img {
    width: 20px; 
    margin: 2px;
}

.newsSection {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.newsDiv {
    display: flex;
    align-items: center; 
}

.newsDiv img {
    width: 150px;
    margin-right: 20px; 
}

.newsDiv h5 {
    font-size: 20px;
    margin: 0;
}

.newsDiv p {
    font-size: 15px;
    color: rgb(117, 117, 117);
    margin: 5px 0;
}

a {
    text-decoration: none;
}

.buttonViewMore {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: rgb(255, 255, 255);
    border-radius: 10px;
    width: 80px;
    height: 20px;
    padding: 5px; /* Adicionado para melhorar a área clicável */
}

.buttonViewMore p {
    margin: 0; /* Removido margens extras do texto */
}

    </style>
    <section class="banner">
        <div>
            
        </div>
    </section>

    <table>
        <thead>
            <tr>
                <th>Posição</th>
                <th>País</th>
                <th>Ouro</th>
                <th>Prata</th>
                <th>Bronze</th>
                <th>Total</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><p>1º</p></td>
                <td>
                  
                    <p>USA</p>
                </td>
                 <td><p>27</p></td>
               <td><p>35</p></td>
                <td><p>33</p></td>
                <td><p>95</p></td>
            </tr>
        </tbody>
    </table>

            <section class="newsSection">
                <div class="displey flex">
            <div class="newsDiv">
            <img src="https://img.olympics.com/images/image/private/t_16-9_640/f_auto/primary/wmzus3toeptpzkadrrdq" alt="Imagem da notícia">
            <div>
                <h5>Título da notícia</h5>
                <p>Descrição</p>
                <a href="https://olympics.com/en/paris-2024/videos/images-of-the-day-day-12-olympic-games-paris-2024">
                    <div class="buttonViewMore">
                    <p>Ver mais</p>
                    </div>
                </a>
            </div>
        </div>
        <div class="newsDiv">
            <img src="https://img.olympics.com/images/image/private/t_16-9_640/f_auto/primary/wmzus3toeptpzkadrrdq" alt="Imagem da notícia">
            <div>
                <h5>Título da notícia</h5>
                <p>Descrição</p>
                <a href="https://olympics.com/en/paris-2024/videos/images-of-the-day-day-12-olympic-games-paris-2024">
                    <div class="buttonViewMore">
                    <p>Ver mais</p>
                    </div>
                </a>
            </div>
        </div>
</div>
    </section>
</body>
</html>












