# bot-selecao-militar-temporario
Bot desenvolvido por jh00nbr, e atualizado por mim.

O bot é responsável pelo acompanhamento das atualizacoes em sites de processo seletivo para militar temporário do Exército Brasileiro e  notificar no [Grupo Militar Temporário do Brasil(Clique para entrar)](https://telegram.me/joinchat/CWigpgp-p7N0Twaj2kGUgg)  no  telegram.




https://telegram.me/joinchat/CWigpgp-p7N0Twaj2kGUgg

http://lab.insightsecurity.com.br/verificando-atualizacoes-do-processo-seletio-de-cabo-especialista-temporario-2016-2/



# Instalação das dependências

```sh
pip install -r requeriments.txt
```

# Configurações:

No caso de utilização por terceiros, é necessário configurar os campos "bot_key" para a key criado do seu bot do telegram.
config = {"bot_key":"key_do_seu_bot","grupo_id":id_do_seu_grupo(int),"url":"http://www.11rm.eb.mil.br/index.php/ultimas-noticias/143-cet-cabo-especialista-temporario-2016"}


# Em caso do erro abaixo:

```sh
from bs4 import BeautifulSoup
ImportError: No module named bs4
```

Instale a lib BeautifulSoup4 
```sh
pip install BeautifulSoup4
```

### Todos

 - Mapeamento das páginas dos sites de seleção
 - Add Code Comments


