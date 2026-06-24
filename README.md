# Organizador de Louvor

Ferramenta web para organizar **letras** e **cifras** de louvor e exportar em **PDF** com a identidade visual da PBC (marca d'água, estrutura da música no topo e rodapé padrão).

Tudo roda no navegador — não precisa instalar nada nem ter servidor. É um único arquivo: `index.html`.

## O que funciona online (em qualquer navegador)

- **Importar PDF** de cifra (lê o arquivo e preenche nome, tom e a cifra automaticamente).
- **Organizar letras / Montar cifras** com seções coloridas (Intro, Verse, Chorus, Bridge…).
- **Estrutura da música** editável (reordenar, repetir e remover seções) que aparece no topo do PDF.
- **2 colunas** quando quiser.
- **Exportar PDF** com marca d'água, estrutura no topo e rodapé padrão.
- Nome do arquivo automático: `Nome - Tom - Cifras.pdf`, `Nome - Letras.pdf` ou `Nome - Lyrics.pdf`.

> Observação: a marcação por **IA** depende do ambiente do Claude e **não** funciona em um site estático. Na versão publicada, o botão "Organizar/Montar" usa o **modo offline** (detecta os rótulos do PDF e agrupa as estrofes). Importar PDF, editar a estrutura e gerar o PDF funcionam normalmente.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `organizador-louvor`).
2. Envie o arquivo **`index.html`** para a raiz do repositório (botão **Add file → Upload files**).
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**; selecione a branch **main** e a pasta **/ (root)**; clique em **Save**.
5. Aguarde ~1 minuto. O link aparece no topo da página de Pages, no formato:
   `https://SEU-USUARIO.github.io/organizador-louvor/`
6. Pronto — é só compartilhar esse link. Qualquer pessoa abre e usa.

## Como atualizar depois

Sempre que quiser mudar algo, basta substituir o `index.html` no repositório (Upload files → commit). O site atualiza sozinho em seguida.

## Requisitos do navegador

Funciona em navegadores atuais (Chrome, Edge, Firefox, Safari recentes). A leitura de PDF usa recursos modernos do navegador; em navegadores muito antigos pode não funcionar — nesse caso, é só colar a cifra/letra manualmente no campo.
