<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido de Namoro</title>
    <style>
        /* Estilizando o botão */
        .botao-namoro {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            border-radius: 8px;
        }
    </style>
</head>
<body>

<h2>Você aceita namorar comigo?</h2>

<!-- Botão de "Sim" -->
<button class="botao-namoro" onclick="alert('Ufa, ainda bem! Não aguentava mais.')">Sim</button>

<!-- Botão de "Não" -->
<button class="botao-namoro nao" onclick="naoOption()">Não</button>

<script>
    // Função para exibir a mensagem ao clicar na opção "Não"
    function naoOption() {
        alert("Essa opção você não tem, ou é sim ou é morte");
    }
</script>

</body>
</html>
