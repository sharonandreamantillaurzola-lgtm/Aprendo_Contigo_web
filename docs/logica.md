# logica del negocio 
Aprendo Contigo
# Descripción: Aprendo Contigo es un emprendimiento educativo dedicado a crear materiales didácticos y recursos creativos que hacen del aprendizaje una experiencia divertida, significativa y adaptada a las necesidades de cada niño. Acompañamos a familias y docentes con herramientas que fortalecen el desarrollo de habilidades y el amor por aprender.
## FLUJO PRINCIPAL
INICIO
                    │
      Clic en la bandera verde
                    │
                    ▼
          Mostrar bienvenida
                    │
                    ▼
      Preguntar: "¿Cómo te llamas?"
                    │
                    ▼
      Guardar respuesta en "Nombre"
                    │
                    ▼
 Decir: "¡Hola, [Nombre]! Empecemos."
                    │
                    ▼
 Inicializar variables:
 Puntos = 0
 Aciertos = 0
 Errores = 0
                    │
                    ▼
      Repetir preguntas (16 preguntas)
                    │
                    ▼
 Mostrar una oración
 (Ejemplo: "It is a panda")
                    │
                    ▼
 Preguntar si el verbo es correcto
                    │
          ┌─────────┴─────────┐
          │                   │
      Respuesta           Respuesta
      Correcta            Incorrecta
          │                   │
          ▼                   ▼
 Decir "Well done!"      Decir "Incorrect!"
 Puntos +1               Errores +1
 Aciertos +1             (errores +1)
          │                   │
          └─────────┬─────────┘
                    │
                    ▼
      ¿Quedan preguntas?
            │
      Sí ───┴─── No
      │             │
      ▼             ▼
 Siguiente      Mostrar resultados
 pregunta            │
                     ▼
      Mostrar:
      • Puntos
      • Aciertos
      • Errores
                     │
                     ▼
      ¿Aciertos ≥ 7?
          │
    ┌─────┴─────┐
    │           │
   Sí          No
    │           │
    ▼           ▼
 "¡Ganaste!"  "Sigue practicando"
    │           │
    └─────┬─────┘
          │
          ▼
          FIN
# PSEUDOCODIGO
INICIO

Al presionar la bandera verde

Mostrar "¡Bienvenido!"
Preguntar "¿Cómo te llamas?"
Guardar la respuesta en la variable Nombre

Decir "Hola, " + Nombre + ". ¡Empecemos!"

Puntos ← 0
Aciertos ← 0
Errores ← 0

Para cada una de las 16 preguntas hacer

    Mostrar la oración
    Preguntar la respuesta

    Si la respuesta es correcta Entonces
        Mostrar "Well done!"
        Puntos ← Puntos + 1
        Aciertos ← Aciertos + 1
    Sino
        Mostrar "Incorrect."
        Errores ← Errores + 1
    Fin Si

Fin Para

Mostrar "Resultados"
Mostrar "Puntos: " + Puntos
Mostrar "Aciertos: " + Aciertos
Mostrar "Errores: " + Errores

Si Aciertos ≥ 7 Entonces
    Mostrar "¡Ganaste!"
Sino
    Mostrar "Sigue practicando."
Fin Si

FIN
# simulación Scratch 
nombre: Aprendamos Verbo To Be De una Manera Didactica
Hecho por: Sharon Mantilla, Isabella Torres y Amalia 