# Formulário de Cadastro de Veículo

Este projeto é um formulário simples para cadastro de veículos, com o objetivo de facilitar a venda e descrição detalhada dos itens do veículo. Foi desenvolvido utilizando HTML e CSS, com foco em praticar estilização de formulários e boas práticas de design.

## Estrutura do Projeto

O projeto é composto por uma página HTML que contém um formulário de cadastro de veículos, com validação básica e estilização para facilitar a usabilidade.

### Tecnologias Utilizadas

- **HTML5**: Para a marcação do formulário e seus elementos.
- **CSS3**: Para a estilização e layout do formulário.

## Arquivos Principais

- `index.html`: O arquivo HTML principal da página que contém o formulário.
- `./css/style.css`: O arquivo CSS que define os estilos da página.

## Funcionalidades do Formulário

1. **Preço do Anúncio**: Campo obrigatório para inserir o preço do veículo.
2. **Título do Anúncio**: Campo obrigatório para inserir o título do anúncio.
3. **Descrição**: Área de texto para descrever as características e detalhes do veículo.
4. **Marca e Modelo**: Campos obrigatórios para inserir a marca e o modelo do veículo.
5. **Kilometragem**: Campo para inserir a quilometragem do veículo.
6. **Data de Compra**: Campo para inserir a data de compra do veículo.
7. **Tipo de Câmbio**: Opções de câmbio manual e automático.
8. **Opcionais**: Lista de opcionais, como Airbag e Sistema de Som.
9. **Imagens**: Campo para upload de imagens do veículo.
10. **Botão de Envio**: Um botão estilizado para submeter o formulário.

## Exemplo de Estrutura de Código HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Veículo</title>
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <h3>Cadastre seu Veículo para vender mais rápido!</h3>
        </div>
        <div class="form-container">
            <div class="form-header">
                <p>Formulário</p>
            </div>
            <form action="">
                <div class="box-input">
                    <label for="price">Preço do Anúncio <span class="requiredField">*</span></label>
                    <input type="text" id="price" class="block" placeholder="Digite o preço" required>
                </div>
                <!-- Outros campos omitidos para brevidade -->
                <input type="submit" value="Enviar" class="btn-submit">
            </form>
        </div>
    </div>
</body>
</html>
## Objetivo

O principal objetivo deste projeto é praticar a criação e estilização de formulários complexos utilizando HTML e CSS. A ideia é criar uma interface amigável e funcional para o cadastro de veículos, com atenção a:

- Design responsivo e estilização limpa.
- Uso de diferentes tipos de campos de formulário (texto, número, data, rádio, checkbox, file upload).
- Validação básica de campos obrigatórios.

## Créditos

Projeto desenvolvido por **isaquefreitasdev**, com o intuito de aprimorar suas habilidades em HTML e CSS.

## Como Utilizar

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` diretamente no seu navegador para visualizar a página do formulário.
3. Preencha os campos conforme necessário.
4. Clique no botão **Enviar** para submeter o formulário (a funcionalidade de envio não está conectada a um back-end).

## Licença

Este projeto está disponível para uso livre, principalmente para fins educacionais e não comerciais.
