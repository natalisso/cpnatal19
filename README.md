# cpnatal19
## Workshop about deploy on heroku with ansible

* **Instalando o ansible:**
    * Criar ambiente virtual:

        `$ virtualenv -p python3 cpnatal`

    * Ativar ambiente:

        `$ source cpnatel/bin/activate`

    * Instalar ansbile:

        `$ pip install ansible`


* **Primeiro playbook ansible**
    * Construindo nosso primeiro playbook para pingar seu localhost. No repositório tem um exemplo chamado `ping.yml`.
    Para executar rode o seguinte comando:
    
        `$ ansible-playbook ping.yml`
    