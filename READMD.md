# Preparação de ambiente
Criar uma máquina virtual para instalar as ferramentas e dependências para o estudo de algoritimos e lógica de programação.


## Criar o diretório base
Vamos criar um diretório para guardar a nossa máquinavirtual. Será criado no Drive D. Nomeada com o nome do usuário.


<img src="criar-diretorio-d.png">

## Preparação da máquina virtual
### Vamos usar a ferramenta de virtualização chamada virtual Box

<img src="tela-virtualbox.png">

<a href= "https://www.virtualbox.org/wiki/Downloads"> Faça o downlond aqui </a>


## Criando a máquina virtual

<img src= "criando-maquina-virtual.png">


## Criando usuário e senha (Será solicitado após a instalação do Ubuntu)

<img src="tela-usuario.png">

## Inserindo as configurações dde Hardware para a instalação do Ubuntu

<img src= "hardware1.png" >

<img src= "hardware.png">

Concluindo a configuração de hardware, clique em finalizar.

# Instalando e configurando a Linux Ubuntu Server

Após a instalação do Ubuntu, insira o usuário e a senha que criou na configuração na maquina virtualbox

<img src="tela-login.png">
Observação: Aperte enter para aparecer o usuário e senha.

## Configuração e atualização dos comandos e app do Ubuntu

Na tela informa as configurações de hardware utilizados pelo sistema operacional e a quantidade de updates a serem aplicados

<img src="sistema.png">

Para atualizar o sistema iremos usar os seguintes comandos:

```` shell
sudo apt update -y
````
<img src="comando1.png">

```` shell
sudo apt upgrade -y
````
<img src="comando-.png">
<img src="comando2.png">

_reboot (irá reiniciar o Ubuntu)

_Instalar o cockpit - ferramenta para gerenciar o servidor, por meio de um ambiente gráfico online

<img src="cockpit.png">



```` shell
sudo apt install cockpit
````
<img src="yescockpit.png">

Confirme a instalação com: yes

<img src="cockpitfinal.png">







