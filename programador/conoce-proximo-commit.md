---
layout: programador
title: Conoce tu próximo Commit
overview: true
author: Dan Bergh Johnsson
translator: Espartaco Palma
original: http://programmer.97things.oreilly.com/wiki/index.php/Know_Your_Next_Commit
---

Toqué a tres programadores en su hombro y les pregunté que estaban haciendo. "Estoy refactorizando este método", respondió el primero. "Estoy agregando algunos parámetros a esta actividad web". respondió el segundo. El tercero respondió: "Estoy trabajando en esta historia de usuario".

Podría ser que los primeros dos estaban dedicados en el detalle de su trabajo mientras el tercero estaba viendo la escena completa, y que el último tenía un mejor enfoque. Sin embargo, cuando pregunté sobre cuándo y a qué le harían commit, la escena cambió dramáticamente. Los primeros dos estaban bastante claros sobre qué archivos estarían involucrados y que esto estaría terminado en una hora o dos. El tercer programador respondió: "Oh, creo que estaré listo en unos días. Probablemente agregaré unas cuantas clases y quizás cambie de algún modo estos servicios".

Los primeros dos no carecían de una visión de la meta general. Habían seleccionado tareas que pensaron los llevaría a una dirección productiva, y que podría estar terminado en un par de horas. Una vez que hubieran terminado con esas tareas, seleccionarían una nueva característica o refactorización en la cual trabajar. Todo el código escrito era, por lo tanto, realizado con un propósito claro y limitado, con una meta realizable en mente.

Al tercer programador no había sido capaz de descomponer el problema y había trabajado en todos los aspectos al mismo tiempo. No tenía idea de cuánto le tomaría, básicamente estaba haciendo programación especulativa, esperando llegar a algún punto donde podría ser posible hacer un commit. Más probablemente, el código escrito al inicio de su larga sesión fue pobremente igualado a la solución que salió al final.

¿Qué harían los primeros dos programadores si sus tareas tomaran más de dos horas? Después de darse cuando que habían tardado mucho, lo más probable es que desecharían sus cambios, definirían tareas más pequeñas y volverían a empezar. El mantenerse trabajando sería una carencia de concentración y llevado el código especulativo al repositorio. En vez de ellos, los cambios serían desechados, pero mantendrían su visión.

El tercer programador podría seguir adivinando y tratando desesperadamente de realizar sus parches dentro de algo a lo que pudiera hacerle commit. Después de todo, no puedes tirar los cambios de código que has hecho -- eso sería trabajo perdido, ¿no es así?. Desafortunadamente, no desechar el código lleva a un código un poco extraño que carece de un propósito claro al entrar al repositorio.

En algún momento, incluso los programadores enfocados en el commit podrían no encontrar algo útil que piensen pueda ser terminado en dos horas. Entonces, irían directamente al modo especulativo, jugueteando con el código, y, por supuesto, desechando los cambios en el momento en que alguna idea los lleve a ese camino. Incluso esas sesiones de hacking aparentemente no estructuras tienen un propósito: aprender sobre el código y ser capaces de definir una tarea que sería constitutiva de un paso productivo.

Conoce tu próximo commit. Si no puedes terminar, tira tus cambios, entonces define una nueva tarea en la que creas con las ideas que has ganado. Haz experimentación especulativa donde sea necesario, pero no caigas en el modo especulativo sin darte cuenta. No mandes commit de conjeturas a tu repositorio.



