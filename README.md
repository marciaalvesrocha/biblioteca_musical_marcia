# Sistema Musical

## Sobre a atividade

Esta atividade consiste no desenvolvimento da parte visual de um Sistema Musical utilizando HTML e CSS. O objetivo é criar páginas para organizar artistas e músicas, permitindo visualizar cadastros e acessar as principais áreas do sistema por meio de um menu.

O projeto foi dividido em páginas HTML, cada uma com uma função específica, e utiliza um arquivo CSS externo para manter a aparência padronizada.

## Funcionalidades e páginas

### 1. Login (`login.html`)

Página de acesso ao sistema. Possui campos para informar usuário e senha e um botão para entrar.

Credenciais de teste:
- Usuário: `admin`
- Senha: `123`

### 2. Menu principal (`index.html`)

O menu principal apresenta as opções disponíveis:
- Gerenciar artistas;
- Cadastrar músicas;
- Acessar a biblioteca musical;
- Sair do sistema.

Cada opção possui um link que direciona para a página correspondente.

### 3. Cadastro de artistas (`cadastro_artista.html`)

Página destinada ao cadastro e à visualização de artistas. O formulário apresenta os seguintes campos:
- Nome do artista (obrigatório);
- Gênero musical;
- País;
- Foto do artista.

Abaixo do formulário, há uma tabela com artistas cadastrados, exibindo foto, nome, gênero, país e opções de ações. Também existe um link para acessar o cadastro de músicas.

### 4. Cadastro de músicas (`cadastro_musica.html`)

Página utilizada para preencher as informações de uma música. Os campos disponíveis são:
- Artista (obrigatório);
- Título da música (obrigatório);
- Álbum;
- Gênero;
- Link do YouTube (obrigatório);
- Capa do álbum;
- Letra da música.

A página também apresenta uma tabela com músicas cadastradas, mostrando a capa, o título, o álbum, o link para assistir e as opções de ações.

### 5. Biblioteca musical (`listagem_musicas.html`)

Página que reúne as músicas em uma tabela. Ela permite visualizar informações como capa, título, artista, álbum, gênero e link do YouTube.

Também apresenta filtros para facilitar a busca, com opções de pesquisa geral, seleção de artista e seleção de gênero.

### 6. Estilos do sistema (`styles.css`)

Arquivo responsável pela parte visual de todas as páginas. Nele são definidos:
- Cores e fontes;
- Espaçamentos e tamanhos;
- Aparência dos formulários e campos;
- Estilo dos botões e links;
- Organização das tabelas;
- Aparência dos menus;
- Ajustes para telas menores, por meio de media queries.

## Tecnologias utilizadas

- **HTML5:** utilizado para estruturar as páginas, formulários, tabelas e links.
- **CSS3:** utilizado para definir cores, fontes, espaçamentos, organização e aparência dos elementos.

## Organização dos arquivos

```text
Sistema-Musical/
├── index.html
├── login.html
├── cadastro_artista.html
├── cadastro_musica.html
├── listagem_musicas.html
└── styles.css
```

## Como executar o projeto

1. Baixe ou copie todos os arquivos do projeto para uma mesma pasta.
2. Verifique se o arquivo `styles.css` está na mesma pasta que os arquivos HTML.
3. Abra o arquivo `login.html` em um navegador.
4. Visualize as demais páginas utilizando os links disponíveis no sistema.

Não é necessário instalar programas ou bibliotecas adicionais para visualizar as páginas.

## Observação

Nesta etapa, o projeto apresenta a estrutura visual e a navegação entre as páginas. Os formulários estão preparados em HTML, mas os arquivos enviados não apresentam integração com banco de dados ou processamento no servidor. Por isso, as operações de cadastrar, editar, excluir, filtrar e realizar o login ainda não possuem funcionamento completo.

## Conclusão

A atividade permitiu praticar a criação de páginas com HTML e a estilização com CSS, trabalhando com formulários, tabelas, campos de entrada, botões, links e organização de conteúdo. O resultado é a estrutura visual de um sistema para gerenciamento de artistas e músicas.
