Base de Dados das imagens(.ova) usadas no treinamento Pentest - Impacta
=============================

Repositório para armazenar os DUMPS usados para o treinamento de pentest da [IMPACTA][1]

Dependências
------------

Para a criação do laboratório é necessário ter pré instalado os seguintes softwares:

* [Git][2]
* [VirtualBox][3]

> Para as máquinas com MAC OS aconselhamos, se possível, que as instalações sejam feitas pelo gerenciador de pacotes **brew**.

DUMPS
-----------

Para que o **Lab** aconteca, estamos levando em consideracao que estamos trabalhando com a modalidade BlackBox, desta forma nem uma informacao nos 'e fornecida:

* f544d0575bbfa40282400188a8b9f868  

[Path] / filename                              MD5 sum
-------------------------------------------------------------------------------
* Laboratorios_aula_01.ova                  100% f544d0575bbfa40282400188a8b9f868
* metasploitable-linux-2.0.0.zip	    100% 8825F2509A9B9A58EC66BD65EF83167F

Caracterizando uma maquina completa.

> Caso queiram conferir o HASH, use `md5sum Laboratorios_aula_01.ova`

Nesse laboratório, que está centralizado nas **.OVAs** do [Virtualbox][3], são sugeridas 2 distribuicoes que auxiliam no processo de analise:

Nome       | vCPUs | Memoria RAM | IP             | S.O.¹           | Link para Download²
---------- |:-----:|:-----------:|:--------------:|:---------------:| -----------------------------
Kali Linux | 1     | 3072MB      | 192.168.56.100 | Kali Linux      | [https://www.kali.org/get-kali/][5]
Parrot     | 1     | 3072MB      | 192.168.56.101 | Parrot          | [https://www.parrotsec.org/][6]

> **¹**: Esses Sistemas operacionais estão sendo utilizado no formato de OVAs (Open Virtualization Appliances), é a forma como o VirtualBox chama as imagens do sistema operacional utilizado.

> **²**: Link para o Download de cada distribuicao sugerida

Criação do Laboratório 
----------------------

Para ter acesso aos dumps do **CTF** deste laboratorio é necessário fazer o `git clone` desse repositório e realizar a descompactacao dos arquivos, conforme abaixo:

```bash
git clone https://github.com/joathamp/pentest_impacta.git
cd pentest_impacta/
```

Contato
----------------------

Entre em contato conosco.

Continue aprofundando seus conhecimentos, utilize este material para continuar praticando. 


Um forte abraco do Jota e do Vitor e de toda a equipe da Daryus, bons estudos e a gente se ve por ai:

* **Msc. Joatham Pedro**
  * **Perito Computacional**
  * **Pentester**
  * **Mestre em Sistemas e Computação** 
  * **Analista Sênior de Segurança da Informação - 4Linux** 
  * **Analista/Gerente de Seguranca - IFTO**   
  * **Instrutor MBA Cybersecurity Gov TI - FATEC Cuiabá**
  * **Instrutor  MBA Cybersecurity - IMPACTA**
  * **Instrutor Pos Graduacao Computação Forense - Daryus**
  * **Linux Professional Institute I** 
  * **Linux Professional Institute II** 
  * **Linux Professional Institute III - Security** 
  * **Datacenter Techical Specialist** 
  * **Novell Certified Linux Administrator (CLA)** 
  * **Computer Hacking Forensic Investigation - C|HFI** 
  * **Ec-Concil Incident Handler - EC|IH** 
  * **Certified Ethical Hacker - C|EH** 
  * **Exin Ethical Hacker - EXIN** 
  * **DevOps Essential Professional - DEPC** 
  * **Pos-Graduado em Redes de Computadores**
  * **Bacharel em Ciencia da Computacao**
  * **https://www.youtube.com/c/EaiQualteupapo**
  * **https://www.linkedin.com/in/joatham-pedro-44a3351b/**
  * **https://www.instagram.com/qualteupapo/**
  * **https://www.instagram.com/joatham.pedro/**

[1]: https://impacta.com.br/
[2]: https://git-scm.com/downloads
[3]: https://www.virtualbox.org/wiki/Downloads
[5]: https://www.kali.org/get-kali/
[6]: https://www.parrotsec.org/
