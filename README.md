# Passo a Passo

1. Ir em Settings
2. Ir em Pages
3. Mudar a "Branch" de None para `main`, deixar como `/(root)` e apertar em "Save"
4. Voltar ao começo do repositório e na parte dos commits vai aparecer uma bolinha amarela, aquilo é o deploy do website. Tem que esperar até ficar um check verde
- É bom fazer um F5 após uns 30 segundos, para esse check aparecer
5. Quando for digitar a url do website, tem que ser nesse modelo
- `nome_do_perfil.github.io/nome_do_repositório/nome_da_página.html`

O GitHub Pages tem algumas limitações, ele não suporta sites dinâmicos, ou seja, você não pode colocar o seu site em PHP pois ele não vai rodar da mesma maneira que ele roda no XAMPP. Ele só suporta sites estáticos (HTML, CSS, JavaScript)

Mas ele também suporta geradores de sites estáticos, como o Jekyll, onde você pode escrever o site inteiro em Markdown, que ele vai "traduzir" para HTML

Existe também varios temas que você pode usar, os temas que o GitHub nativamente são [esses](https://pages.github.com/themes/)

Só que, honestamente, eles são muitos simplistas, então eu uso esse [site](http://jekyllthemes.org/) para usar temas mais bonitos, como o Chirpy, que é o que eu utilizo no meu blog

Geralmente esses temas oferecem um template para usar o tema deles, sem precisar fazer um clone inteiro do tema, como o [Chirpy](https://github.com/cotes2020/chirpy-starter/generate) e o [JustTheDocs](https://github.com/just-the-docs/just-the-docs-template/generate)
