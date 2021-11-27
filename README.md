# DjangoNL
## Agenda_Python_Django

#### Objetivo:
	Este projeto tem como objetivo criar uma agenda estilo to-do list com Python Django. 
	
	
	
![Screens](https://image.prntscr.com/image/d_ZnAB_zTxGfOpCQM-7cnA.png "Screens")
	
<hr style="height: 10px;">
##### Login
	Tela de login, com Admin, somente ele pode cadastrar novos usuários
	
![CSS e DJango](https://image.prntscr.com/image/5JAy7a6ARVy-kFg_Ya5ugg.png "CSS e DJango")


### CSS no Django

Para trabalhar com CSS no Django, utilizamos a pasta "static" dentro da pasta Core do projeto.

![core](https://i.imgur.com/q36AdSw.png "core")

Adicionamos o STATICFILES_DIRS no arquivo settings 

![settings](https://i.imgur.com/pz138Yh.png "settings")

No HTML, adicionamos o {% load static %} em cima da tag < link> e no SRC adicionamos {"% static 'caminho' %"}


![load](https://i.imgur.com/cYw8Geq.png "load")

Lista de tarefas (Retificada)

![lista](https://i.imgur.com/mAHZp66.png "lista")

Tela de cadastro de novo item da lista

![Cadastro de novo item](https://i.imgur.com/MWQxBG7.png "Cadastro de novo item")
