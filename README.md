<h1 align='center'> AUTOMAÇÃO DE CONFIGURAÇÃO PARA ONUs STAVIX AC </h1>

<hr>

<p align='center'> Um aplicativo desenvolvido utilizando Python e Selenium. </p>

<p align='center'><img  src='https://user-images.githubusercontent.com/106451416/187090113-3cd194f0-245f-422c-ac1b-645496849077.png' alt='Interface'></p>



<h3> Assista ao vídeo demonstrativo </h3>
<hr>

[![Video Demonstrativo Stavix](https://user-images.githubusercontent.com/106451416/187091862-5aab9101-ae17-4420-990e-35f24b470057.png)](https://youtu.be/2H9MM_9q_QQ)

<h3> Problemática </h3>
<hr>
<p>Em meu trabalho em uma empresa de Telecomunicações, trabalhando como Auxiliar de Instalação, após concluir a instalação da fibra optica, configuravamos a ONU Stavix AC para então liberarem o acesso no sistema.
Era necessário : </p>
<blockquote>
<p> → Configurar as duas frequencias de rede Wifi (2.4G e 5.8G)) <br> </p>
<p> → Inserir a VLAN, o usuario PPPOe do cliente e ativar as portas LAN <br> </p>
<p> → Ativar outras opções na ONU como UPNP e Ping <br> </p>
<p> → Trocar a senha de acesso do painel de configuração, para a senha padrão utilizada na empresa <br> </p>
</blockquote>

<h3> Linguagem e bibliotecas </h3>
<hr>
<blockquote> 
<p><a href='python.org'> Python </a></p>
<p><a href='https://pypi.org/project/selenium/'> Selenium </a></p>

<code> pip install selenium </code>

<p> <a href='https://pypi.org/project/PySimpleGUI/'> PySimpleGui </a> </p>

<code> pip install PySimpleGUI </code>

<p><a href='https://pypi.org/project/auto-py-to-exe/'> Auto-Py-To-Exe </a> (opcional)</p>

<code> pip install auto-py-to-exe</code>

</blockquote> 

<h3> Pré-requisitos </h3>
<p text-align='center'> É necessário possuir o Webdriver do Chrome para Selenium interagir com o navegador. </p>
<a href='https://chromedriver.chromium.org/downloads'> Chrome Driver </a>


<h3> Colocando para funcionar </h3>
<hr>
<p> Após ter o Python instalado e as bibliotecas necessárias, precisamos garantir que o <a href='https://chromedriver.chromium.org/downloads'> Chrome Driver </a> esteja na raiz do Python.
Para isso, basta abrir o terminal e inserir o seguinte comando:

<code> where Python </code>

![image](https://user-images.githubusercontent.com/106451416/187091233-c1b6bd96-36be-4567-868e-01aba41b3c7e.png)


Com a raiz do diretorio do seu Python, basta deixar o ChromeDrive na pasta raiz do Python.

![image](https://user-images.githubusercontent.com/106451416/187092062-54db097a-0904-4e8a-ba07-846bb7f8dd99.png)

Com tudo pronto, você pode executar o código em seu interpretador, ou utilizar o <a href='https://pypi.org/project/auto-py-to-exe/'> Auto-Py-To-Exe </a> para criar um arquivo executavél. (Igual é demonstrado no <a href='https://youtu.be/2H9MM_9q_QQ'>vídeo demonstrativo no YouTube </a>)



