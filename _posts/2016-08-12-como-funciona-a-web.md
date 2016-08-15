---
layout: post
title: Como funciona a Web
cover: como-funciona-a-web.jpg
date:   2016-08-14 12:00:00
categories: posts
---
<br>

# --Internet--    

<br>
	
A internet e a web não são a mesma coisa. A internet é maior, mais velha e mais diversa.

Imagine como as **estradas** são conectadas em todo o mundo: pequenas ruas dentro de cidades que se transformam em vias regionais que se ligam a rodovias nacionais e internacionais. Você pode dirigir de sua casa até chegar em outra casa localizada em quase qualquer lugar nesse mundo.

A internet funciona do mesmo jeito. Mas ao invés de estradas, há **cabos**. Ao invés de casas, **computadores**. E ao invés de carros viajando na rede, há a **informação**.

Foi inventada em 1969 para conectar computadores nos EUA. Hoje, bilhões de dispositivos (incluindo computadores, laptops, smartphones, TVs, geladeiras...) estão interconectados.

## Cliente e servidor

Usualmente, uma conexão com a internet é estabelecida entre apenas **2** computadores:

* O que **tem** a informação (servidor)
* O que **obtem** a informação (cliente)

Um **cliente** é manifestado em várias formas:

* Um navegador Web (como o Chrome)
* Um cliente de email (como o Outlook)
* Um app de mensagens (como o Whatsapp)
* Um serviço de streaming de video (como o Netflix)

Cada um desses programas terá suas informações advindas de um **servidor**, onde algo é armazenado(um site, seus emails, mensagens, filmes). Embora programas clientes também enviem informações ao servidor, eles usualmente não as guardam, enquanto servidores sim.

Um servidor pode ser considerado um computador dedicado que está sempre conectado à internet, o qual tem como único propósito o de fornecer conteúdo.


> Embora alguns dispositivos conectados à internet possam ser clientes e servidores ao mesmo tempo, a maioria dos dispositivos que nós usamos são considerados **clientes**, por não fornecerem dados.

## Endereço IP  

Assim como toda casa possui um endereço postal único, a cada computador conectado à internet também é dado um **endereço IP**.

Um endereço IP usualmente é composto por uma combinação de 4 números: 
``` 69.171.230.68 ```

## Domínios

Embora endereços IP sejam úteis para computadores se comunicarem uns com os outros graças as suas singularidades, eles são difíceis de ser lidos e lembrados por nós seres humanos.

Foi por isso que os **domínios** foram criados em 1985. Eles associaram um endereço IP como ``` 69.171.230.68 ``` com um pedaço de **texto** como ``` facebook.com ```. Como resultado, ambos são **imodificáveis**: você pode ir para <http://69.171.230.68/> ou <http://facebook.com/> e acabará no mesmo lugar.







``` java
public class GameDAO
{
	public static ArrayList<Integer> queue = new ArrayList<>();
	public static int index = 0;
	
	public static void insertElement()
	{
		Random r = new Random();
		queue.add(r.nextInt(4));
	}
	
	public static boolean verifyAnswer(int answer)
	{	
		return queue.get(index) == answer ? true : false;
	}
}
```
