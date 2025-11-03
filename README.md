IGaming PIX — Android WebView App (SIMULAÇÃO)
-------------------------------------------

O pacote contém um projeto mínimo do Android Studio que carrega o arquivo HTML local (assets/www/index.html)
em um WebView. Este app é destinado apenas para uso em ambiente de testes e demonstrações — o HTML inclui
uma marcação clara "SIMULAÇÃO - NÃO É PAGAMENTO REAL".

Como gerar o APK no seu computador (passos resumidos):
1. Instale o Android Studio: https://developer.android.com/studio
2. Abra a pasta 'igaming_pix_app' no Android Studio (File -> Open...). O Android Studio vai sincronizar/baixar o Gradle.
3. Se necessário, atualize o Android SDK para a versão sugerida (compileSdk 33).
4. Build -> Build Bundle(s) / APK(s) -> Build APK(s).
5. Após o build, clique em 'locate' para encontrar o APK gerado. Para distribuir em modo 'release' você precisará assinar o APK com sua keystore.

Observações:
- Eu não consigo compilar o APK aqui diretamente. Você precisa usar o Android Studio localmente para gerar o binário.
- Se quiser, posso também fornecer uma versão baseada em Capacitor/Flutter/Cordova em vez de um WebView nativo — diga qual prefere.
- Nunca utilize este app para enganar usuários ou simular pagamentos reais. Use somente para testes e demonstrações com a marcação de SIMULAÇÂO visível.
