# Cabreúrismo

Protótipo estático e responsivo de um guia turístico de Cabreúva, criado somente com HTML5, Bootstrap e CSS3. A página navega por âncoras e links externos; não usa JavaScript, backend, formulários ou banco de dados. Paleta e tipografia são provisórias: a referência do Canva disponibilizou a estrutura do conteúdo, mas não permitiu confirmar os elementos gráficos exatos.

## Abrir localmente

Abra `index.html` diretamente no navegador ou execute `python3 -m http.server 3000` na pasta do projeto e acesse `http://localhost:3000`. Não há dependências para instalar.

## Arquivos

- `index.html`: página e conteúdo.
- `style.css`: estilos responsivos e variáveis de cor.
- `images` pasta de images.
- `manus-routes.json`: manifesto da rota estática principal.

## Conteúdo e créditos

As informações sobre os atrativos e o roteiro são baseadas no [Destino Cabreúva](https://destinocabreuva.com/), em especial [Roteiro Conhecendo Cabreúva](https://destinocabreuva.com/roteiro-conhecendo-cabreuva/) e [Roteiros](https://destinocabreuva.com/roteiros-3/). O formato de apresentação das rotas foi inspirado na organização da [página de Rotas do Turismo de Itu](https://turismo.itu.sp.gov.br/rotas/), sem copiar o seu conteúdo.

A imagem de destaque mostra a Estrada dos Romeiros e tem crédito de Erich Sacco/iStock, via [Catraca Livre](https://catracalivre.com.br/viagem-livre/cidade-no-interior-de-sp-se-destaca-por-suas-belezas-naturais-tranquilidade-e-bom-custo-de-vida/). Para fotos com licença comercial ou distribuição independente, obtenha autorização do respectivo titular antes de publicar.

Informações sobre horários, reservas e condições de acesso podem mudar; confirme diretamente com os locais antes da visita. Os atalhos do Google Maps pesquisam os locais e não calculam uma rota validada. Para publicação na Vercel, mantenha a estrutura da pasta e publique como site estático; as fotografias usam um caminho relativo dentro de `images/`.

Integrantes:
Bruno Lopes
Enzo Bruni
Luiz Henrique 
Otavio Costa
