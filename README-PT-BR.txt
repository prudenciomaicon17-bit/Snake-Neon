NEON SNAKE — PROJETO ANDROID

Este projeto transforma o jogo HTML em um aplicativo Android usando WebView.
O arquivo do jogo está em:
app/src/main/assets/index.html

COMO GERAR O APK DE TESTE PELO GITHUB (sem precisar instalar Android Studio):
1. Extraia este ZIP.
2. Crie um repositório novo no GitHub e envie TODOS os arquivos e pastas deste projeto.
3. Abra a aba Actions do repositório.
4. Se necessário, autorize o uso de GitHub Actions.
5. Execute "Build NEON SNAKE APK" com Run workflow (ou aguarde o build após enviar os arquivos).
6. Quando terminar com sucesso, abra a execução e baixe o artefato "NEON-SNAKE-APK".
7. Dentro dele estará app-debug.apk. Baixe no Android e instale.
   Talvez seja necessário autorizar "Instalar apps desconhecidos" para o navegador/gerenciador de arquivos.

IMPORTANTE:
- Este ZIP é o projeto-fonte Android, não é o APK já compilado.
- O APK debug serve para teste e não é o arquivo final para publicar na Play Store.
- O jogo roda offline: não precisa de internet durante a partida.
- O Android pode exibir um aviso ao instalar APK fora da Play Store.
