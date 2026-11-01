# Marcador de Fodinha (app web)

Marcador de palpites e pontos do Fodinha. Funciona sem internet depois da primeira abertura e pode ser instalado na tela inicial do celular.

## Arquivos

- `index.html`: o app inteiro (jogo, histórico e manual).
- `manifest.webmanifest`: nome, cores e ícones do app.
- `sw.js`: guarda o app no aparelho para abrir offline.
- `icons/`: ícones do app.

## Publicar no GitHub Pages

1. No GitHub, crie um repositório novo (por exemplo `fodinha`) ou escolha uma pasta de um repositório que você já usa.
2. Envie todos os arquivos desta pasta mantendo a estrutura, com `index.html` na raiz da pasta publicada.
3. Em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.
4. Aguarde um ou dois minutos. O endereço será parecido com `https://SEU-USUARIO.github.io/fodinha/`.

Todos os caminhos são relativos, então funciona tanto na raiz do site quanto em subpastas.

## Instalar no celular

- **iPhone:** abra o endereço no Safari, toque em Compartilhar e depois em "Adicionar à Tela de Início".
- **Android:** abra no Chrome, toque nos três pontinhos e depois em "Instalar app" (ou "Adicionar à tela inicial").

O jogo em andamento fica salvo no próprio aparelho. No iPhone, o ícone da tela inicial guarda os dados separados do Safari, então comece o jogo já pelo ícone. Use um único celular como marcador central.

## Atualizar o app

Depois de mudar qualquer arquivo, aumente o número em `VERSION` no começo de `sw.js` (por exemplo `fodinha-v2`). Assim os aparelhos baixam a versão nova na próxima abertura.

## Fontes

As fontes (Big Shoulders Display e Schibsted Grotesk) vêm do Google Fonts e ficam guardadas no aparelho depois da primeira abertura. Sem elas, o app usa fontes do sistema e continua funcionando.
