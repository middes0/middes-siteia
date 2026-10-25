# ONE JUMP

Jogo de plataforma 2D em pixel art, pensado para uma primeira versão pequena e jogável no Android.

## Escopo inicial
- 5 fases curtas em uma tela cada.
- Movimento lateral e pulo com botões de toque.
- Espinhos, plataformas e portal de saída.
- Contador de mortes e recorde local.
- Arte em pixel art desenhada diretamente no canvas.
- Sem conta, servidor ou internet obrigatória.

## Testar no navegador
Abra `index.html` em um navegador moderno. No computador, use as setas ou A/D para mover e Espaço/Seta para cima para pular. No celular, use os botões na tela.

## Gerar APK de teste
O workflow **Build ONE JUMP Android APK** compila um APK de depuração em GitHub Actions. Abra a aba **Actions**, selecione o workflow e use **Run workflow**. Quando terminar, baixe o artefato `ONE-JUMP-debug-APK`.

O APK de depuração serve para testes. Publicar na Play Store exige gerar uma versão assinada (normalmente AAB), preparar a ficha da loja e cumprir as exigências vigentes do Google Play.