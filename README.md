O principal proposito do git é trabalhar em grupo no desenvolvimento de um projeto. Proporcionando agilidade, pois através dos ramos 
cada integrante do grupo pode criar ou modificar o conteúdo proposto ao mesmo tempo e cada um em seu computador.
Caso aconteça algum erro conseguiremos observar as versões anteriores e voltar corrigindo erros e recuperando possiveis perdas por exemplo.
Alem de proporcionar agilidade, os arquivos ficam armazenados em nuvem, com mais segurança.
Pode se observar a produtividade de cada integrante do grupo durante o processo.

Aprendi no curso a utilizar o github juntamente com o git bach no computador através de comandos.
Aprendi a criar repositórios e organizações. A criar ramos no meu projeto e no projeto em que fui adicionado.
aprendi a realizar o pull request.

abaixo os comandos utilizados: 

Avaliação;

Passos:
 - primeiramente abri o github e fiz login na minha conta 
   no navegador edge, pois é melhor pra confirmação de conta;


 - Depois fui em "your repositories" e criei um "New"(novo) 
   repositório chamado "turismo";


 - No computador, criei uma pasta dentro de:
	C:\xampp\htdocs\Sergio 
	
	Na pasta Sergio, com o botão direito do mouse, 
	abri o "Git Bash", e dei um git init


 - Criei um arquivo em txt nomeado "bom_dia e salvei na pasta.


 - Então segui os devidos procedimentos:
	- git status
	- git add .
	- git status(vi que o arquivo bom_dia.txt foi reconhecido)
	- git commit -a -m "bom dia"
	  obs: Devido ao fato de estar realizando a avaliação em outro Computador
	      foi necessário digitar os comandos: git 
	      - $ git config --globaluser.email "sergio.vieira@fatec.sp.gov.br"
		e o comando: git config -- globaluser.name "sergio"
	
	- Em Seguida, voltei no github e copiei o link:
	  git remote add origin https://github.com/servieira/turismo.git
	
	- Voltei no Git Bash, e dei um "Paste" para colar o comando
	- finalmente utilizei o comando git push origin master
	
	Novo ramo:
	Criei um novo ramo chamado "back-end"
	no github
	
	Abri o Visual Studio Code, Criei:
	- Uma pasta chamada "back-end"
	- Um Arquivo Chamado UserController.js
	No Git Bach digitei: 
	- git status
	- git add .
	- git commit -a -m "arquivo js inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:ProductController.php
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo php inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:Product.html
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo html inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:AdminController.js
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo admin js inserido"
	- git push origin back-end
	- Cliquei no botão "Compare pull request
	- depois em "Create pull request"
	- depois em merge pull request
	- por ultimo em confirm merge

	Voltei no Visual Studio code e criei a pasta models
	nela criei o arquivo:product.class.php
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo product.class.php inserido"
	- git push origin back-end
	
	
	
	Voltei no Visual Studio code e criei o arquivo:index.php
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo index.php inserido"
	- git push origin back-end
	
	Voltei no Visual Studio code e criei o arquivo:usuario.class.php
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo usuario.class.php inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:login.class.php
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo login.class.php inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:
	- loginDAO.php
	- productDAO.php
	- usuarioDAO.php
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo todos os DAOS.php inserido"
	- git push origin back-end
	- Cliquei no botão "Compare pull request
	- depois em "Create pull request"
	- depois em merge pull request
	- por ultimo em confirm merge


	Criei um novo ramo: git checkout -b "front-end"
	Voltei no Visual Studio code e crieia pasta "front-end" e o arquivo:
	- index.html	
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo index.html inserido"
	- git push origin back-end
	
	
	Voltei no Visual Studio code e crieia pasta "front-end" e o arquivo:
	- usuario.html	
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo usuario.html inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:
	- login.html	
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo login.html inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:
	- produto.html	
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo produto.html inserido"
	- git push origin back-end

	Voltei no Visual Studio code e criei o arquivo:
	- cat_produto.html	
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo cat_produto.html inserido"
	- git push origin back-end
	
	Voltei no Visual Studio code e criei os arquivos:
	- estilo.css e gatinho.css	
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "arquivo arquivos.css inseridos"
	- git push origin back-end
	
	adicionei 5 imagens
	Voltei no Git Bash e digitei os comandos:
	- git status
	- git add .
	- git commit -a -m "Imagens inseridas"
	- git push origin back-end
