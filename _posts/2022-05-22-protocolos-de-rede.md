---
layout: article
title: Protocolos de redes de computadores
aside:
  toc: true
sidebar:
  nav: posts
tags:
- redes
- protocolos
- padrões
  
author: melissa
---

Olá! Sou a Melissa Costa.
Continue a seguir o caminho dos conhecimentos básicos sobre redes de computadores!


## Protocolos

O principal objectivo de qualquer rede é fornecer um método para comunicar e partilhar informações. Para que a comunicação seja possível, são necessários 3 elementos:

1. Emissor: a origem que emite a mensagem;

2. Receptor: o destinatário da mensagem;

3. Canal: o meio de transmissão da mensagem.


>Protocolos são regras ou acordos que direccionam a comunicação para que seja bem sucedida.

Os protocolos de rede definem aspectos como:
<li>O tempo e a velocidade em que os bits são transmitidos;</li>
<li>O tamanho da mensagem;</li>
<li>Formato e encapsulamento;</li>
<li>Codificação;</li>
<li>Padrão da mensagem.</li>

## Tipos de modelos de rede

Para descrever as funções que devem ocorrer em comunicações de rede bem.sucedida usam-se 2 tipos de modelo básico:

1.Modelo de protocolo: fornece toda a funcionalidade necessária para a comunicação na rede de dados, descrevendo as funções em cada camada.

2.Modelo de referência: ajuda a entender melhor a funções e os processos necessários para as comunicações na rede, sem especificar como cada função é realizada.

## Modelos em camada

A comunicação bem-sucedida entre hosts requer uma interação entre vários protocolos dispostos numa hierarquia em camadas, desde os protocolos de alto nível, até aos níveis inferiores.

Os modelos em camada ajudam a visualizar o funcionamento conjunto dos diversos protocolos, como a interação entre as camadas acima e abaixo, para possibilitar a comunicação de rede.
### TCP/IP
O modelo TCP/IP é um modelo de protocolo de internet criado no início dos anos 70. A sua estrutura  inclui 4 camadas:

4. Aplicação

3. Transporte

2. Internet

1. Acesso à rede

### OSI

O modelo OSI do projecto Open Systems Interconnection da ISO. É um modelo de referência usado para a elaboração de rede de daods, especificações de operação e resolução de problema, formado por 7 camadas:

>A diferença entre o modelo OSI e o  TCP/IP está no modo como se relacionam as camadas superiores e inferiores :

| OSI | TCP/IP | Função |
|--- |--- |--- |
| 7 - Aplicação | HTTP, SMTP, SNMP, FTP | Funções especialistas (transferência de arquivos, envio de e-mail, terminal virtual).|
| 6 - Apresentação | XDR, TLS | Formatação dos dados, conversão de códigos e caracteres (compressão e criptografia).|
| 5 - Sessão	| Estabelecimento da sessão TCP | Negociação e conexão com outros nós, analogia.|
| 4 - Transporte |	TCP, TFTP UDP, RTP, SCTP, SSL | Oferece métodos para a entrega de dados ponto-a-ponto.|
| 3 - Rede |	IP, ICMP, IPsec, RIP, OSPF, BGP, NAT, Roteador | Roteamento de pacotes em uma ou várias redes.|
| 2 - Enlace | 	MTP-2, ARP | Detecção de erros.|
| 1 - Física |	| Transmissão e recepção dos bits brutos através do meio físico de transmissão.|

## Padrões de internet

Os diferentes protocolos existentes utilizam variados padrões para a comunicação entre as várias redes do mundo inteiro.

> Padrão é um conjunto de regras que determinam como algo deve ser feito. <br> Os padrões de redee internet asseguram que todos os dispositivos implementem o mesmo conjunto de regras e protocolos

Ethernet é a tecnologia mais usada em redes locais. . Para aceder à LAN Ethernet os dispositivos usam uma Ethernet NIC-Network Interface Card(Placa de Interface de Rede), que tem uma emnfereço único incorporado na placa permanentemente, o endereço MAC- Media Access Control.

>O principal padrão Ethernet é o IEEE 802.3

Os padões de internet mais comuns como HTTP, HTML, Telnet, DNS, WWW(World Wide Web), FTP, entre outros,são definidos  seguindo um determinado modelo e fornecidos por vários disponibilizadores, tais como:

ISO - International Organization for Standardization (Organização Internacional para Padronização)

IEEE - Instituto de Engenheiros Eletricistas e Eletrônicos (pronuncia-se I-3-É) 

ICANN - Internet Corporation for Assigned Names and Numbers

IANA - Internet Assigned Numbers Authority ( Autoridade para Atribuição de Números da Internet) 

IETF - Internet Engineering Task Force(Força-Tarefa de Engenharia de Internet)

### Vantagens dos Padrões

<li>Facilitam o design;</li>
<li>Simplificam o desenvolvimento de produtos;</li>
<li>Promovem a concorrência;</li>
<li>Fornecem interconexões consistentes;</li>
<li>Facilitam o treinamento;</li>
<li>Oferecem mais opções de fornecedor aos clientes.</li>

## Conclusão

Este capítulo começou por discutir sobre os princípios da comunicação em uma rede: origem, destino e meio de transmissão. 

Foram introduzidos os Protocolos de rede e seus modelos. Nos modelos em camada, foram descritas as estruturas dos modelo OSI e TCP/IP e estabelecidas as devidas relações entre as suas camadas superiores e inferiores.

Por fim, conhecemos alguns padrões de internet como o IEEE 802.3, Telnet, WWW e HTML e seus disponibilizadores, tendo se ressaltado as vantages de se aquirir os padrões.

