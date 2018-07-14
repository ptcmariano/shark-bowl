Shark Bowl
===

O Fishbowl no modo hard
---

> O Shark bowl é um formato de evento/palestra inspirado no Fish Bowl. 
> Este repositório tem a intenção de documentá-lo afim de compartilha-lo com a comunidade.

### O que é
Um formato para eventos com número reduzido de público.

### Qual a motivação
Que o conteúdo atinja e seja gerado por todos os presentes (ou pelo menos sua maioria). 

### As Regras
* Cada um ao chegar (ou fazer checkin, ou se registrar ...) deve ser questionado sobre um assunto sobre o qual saiba falar ou que queira ver em uma discussão. 
 * É importante fazê-lo antes da abertura, com as pessoas chegando para que o "choque" as desarme e incentive a no mínimo iniciar uma discussão.
* Idealmente os participantes devem estar dispostos de maneira a todos verem todos, em uma roda, em formato U... o importante é que não se limite a visão, audição ou percepção de nenhum presente.
* Ao início define-se o tempo máximo de cada apresentação ou discussão. Idealmente não deve passar de 10 minutos e não ser menor de 5 minutos.
 *  Em um evento com 15 pessoas, de 2 horas de duração, divida 120 minutos por 15 participantes, acrescentando a cada participante um décimo de seu tempo para a troca de "vítima"
 *  Em php (sim, funciona :P):
```php
echo round(120 /* minutos */ / (15 /* participantes */ * 1.1)), " minutos para cada vítima";
``` 
* Randomize a lista gerada a partir dos inscritos. 
  * Uma dica é usar a [ferramenta de listas do random.org](http://www.random.org/lists/)
* Use um timer sonoro para cada apresentação/discussão
  * [O google pode ser um timer](https://www.google.com.br/?x=#safe=on&q=7+minute+timer) ;)
* Chame o primeiro "sorteado", inicie o timer e deixe que a pessoa se apresente (caso seja nova no grupo), apresente o tema escolhido e a motivação pela escolha do tema.
* Deixe a discussão fluir normalmente a partir dai até que se esgote o tempo do participante
* Repita os dois últimos passos até o evento acabar :D
* Importante: perguntas e comentários dos outros participantes durante um tema devem ser incentivadas, mas não permita que o evento torne-se um campo de guerra #fikdik
 

#### Termos de uso:
Use a vontade! 
Se achar um problema, ou tiver uma sugestão, por favor [abra uma Issue](duodraco/shark-bowl/issues/new) ou envie um Pull Request :D
