# Proyecto_Final
Proyecto de graduación relacionado con el cambio climático
# Proyecto: BotEcoShow

## Idea
Un Bot de Discord que a una hora programable del día (dos días a la semana) empieza un concurso en el servidor sobre temas ecologicos simples extraídos de API's ambientales, donde el que se desarrolle mejor en un periodo de 1hs de preguntas consecutivas obtendrá puntos para una tierlist. Al terminar el periodo de concurso, se les dará a los concursantes las respuestas y explicará como aplicarlas.

## Tipo de proyecto
Bot de Discord + API de noticias ambientales + pyttsx3.

## Tecnologías
- Python
- discord.py
- Requets (para consumir API's)
- SQLite (para guardar progreso de usuarios)
- pyttsx3 (para ajustar el habla con los usuarios del entorno)

## Problema que resuelve
La gente usualmente no se interesa en los temas ambientales, para eso el Bot se volvería algo más cercano a los usuarios, introduciendo un ambiente de competencia y que potencialmente, y con carisma programada, induciría curiosidad a los usuarios para investigar con un propósito mayormente competitivo.

Definan su idea respondiendo a estas preguntas:

¿Qué problema relacionado con el cambio climático resuelve?
    Resuelve el desinterés de los usuarios al introducir un tema así de importante como un concurso o competición.
¿A quién ayuda o beneficia?
    Ayuda a la gente más joven,  que muchas veces se ve apartada de estos temas por ser un publico difícil para llegar o ser considerados muy jóvenes para temas importantes.
¿Qué tecnologías van a usar de las que ya conocemos?

¿Cómo funcionará en terminos generales? (ej: un bot que da consejos ecológicos, una web que calcula la huella de carbono, un analizador de textos sobre noticias ambientales, etc.)
    Un Bot de Discord que, a una hora programada, 2 días a la semana iniciará un concurso de preguntas y respuestas de 1 hora en el que se darán puntos por las respuestas correctas al final y se explicaran los temas del concurso. Los puntos se guardaran para una tierlist que al final de un mes se podrá reiniciar el mensual pero se mantendrán almacenados los puntos de cada usuario y al final del año se darán los resultados anuales.
