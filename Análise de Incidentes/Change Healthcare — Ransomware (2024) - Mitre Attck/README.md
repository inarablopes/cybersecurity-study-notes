# O que eu aprendi?

Ficha de Análise de Incidente · Aulas 01 e 02 · Módulo 1 (KODIE Academy · Cibersegurança 2.0)

Este README resume o que aprendi ao fazer a Ficha de Análise de Incidente, que trabalhou três formas diferentes de analisar um ataque cibernético: o Modelo CIA, a Cadeia de Ataque e o framework MITRE ATT&CK.

## O que essa atividade me ensinou, de forma geral

Aprendi que analisar um incidente de segurança não é só dizer "houve um vazamento" — é preciso decompor o ataque em camadas diferentes:

O que foi afetado (Modelo CIA)
Como o ataque progrediu passo a passo (Cadeia de Ataque)
Quais técnicas específicas o atacante usou, catalogadas por um padrão da indústria (MITRE ATT&CK)

Isso me mostrou que uma mesma notícia pode ser lida de vários ângulos técnicos, e que existe um vocabulário padronizado para descrever ataques — o que facilita a comunicação entre profissionais de segurança.
Professor deixou bem claro que a COMUNICAÇÃO É DE EXTREMA IMPORTÂNCIA, não adianta saber fazer e não conseguir explicar!

## O que aprendi sobre o Modelo CIA

A Parte 1 da ficha me fez entender que segurança da informação gira em torno de três pilares:

Confidencialidade — impedir acesso não autorizado
Integridade — impedir alteração indevida dos dados
Disponibilidade — garantir que o sistema continue acessível

O principal aprendizado aqui foi perceber que um incidente raramente afeta só um pilar de forma isolada — muitas vezes há sobreposição (ex.: um ransomware pode afetar disponibilidade e, se vazar dados, também confidencialidade).
Isso me ensinou a olhar para um incidente de forma mais completa, em vez de rotulá-lo com um único adjetivo genérico como "ataque hacker".

## O que aprendi sobre a Cadeia de Ataque

A Parte 2 me mostrou que um ataque não é um evento único, mas um processo com etapas:

Reconhecimento
Entrega
Exploração
Persistência
Exfiltração

O aprendizado mais importante foi perceber que cada fase representa uma oportunidade de defesa. Ou seja, um ataque bem-sucedido geralmente significa que várias camadas de proteção falharam em sequência — não apenas uma.
Isso muda a forma como penso em segurança: em vez de buscar "uma solução mágica", entendi a importância de ter controles em múltiplas etapas da cadeia.

## O que aprendi sobre o MITRE ATT&CK

Que assusta de primeira mas o importante é persistir!
E também a parte 3 foi a que mais me exigiu pesquisa, porque precisei consultar o site oficial (attack.mitre.org) para encontrar técnicas reais associadas ao incidente escolhido.

Aprendi que:

Existe uma base de dados pública e padronizada de táticas e técnicas de ataque, usada globalmente pela indústria de segurança.
Cada técnica tem um ID único (como T1566 para phishing), o que facilita a documentação e comparação entre incidentes diferentes.
Para cada técnica, o próprio MITRE já sugere mitigações catalogadas (com seus próprios IDs, como M1017), o que me ajudou a conectar "o problema" com "a solução recomendada pela comunidade".

Esse foi provavelmente o maior salto de aprendizado: perceber que existe uma linguagem técnica compartilhada entre analistas de segurança do mundo todo, e que não preciso "inventar" como classificar um ataque...
posso me apoiar em um padrão já validado.

## Como os três conceitos se conectam

O maior insight da atividade foi ver como as três partes se encaixam:

O Modelo CIA diz o que foi comprometido → a Cadeia de Ataque mostra em que momento o ataque teve sucesso → o MITRE ATT&CK nomeia exatamente qual técnica foi usada e qual mitigação teria ajudado.

Isso me ajudou a construir um raciocínio completo, do mais geral (pilares de segurança) para o mais específico (técnica catalogada com ID), o que é exatamente como analistas de segurança reais estruturam relatórios de incidentes.

## Principal takeaway

Antes dessa atividade, eu via notícias de vazamentos/ataques de forma superficial. Depois de aplicar esses três frameworks, percebi que consigo:

Identificar rapidamente (talvez não tão rapidamente assim) qual pilar de segurança foi violado;
Buscar e procurar uma técnica MITRE ATT&CK real e sua mitigação correspondente.
