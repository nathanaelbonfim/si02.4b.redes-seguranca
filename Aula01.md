# Firewall

## O que é?
Uma forma de proteger o sistema, utilizando um programa ou hardware para
gerenciar os pacotes da rede.

## Firewall stateless
Filtra os pacotes de acordo com os dados de origem. 

## Proxy
Intermediário entre os usuários e os pacotes. Armazena a parte estática das
páginas em cache.
> Pode ser usado para criar um cache dos dados transmitidos.

> Descobriram que Proxy poderia fazer mais do que proteger a rede, mas também a
> criação de regras para realizar o recebimentos dos pacotes.

**Proxy transparente**: não precisa de senha.
**Proxy autenticado**: permite separar por grupo, restringir o acesso e etc.

### Firewall simples
**Bloqueia**: tudo que vem da rede externa.
**Libera**: tudo que sair e o que voltou de uma conexão de saída.


### Snort (1998) - IDS
IDS são ferramentas que analisam o comportamento da rede no período de **análise
ou aprendizado**. A partir daí, ele cria uma **linha de base**.

Quando ativado, qualquer comportamento na rede que saia do padrão é
automaticamente Bloqueada.

## IDS (Intrusion Detection System) vs IPS (Intrusion Prevention System)

**IDS**: Ferramentas de monitoramento para detectar ameaças na rede e motrar ao
operador.
> O IDS não toma ações por conta própria, só detecta.

**IPS**: Ferramenta para _ativamente_ bloqueia as ameaças conhecidas.
Atualizações automáticas.
> Ambos requerem o uso de uma base de dados para atulizar suas regras de
> detecçao e bloqueio.


## Tipos de firewall
Analisa uma lista de regras, vê o compatível e filtra os pacotes.

**Estático**: regras escrita e não adaptáveis.
> Ex: se você liberou um domínio com IP, só libera para aquele.

**Dinâmica**: as regras se adaptam de acordo com as regras anteriores.
> Ex: se liberou um domínio, as dependências de CND, imagens e etc também são
> liberadas.

## Proxy services
É um firewall de aplicação. Eles impedem a comunicação direta entre origem e
destino.

> O marco civil da internet proibiu os provedores de guardarem os logs
> completos.
>
> **Provedor**: guarda um log dos endereços de IP que os usuários usaram em cada
> dia.
>
> **Site**: um log de quais endereços acessaram o site.


## Firewall e suas vantagens
No mundo atual, é necessário ter firewall.
