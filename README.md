﻿# :rotating_light: Automatizacao eSocial - Domínio Sistemas
Com o propósito de aumentar a produtividade dos funcionários do Depto. Pessoal, desenvolvi um RPA que realiza todo o procedimento de envio do eSocial dentro do ERP da Domínio Sistema (Thomson Reuters), desde o envio dos 'Pagamentos' e 'Remuneração' até o envio do 'Fechamento dos Eventos Periódicos' para o Ecac - Receita Federal.

A automatização foi desenvolvida utilizando biblioteca 'Pywinauto' como principal e essencial devido ao poder de manipulação de janelas que ela apresenta (documentação disponível no rodapé deste README). 

**:books: Entre as outras bibliotecas, estão:** </br>
- Psutil: Permite a interação com um processo no Windows, desde que esta esteja em execução;</br> 
- os: É uma biblioteca de comandos do sistema operacional;</br>
- pyperclip: Permite que a automatização utilize nossa Área de transferência (ctrl+c);</br>
- numpy: Utilizada para processamento de dados, permite obtermos resultados de planilhas;</br>
- sys: Fornece funções e variáveis para manipular diferentes partes do ambiente de tempo de execução, como interromper a execução, por exemplo.</br>
- datetime: Fornece funções de tempo e data;</br>
- pyautogui: Permite a movimentação do mouse por coordenadas e/ou por imagens.</br>
- pandas: Permite a manipulação de planilhas;</br>
- winotify: Executa evento notificação no Windows;</br>
- *biblioteca api do google: Permite a interação do python com as planilhas google (É necessário a utilização dos arquivos credentials.json e token.json para obter acesso às planilhas).

## :point_down: O RPA é dividido em 4 arquivos, são eles:
    1. Imagens: São as imagens da Domínio Sistemas em que o pywinauto não conseguiu realizar a interação;
    2. main.pyw: É o código propriamento dito;
    3. parametrizacao.xlsx: Esta planilha refere-se ao código das empresas cadastradas dentro da Domínio Sistemas;
    4. credentials.json e token.json: São os arquivos que fornecem as credenciais e token de acesso do usuário para utilizar o google planilhas.

**:pushpin: Documentações utilizadas:**</br>
    1. [pyautogui](https://pyautogui.readthedocs.io/en/latest/)</br>
    2. [pywinauto](https://pywinauto.readthedocs.io/en/latest/)</br>
    3. [winotify](https://pypi.org/project/winotify/)</br>
    4. [pandas](https://pandas.pydata.org/docs/user_guide/index.html)
