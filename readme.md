SDK V2 de integração - Android
=======================

Conteúdo:

[/JARs/Stone/](https://github.com/stone-pagamentos/sdk-android-V2/tree/master/JARs/Stone) contém um único .jar com todas as seguintes dependências:
<br>

<i>Para envio de email</i>
* Mail.jar
* Activation.jar
* additionnal.jar
<br>

<i>Base64 encoder</i>
* commons-codec.jar
<br>

<i>JSON</i>
* Gson_v1.7.2.jar
<br>

<i>XML</i>
* Xstream_v1.4.7.jar

[/JARs/Dependências/](https://github.com/stone-pagamentos/sdk-android-V2/tree/master/JARs) contém todas as libs mencionadas e o jar de integração da Stone.<br>
Esta caso você possua essas libs no seu projeto, você tem a opção de remove-las e utilizar o jar da pasta /JARs/Stone/ ou adicionar as dependências e o jar de integração da Stone.

Change Log
=======================

Conteúdo:

<i><b>v2.0.3</b></i>
* [!] Hotfix nos tipos de conexão;
* [!] Correções e melhorias na Demo;
* [+] Documentação na pasta [/doc/](https://github.com/stone-pagamentos/sdk-android-V2/tree/master/doc);
* [+] Demo utilizando o Android Studio;
* [+] Demo - exemplo do DisplayMessageProvider;


<i><b>v2.0.2</b></i>
* [!] Hotfix na impressão com Ingenico (Logo da Stone);
* [!] Melhores tratamentos no bluetooth;
* [!] Melhorias na impressão (tratamentos para status diferente de 00);
* [&] Correções na Demo (Extra)


<i><b>v2.0.1</b></i>
* [!] Hotfix no QR Code com Pinpads da Ingenico;
* [!] Pequenas correções na transação (update na coluna 'request_id' da transação);
* [+] Adicionada a função que o integrador poder enviar o ITK (identificador único da transação) pelo método 'setInitiatorTransactionKey(SEU_ITK_AQUI_STRING)' do objeto StoneTransaction;
* [#] Assinatura do objeto PrintProvider mudou, agora você precisa informar qual pinpad você está utilizando, se estiver conectado a somente um Pinpad, passe 'GlobalInformations.getPinpadFromListAt(0)'
