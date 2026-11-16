# Proyecto de Trabajo de Investigación – Versión corregida

**Integrante:** Campos Mejia, Cesar Antonio (U19208325)
**Docente:** Chávez Moreno, Segundo Reynaldo (C24983)
**Ciclo:** 2026-II

## Cómo leer este documento

Cada párrafo empieza con una etiqueta que indica qué se hizo con él respecto del APF3:

| Etiqueta | Significado |
|---|---|
| **[SIN CAMBIOS]** | Se mantiene igual que en el APF3 |
| **[MODIFICADO]** | Se conserva la idea, pero se corrigió la redacción, las citas o parte del contenido |
| **[REEMPLAZADO]** | El texto anterior se sustituyó por uno nuevo con otro enfoque |
| **[AGREGADO]** | Contenido que no existía en el APF3 |
| **[ELIMINADO]** | Contenido que se quitó; se indica el motivo, pero el texto no aparece |
| **[COMPLETAR]** | Dato que debe añadir el autor |

Antes de pegar el texto en el Word, borra las etiquetas. La tabla de control de cambios está al final.

---

## TÍTULO

**[MODIFICADO]** Aplicación web basada en analítica predictiva y microaprendizaje para fortalecer la autoeficacia digital del personal de mesa de ayuda del área de TI

*Antes:* Propuesta de una aplicación web basada en analítica predictiva para mejorar la autoeficacia digital en el personal del área de TI.

---

## RESUMEN

**[AGREGADO]** (286 palabras, sin citas)

En las áreas de Tecnologías de la Información, el personal puede mostrar inseguridad al adoptar nuevas plataformas, lo que se refleja en escalamientos frecuentes, demoras y reapertura de incidentes. Sin embargo, estas áreas registran el desempeño del servicio, pero rara vez miden la confianza del personal en su propia capacidad digital, y la capacitación suele ser extensa, homogénea y posterior a los problemas. Este proyecto tiene como objetivo determinar la contribución de una aplicación web basada en analítica predictiva y microaprendizaje al fortalecimiento de la autoeficacia digital del personal de mesa de ayuda del área de TI, así como su relación con el desempeño operativo en la gestión de incidentes. Para ello, se propone un estudio cuantitativo, de tipo aplicado y diseño preexperimental con medición antes y después en un solo grupo, conformado por los analistas de la mesa de ayuda de una organización. Se prevé desarrollar un prototipo web que integre un modelo de regresión logística, microcontenidos audiovisuales y retroalimentación, y aplicarlo en un piloto de cinco semanas. La autoeficacia digital se medirá con un cuestionario adaptado y validado, aplicado antes y después del piloto. El desempeño operativo se obtendrá de los registros del sistema de gestión de servicios de TI mediante el tiempo medio de resolución, la tasa de escalamiento, la tasa de reapertura y el tiempo a la primera acción. Los cambios se compararán con la prueba de Wilcoxon y la relación entre ambas variables se examinará con la correlación de Spearman. El análisis permitirá establecer si el uso de la aplicación se asocia con un aumento de la autoeficacia digital y si ese aumento se acompaña de mejoras observables en el servicio, lo que aportará criterios para orientar futuras implementaciones en organizaciones.

---

## 1. PROBLEMA DE INVESTIGACIÓN

**[SIN CAMBIOS]** Los departamentos de TI proporcionan una variedad de servicios, desde identidades digitales y Help Desk hasta herramientas y servicios que componen la infraestructura interna de la empresa. El personal puede sentirse inseguro y temeroso de confiar completamente en las nuevas plataformas de TI de la empresa [1], [2]. Por ejemplo, el personal puede sentir que es mejor posponer la automatización de un proceso comercial, o que conviene esperar una capacitación presencial antes de usar una nueva plataforma de TI de la empresa [1], [4].

**[SIN CAMBIOS]** La actitud del personal hacia las nuevas plataformas de TI de la empresa puede deberse a una falta de confianza del personal en el uso de la TI. La autoeficacia digital puede definirse como la creencia en la propia capacidad para hacer uso de las plataformas de TI de la empresa [2], [6]. Muchas empresas ya implementan programas de gestión del talento para mejorar sus operaciones comerciales [3]. El uso de herramientas de inteligencia empresarial de autoservicio para identificar lagunas de autoeficacia digital puede ser un buen punto de partida para prevenir incidentes y mejorar las operaciones comerciales [3], [5], [7].

**[AGREGADO]** Conviene distinguir la autoeficacia digital del desempeño operativo. La primera es una creencia sobre la propia capacidad; el segundo es el resultado observable del trabajo, como el tiempo que toma resolver un incidente o la frecuencia con que se escala. Las áreas de TI registran el desempeño en sus sistemas de gestión de servicios, pero casi nunca miden la autoeficacia, de modo que una pérdida de confianza solo se advierte cuando ya afecta al servicio.

**[MODIFICADO]** Existe una brecha creciente entre el ritmo de los cambios de TI y de negocio y el ritmo de la formación y el aprendizaje [4], [9]. La participación en actividades formativas es medible y permite identificar a los aprendices en riesgo [5], [7], [8]. Esto permitiría al área de TI pasar de evaluar la competencia del personal después de que se entrega el servicio a hacerlo durante su uso, identificar y abordar las barreras, y medir el progreso en los módulos. Actualmente, los servicios se enfocan en programas de formación de larga duración o en credenciales de corta duración, y no integran la analítica de aprendizaje [1], [2].

*Cambio:* se unieron dos párrafos cortos, se aclaró de qué participación se habla y se corrigió el formato de citas ("[1, 2]" pasa a "[1], [2]").

**[MODIFICADO]** En cuanto a la analítica de aprendizaje, la literatura reporta otras barreras: la evaluación reactiva del desempeño, la formación homogénea, la falta de integración entre los datos de formación y los de operación, y el uso de formatos largos y complejos en programas de alto riesgo [3]–[5], [9]. Además, cuando la organización no ofrece apoyo formativo, el aprendizaje entre pares se vuelve la vía predominante [1], [2]. Estas barreras influyen en el diseño e integración de tecnologías, especialmente en el campo de la TI organizacional [5], [6].

*Cambio:* "Hablando de analítica de aprendizaje" pasa a "En cuanto a la analítica de aprendizaje"; se simplificó la redacción y se ajustaron las citas al formato IEEE.

**[SIN CAMBIOS]** Delimitando el problema de investigación, se formulan las siguientes interrogantes.

### Problema principal

**[MODIFICADO]** ¿De qué manera contribuye una aplicación web basada en analítica predictiva y microaprendizaje al fortalecimiento de la autoeficacia digital del personal de mesa de ayuda del área de TI, y cómo se relaciona dicho fortalecimiento con su desempeño operativo?

### Problemas secundarios

**[REEMPLAZADO]**

1. ¿Qué instrumentos e indicadores permiten medir la autoeficacia digital del personal de TI y su desempeño operativo en la gestión de incidentes?
2. ¿Qué modelo de analítica predictiva permite identificar de forma anticipada al personal con posibles brechas de autoeficacia digital a partir de registros operativos y de uso?
3. ¿Cómo deben integrarse el microaprendizaje, los contenidos audiovisuales y la retroalimentación inteligente en una aplicación web que atienda las brechas identificadas, y con qué criterios puede evaluarse funcionalmente su diseño?
4. ¿Qué cambios se producen en la autoeficacia digital y en el desempeño operativo del personal tras el uso de la aplicación web, y qué relación existe entre ambos?

**[MODIFICADO]** En este sentido, la presente investigación se inscribe en la línea "Aplicaciones TIC, electrónicas, robóticas y de telecomunicaciones para la competitividad, salud, educación y seguridad ciudadana", con el propósito de diseñar y evaluar una aplicación web que integre analítica predictiva y TIC al servicio del fortalecimiento de capacidades humanas en las organizaciones. Su aporte a la competitividad consiste en contar con personal de TI más autónomo y eficaz en entornos digitales.

*Cambio:* se eliminó la frase sobre "la equidad y la calidad del sistema educativo nacional" y "los futuros profesionales peruanos", porque se refería a otra población distinta de la del estudio.

**[MODIFICADO]** Asimismo, el proyecto se vincula con la competencia del egresado "Sistemas informáticos: conceptualiza, planifica, provee y evalúa sistemas informáticos centrados en las necesidades de sus clientes, con un enfoque en soluciones y con una clara línea comercial". Esta competencia exige conceptualizar y planificar una solución basada en arquitectura de software, analítica de datos y evaluación funcional, orientada a necesidades reales de capacitación en TI. El desafío no es solo técnico, sino también estratégico y humano, pues la solución debe ayudar al personal a confiar en sus propias capacidades para resolver problemas tecnológicos de manera autónoma.

*Cambio:* se eliminó la referencia a "educación virtual equitativa e inclusiva" y a "futuros estudiantes", por la misma razón que en el párrafo anterior.

---

## 2. OBJETIVO GENERAL Y ESPECÍFICOS

### Objetivo general

**[REEMPLAZADO]** Determinar la contribución de una aplicación web basada en analítica predictiva y microaprendizaje al fortalecimiento de la autoeficacia digital del personal de mesa de ayuda del área de Tecnologías de la Información, así como su relación con el desempeño operativo en la gestión de incidentes.

*Antes:* "…mediante la identificación anticipada de brechas, la personalización de contenidos de microaprendizaje y el seguimiento del desempeño, a partir del diseño arquitectónico de la solución propuesta". Se quitó "a partir del diseño arquitectónico" porque la metodología incluye un piloto con mediciones reales, y se añadió la relación con el desempeño, como pidió el docente.

### Objetivos específicos

**[REEMPLAZADO]**

1. Identificar los instrumentos e indicadores que permitan medir la autoeficacia digital del personal del área de TI y su desempeño operativo en la gestión de incidentes.
2. Determinar un modelo de analítica predictiva que permita identificar de forma anticipada al personal con posibles brechas de autoeficacia digital a partir de registros operativos y de uso.
3. Diseñar y evaluar funcionalmente la integración de microaprendizaje, contenidos audiovisuales y retroalimentación inteligente en una aplicación web orientada a atender las brechas identificadas.
4. Evaluar los cambios en la autoeficacia digital y en el desempeño operativo del personal antes y después del uso de la aplicación web, así como la relación entre ambos.

---

## 3. JUSTIFICACIÓN

**[SIN CAMBIOS]** La investigación se apoya en cuatro frentes: impacto social y organizacional, viabilidad tecnológica, formación del egresado y aporte a la línea UTP de TIC.

**[MODIFICADO]** En las empresas, casi todo servicio digital pasa por TI. Si quien opera una herramienta crítica duda de sí mismo, el riesgo no aparece en un inventario: se ve en escalamientos, tiempos de respuesta y rechazo a los cambios. Ya existen precedentes del uso de historiales de formación, desempeño y metadatos de carrera con analítica predictiva para tomar decisiones de talento [3]. Combinar señales similares con una medición directa de la autoeficacia digital permitiría intervenir antes de que caiga la calidad del servicio.

**[MODIFICADO]** En lo tecnológico, hoy es viable combinar analítica de aprendizaje, modelos predictivos y una interfaz web en una misma solución. La propuesta no sería un repositorio de cursos, sino un sistema que lea datos de uso y devuelva alertas y microcontenidos al analista en el momento en que los necesita.

*Cambio:* se quitaron las afirmaciones con citas [4], [5] y [8], porque ahora se desarrollan en el estado del arte y repetirlas aquí resultaba redundante.

**[MODIFICADO]** En lo académico, el trabajo cruza ingeniería de software, ciencia de datos y diseño formativo, en línea con la competencia de Sistemas informáticos. Se planifica desarrollar un prototipo y aplicarlo en un piloto acotado en el que se medirán por separado la autoeficacia digital y el desempeño operativo del personal, para saber no solo si la herramienta funciona, sino si realmente fortalece la confianza de quienes la usan.

**[MODIFICADO]** Se esperan cuatro aportes: un cuestionario de autoeficacia digital adaptado al personal de TI; evidencia sobre la relación entre esa autoeficacia y el desempeño en la gestión de incidentes; una base para pilotos o implementaciones futuras en organizaciones; y una contribución a la línea UTP de TIC orientadas a la competitividad organizacional.

---

## 4. REVISIÓN DE LA LITERATURA ACTUAL O ESTADO DEL ARTE

**[MODIFICADO]** La revisión se realizó sobre artículos publicados en revistas indexadas en los campos de la autoeficacia digital, la analítica de aprendizaje y la capacitación corporativa basada en TIC. Se consultaron las bases **[COMPLETAR: bases usadas en tu RSL, por ejemplo Scopus, SciELO, Redalyc y Dialnet]** con términos como "autoeficacia digital", "analítica de aprendizaje", "modelos predictivos", "microaprendizaje" y "capacitación corporativa", y se priorizaron las publicaciones de **[COMPLETAR: periodo, por ejemplo 2020–2026]**. Se incluyeron estudios primarios y revisiones que abordaran la capacitación o la interacción con tecnologías digitales, y se descartaron aquellos cuyo resumen no permitía valorar estos criterios. Los trabajos seleccionados se organizaron en cuatro ejes para establecer qué se conoce y qué aspectos siguen pendientes en el caso del personal de TI de una organización.

### 4.1 Panorama

**[MODIFICADO]** La literatura revisada se agrupa en tres líneas de trabajo. La primera estudia la autoeficacia y la competencia digital, entendidas respectivamente como la creencia en la propia capacidad para usar tecnologías y el dominio efectivo de ellas [1], [2], [6]. La segunda corresponde a la analítica de aprendizaje y a los modelos predictivos, que emplean datos académicos, conductuales y de interacción para anticipar el rendimiento o el abandono [5], [7], [8], [14]. La tercera aborda la integración de las TIC en la capacitación corporativa, con atención a la experiencia de usuario, el microaprendizaje y la evaluación de plataformas formativas [4], [9], [13]. Otros trabajos amplían el concepto hacia la alfabetización digital y mediática, que sitúa el uso de la tecnología en un marco más crítico [10], [11].

**[MODIFICADO]** La mayor parte de esta producción procede del ámbito educativo: estudiantes universitarios, docentes y profesionales de la orientación. En el entorno corporativo, la investigación se ha centrado en la introducción de sistemas TIC y en las actitudes de los usuarios hacia las estrategias de capacitación [4], mientras que el personal de TI apenas aparece como población de estudio. Esta ausencia es relevante, porque las dudas de quienes administran y dan soporte a las plataformas de una organización repercuten directamente en la continuidad del servicio.

### 4.2 Análisis temático

#### 4.2.1 Autoeficacia digital

**[REEMPLAZADO]** Los estudios coinciden en que la formación recibida condiciona la confianza con que las personas usan las TIC. En profesionales de la orientación, la formación en TIC se vincula con el uso que hacen de estas herramientas en su práctica [1], y en estudiantes universitarios maduros, un grupo que llega a los entornos digitales con trayectorias formativas diversas, se ha analizado la autoeficacia en el uso de TIC como condición para su desempeño académico [2]. Ambos trabajos, junto con [6], permiten distinguir entre saber utilizar una tecnología y sentirse capaz de emplearla para resolver una tarea: una persona puede dominar una herramienta y, aun así, dudar cuando se enfrenta a situaciones imprevistas.

**[MODIFICADO]** Esa confianza no es homogénea. En docentes de educación superior, la relación entre competencia digital y autoeficacia varía según la edad y el género [6], mientras que en estudiantes de ciencias que investigan en línea las emociones intervienen en la percepción de la propia capacidad [12]. Los factores psicológicos, sociales y demográficos explican, por tanto, parte de las diferencias en la autoeficacia digital entre personas con una formación similar.

**[MODIFICADO]** En cuanto a su medición, los trabajos de este eje evalúan la autoeficacia mediante cuestionarios de autoinforme aplicados a los participantes [2], [6]. Este enfoque es coherente con instrumentos de referencia como la escala de autoeficacia computacional de Compeau y Higgins, que mide la confianza de la persona para completar tareas con tecnología en distintas condiciones de apoyo [15]. Ninguno de estos estudios, sin embargo, aplica este tipo de instrumentos al personal de TI.

#### 4.2.2 Analítica predictiva

**[MODIFICADO]** Los sistemas de gestión de recursos humanos almacenan información sobre la formación, las evaluaciones, el desempeño y la progresión profesional del personal. En gestión del talento, [3] muestra que integrar estos datos y sus metadatos con analítica predictiva puede apoyar decisiones estratégicas como la promoción o la retención. En el ámbito académico, [5] propone modelos multidimensionales que combinan variables académicas, conductuales y de interacción digital para predecir el rendimiento, y [8] estudia de forma longitudinal la relación entre la analítica de aprendizaje y la retención en educación superior virtual. Por su parte, [7] aplica la analítica de enseñanza y aprendizaje en cursos de programación, un contexto cercano a las tareas técnicas del personal de TI.

**[MODIFICADO]** Desde una perspectiva metodológica, [14] describe cómo la ciencia de datos y el aprendizaje automático permiten construir modelos predictivos, y destaca que su utilidad depende de la calidad de los datos disponibles. En conjunto, los estudios coinciden en que combinar varias fuentes de datos mejora la capacidad de anticipación frente a los enfoques basados en una sola variable [5], pero difieren en su propósito: los trabajos educativos predicen rendimiento o abandono, mientras que [3] se orienta a decisiones de talento. Ninguno utiliza la predicción para anticipar brechas de autoeficacia.

#### 4.2.3 Microaprendizaje y retroalimentación

**[MODIFICADO]** En la formación corporativa, [4] evalúa un modelo de aprendizaje centrado en el usuario que integra TIC y experiencia de usuario, y concluye que la capacitación gana eficacia cuando el diseño parte de las necesidades de quien aprende. Por su parte, [9] propone un modelo pedagógico de formación basada en microaprendizaje y apoyado en ontologías, que organiza el contenido en unidades breves y relacionadas entre sí. Ambos trabajos se alejan de los programas extensos y de la certificación documental voluminosa, y favorecen unidades cortas que reconocen el logro formativo de manera progresiva.

**[MODIFICADO]** Esta orientación responde a un problema práctico. Los formatos tradicionales, como un módulo de varios meses en un sistema ERP o una capacitación anual en ciberseguridad, encajan mal con el ritmo del trabajo en TI, donde la necesidad de aprender surge durante la operación o justo después de un error. Por ello, el microaprendizaje no consiste en fragmentar un documento extenso, sino en ofrecer contenidos breves, en el formato más conveniente para el usuario y ajustados a su ruta de aprendizaje [4], [9].

**[MODIFICADO]** La retroalimentación inteligente complementa este enfoque mediante reglas o modelos que indican al usuario en qué se equivocó y cómo ha evolucionado respecto de sus intentos anteriores. Para que resulte útil, debe ser oportuna y pertinente [9].

#### 4.2.4 Evaluación de plataformas formativas

**[MODIFICADO]** En el análisis longitudinal de plataformas y aplicaciones educativas digitales, [13] considera dimensiones como el contenido educativo, la tecnología y la pedagogía, y plantea que la evaluación debe integrarse desde el diseño para anticipar cómo se articularán los componentes de una plataforma antes de su implantación. Sus criterios, sin embargo, se formularon para la educación infantil, por lo que requieren adaptarse para valorar una aplicación orientada a la capacitación de personal técnico.

### 4.3 Balance crítico

**[AGREGADO]** La evidencia revisada permite sostener tres ideas. La autoeficacia digital se distingue de la competencia y depende de factores formativos, demográficos y emocionales [2], [6], [12]. Los modelos que combinan varias fuentes de datos ayudan a anticipar riesgos de rendimiento [5], [8]. Y el microaprendizaje acompañado de retroalimentación oportuna favorece una capacitación más eficiente en entornos corporativos [4], [9].

**[MODIFICADO]** Estas conclusiones, sin embargo, tienen un alcance limitado. Casi todos los estudios sobre autoeficacia se realizaron con estudiantes, docentes u orientadores [1], [2], [6], [12], y la investigación sobre el personal de TI fuera del ámbito educativo es escasa. Del mismo modo, los modelos predictivos se han validado sobre todo con datos académicos [5], [7], [8], y su traslado a las organizaciones todavía es incipiente [3]. A ello se suma un riesgo propio de estos modelos: cuando el usuario no puede examinar su razonamiento, existe la posibilidad de que el sistema premie conductas que solo aparentan una mejora, lo que favorece la elección de técnicas interpretables.

**[MODIFICADO]** Tampoco se identificaron estudios que empleen métricas de mesa de ayuda, como el tiempo de resolución o la tasa de escalamiento, como evidencia de autoeficacia digital. Estas métricas reflejan el desempeño operativo, que puede verse influido por la autoeficacia, pero también por la carga de trabajo o la complejidad de los incidentes. Por ello, no deberían interpretarse como una medida directa del constructo, sino como un resultado cuya relación con la autoeficacia todavía debe comprobarse.

**[AGREGADO]** Por último, la literatura aborda los componentes por separado. Detectar a una persona en riesgo es posible con los modelos disponibles, pero no se encontraron propuestas que integren en un mismo sistema la captura de eventos, la predicción, la retroalimentación y el contenido formativo para el personal de TI.

### 4.4 Fundamentación

**[MODIFICADO]** La producción científica en cada componente es abundante; lo que falta es su integración en un mismo flujo dentro del contexto organizacional de TI. La Tabla 1 resume, para cada aspecto, la evidencia disponible, el vacío identificado y la orientación que adopta esta investigación.

**Tabla 1.** Síntesis de vacíos identificados en la literatura **[MODIFICADO: se añadieron citas, una fila nueva y se actualizó la orientación]**

| Aspecto | Evidencia de la literatura | Vacío identificado | Orientación de la investigación |
|---|---|---|---|
| Autoeficacia digital | Se relaciona con la competencia digital, la formación y factores personales; se mide con cuestionarios de autoinforme [1], [2], [6], [12], [15] | Poca evidencia en personal de TI | Medición de la autoeficacia digital del personal de mesa de ayuda con un cuestionario adaptado |
| Analítica predictiva | Modelos multidimensionales en educación y gestión del talento [3], [5], [7], [8], [14] | No se orienta a anticipar brechas de autoeficacia | Modelo interpretable que alerte sobre posibles brechas a partir de registros operativos y de uso |
| Microaprendizaje y retroalimentación | Eficacia en la formación corporativa centrada en el usuario [4], [9] | Integración limitada con la analítica predictiva | Integración de alertas, microcontenidos y retroalimentación en una aplicación web |
| Evaluación de plataformas | Dimensiones de contenido, tecnología y pedagogía [13] | Criterios generales, no específicos para TI | Criterios funcionales adaptados al diseño propuesto |
| **[AGREGADO]** Desempeño operativo | Métricas de rendimiento usadas en educación y gestión del talento [3], [5] | No se ha relacionado con la autoeficacia en mesa de ayuda | Análisis de la relación entre los cambios en autoeficacia y en desempeño |

**[REEMPLAZADO]** A partir de esta revisión, se identifica como aspecto pendiente la ausencia de propuestas que integren la medición de la autoeficacia digital, la predicción de brechas y el microaprendizaje en una misma solución dirigida al personal de TI, así como la falta de evidencia sobre la relación entre esa autoeficacia y el desempeño observable en la gestión de incidentes. Por ello, la presente investigación se propone determinar la contribución de una aplicación web basada en analítica predictiva y microaprendizaje al fortalecimiento de la autoeficacia digital del personal de mesa de ayuda y su relación con el desempeño operativo.

**[ELIMINADO]** Párrafo "La flexibilidad del personal de TI para cambiar y adaptarse…": casi no tenía citas y trataba la gestión del cambio, que no forma parte del problema.

**[ELIMINADO]** Párrafos "Existen numerosos métodos…", "Hay muchas oportunidades de reciclaje…" y "La tecnología que actualmente está disponible…": estaban en primera persona, hablaban de "clientes", mencionaban el pensamiento de diseño (que no figura en la metodología) y presentaban como hecho algo que aún no se ha investigado.

---

## 5. METODOLOGÍA

**[REEMPLAZADO]** Para determinar la contribución de la aplicación web al fortalecimiento de la autoeficacia digital del personal de mesa de ayuda, se propone un diseño preexperimental con medición antes (M₁) y después (M₂) en un mismo equipo, ya que no se dispone de un grupo de comparación equivalente. En cada momento se medirán dos variables distintas: la autoeficacia digital, mediante un cuestionario de autoinforme, y el desempeño operativo, mediante cuatro indicadores extraídos del sistema de gestión de servicios de TI (ITSM). Esta distinción permite evaluar el constructo de forma directa y, a la vez, examinar si sus cambios se acompañan de mejoras observables en el servicio. A continuación se presentan el enfoque y el diseño; la población, las variables y los instrumentos; los procedimientos por objetivo; las fases de ejecución; y las consideraciones éticas y de viabilidad.

### 5.1 Enfoque, tipo, alcance y diseño

**[MODIFICADO]** La investigación tendrá un enfoque cuantitativo, ya que analizará puntajes de autoeficacia e indicadores numéricos de desempeño antes y después de incorporar la aplicación web. Será de tipo aplicado, porque busca responder a un problema concreto del área de TI: la falta de mecanismos para identificar a tiempo las brechas de autoeficacia digital y atenderlas con capacitación oportuna. La construcción de la herramienta seguirá los principios de la ciencia del diseño, que exigen detallar su arquitectura y evaluarla frente a criterios definidos antes de llevarla a un contexto real.

**[REEMPLAZADO]** El alcance será explicativo, pues se pretende determinar si el uso de la aplicación se asocia con un aumento de la autoeficacia digital. Siguiendo la distinción planteada en el estado del arte, la autoeficacia se entenderá como la confianza de la persona en su capacidad para usar herramientas digitales en sus funciones [2], [6], y el desempeño operativo, como el resultado observable de su trabajo con los incidentes. La primera se medirá con un cuestionario; el segundo, con los registros del ITSM. El desempeño no se interpretará como una medida de la autoeficacia, sino como una posible manifestación de ella, que también puede responder a otros factores, como la carga de trabajo o la complejidad de los casos.

*Antes:* "La autoeficacia digital no se evaluará mediante escalas psicométricas… Los cambios observados… se atribuirán al dominio que acompaña a la autoeficacia digital". Este era el punto principal que observó el docente.

**[MODIFICADO]** Se aplicará un diseño preexperimental con preprueba y posprueba en un solo grupo (G – M₁ – X – M₂). G es el equipo de mesa de ayuda del área de TI. M₁ comprende el cuestionario de autoeficacia, aplicado justo antes de la intervención, y los indicadores de desempeño de los tres meses previos. X es el uso de la aplicación web durante un piloto de cinco semanas: una de adaptación y cuatro de operación estable. M₂ comprende la segunda aplicación del cuestionario al cierre del piloto y los indicadores del mes de operación estable, calculados con las mismas reglas que en M₁.

**[SIN CAMBIOS]** El diseño responde a las condiciones de comparación disponibles. En un área de TI, en general, solo hay un equipo en el cual se puede introducir la solución; no existe un segundo grupo equivalente ni es posible asignar aleatoriamente a los analistas, condiciones que requerirían un diseño experimental o cuasiexperimental. El diseño seleccionado permite obtener evidencia antes y después para el mismo equipo.

### 5.2 Población, variables e instrumentos

**[MODIFICADO]** La población estará conformada por el personal de TI de una organización que trabaja en la mesa de ayuda. Dado el tamaño habitual de estos equipos, se trabajará con todos los analistas disponibles que hayan atendido incidentes durante el periodo de M₁, permanezcan en el equipo durante el piloto y acepten participar. La unidad de análisis será el analista, y las fuentes de datos serán sus respuestas al cuestionario y los tickets que haya atendido, agrupados por analista y mes.

**[REEMPLAZADO]** La variable independiente es el uso del ciclo formativo de la aplicación web, que integra analítica predictiva, microaprendizaje y retroalimentación. La variable dependiente principal es la autoeficacia digital del personal, medida con el cuestionario. La variable dependiente complementaria es el desempeño operativo en la gestión de incidentes, medido con cuatro indicadores del ITSM. Los registros operativos cumplen además una segunda función: alimentan el modelo predictivo que estima qué analistas podrían presentar brechas de autoeficacia, y en ese papel actúan como predictores, no como resultado del diseño.

**[AGREGADO]** La autoeficacia digital se medirá con un cuestionario de autoinforme (MT-4), adaptado de la escala de autoeficacia computacional de Compeau y Higgins [15] y de los instrumentos empleados en estudios previos sobre autoeficacia en el uso de TIC [2], [6]. Los ítems se ajustarán a tareas propias de la mesa de ayuda, como diagnosticar un incidente con una herramienta nueva, documentar una solución o resolver un caso sin escalarlo, y se responderán en una escala tipo Likert. Antes de su aplicación, el cuestionario será revisado por tres expertos y probado con un grupo reducido de analistas ajenos al piloto; su consistencia interna se estimará con el coeficiente alfa de Cronbach.

**[MODIFICADO]** El desempeño operativo se medirá con cuatro indicadores que el ITSM registra antes de que exista la aplicación, lo que permite calcularlos en M₁ y repetir el cálculo en M₂ con las mismas reglas. El tiempo medio de resolución (T-01) es el promedio mensual, por analista, del tiempo transcurrido entre la apertura y el cierre de sus tickets; un valor alto y sostenido puede indicar demoras o casos que exigieron mucho trabajo. La tasa de escalamiento (T-02) es el porcentaje de tickets que el analista transfiere a otro nivel o especialista, y su aumento sugiere menor autonomía para resolver con los procedimientos y herramientas disponibles. La tasa de reapertura (T-03) es el porcentaje de tickets cerrados que se reabren en el mes, lo que puede revelar soluciones provisionales o cierres poco seguros. El tiempo a la primera acción (T-04) mide cuánto tarda el analista en registrar su primera actualización desde la apertura del ticket, y complementa a T-01, que mide el tiempo total hasta el cierre.

*Cambio:* se unieron los dos párrafos sobre los indicadores, se quitaron las repeticiones de T-03 y se eliminaron las citas [5], [7] y [14], porque esas fuentes no tratan métricas de mesa de ayuda (ver el balance crítico).

**[MODIFICADO]** La recolección combinará dos técnicas: la encuesta, para la autoeficacia, y el análisis de registros, para el desempeño. Para los indicadores no se usará encuesta, porque son métricas de proceso que el ITSM ya almacena, y recogerlas por autoinforme solo añadiría sesgo.

**[MODIFICADO]** Los instrumentos de registro son cuatro. La matriz de definición de indicadores (MT-1) establece la definición, la unidad, la fórmula y los filtros de cada indicador para asegurar el mismo cálculo en M₁ y M₂; se prepara en las actividades 1.5 y 1.7 y se utiliza en las actividades 3.4 y 6.4. La matriz de registros del ITSM (MT-2) contiene los datos anonimizados de cada ticket: identificador, código del analista, fechas de creación, primera acción y cierre, categoría, marca de escalamiento con nivel de destino y marca de reapertura; se prepara en las actividades 1.6 y 1.7 y se utiliza en las actividades 3.2 y 6.2. La matriz de consolidación por analista (MT-3) reúne los valores mensuales de T-01 a T-04 y el puntaje de autoeficacia de cada analista en cada momento de medición; se prepara en la actividad 1.7 y se utiliza en las actividades 3.4, 3.7, 6.4, 6.6 y 7.1. El cuestionario de autoeficacia digital (MT-4) se elabora en la actividad 1.7, se valida en la actividad 1.10 y se aplica en las actividades 3.7 y 6.6.

### 5.3 Procedimientos por objetivo

**[MODIFICADO]** Para el primer objetivo, se revisará la literatura sobre autoeficacia digital, analítica de aprendizaje y desempeño en mesa de ayuda con el fin de identificar instrumentos e indicadores. Los ítems candidatos se registrarán en una matriz y se adaptarán al contexto para conformar el cuestionario MT-4, que pasará por juicio de expertos y una prueba piloto. Los indicadores de desempeño se contrastarán con los campos disponibles en el ITSM para seleccionar los que puedan medirse de la misma forma en M₁ y M₂, y a partir de ellos se elaborarán MT-1 y MT-2. Los registros de la aplicación, como el avance en los microcontenidos, el tiempo de visualización y la respuesta a la retroalimentación, se usarán para describir cómo se utilizó la herramienta durante el piloto.

**[MODIFICADO]** Para el segundo objetivo, se compararán las técnicas predictivas reportadas en la literatura, entre ellas la regresión logística, los árboles de decisión y los modelos de ensamble, según su interpretabilidad, el volumen de datos que requieren, su costo computacional y su utilidad para emitir alertas tempranas [3], [5], [14]. Se prevé seleccionar la regresión logística, porque permite explicar al usuario qué variables originan una alerta y se comporta mejor con muestras pequeñas. El modelo se entrenará con los registros de M₁ y estimará, para cada analista y mes, la probabilidad de presentar una posible brecha, definida a partir de umbrales en los indicadores de desempeño. Como esta etiqueta es operativa, su relación con el constructo se comprobará comparando el riesgo estimado con el puntaje del cuestionario en M₁ mediante la correlación de Spearman. El modelo se documentará en una ficha técnica con sus variables, supuestos, entrenamiento y validación.

**[MODIFICADO]** Para el tercer objetivo, se definirán los casos y las reglas que vinculan la salida del modelo con la respuesta formativa: cuando se detecte una posible brecha, la aplicación sugerirá microcontenidos relacionados, registrará la actividad del analista y le ofrecerá retroalimentación. La integración entre el ITSM, el motor predictivo y el módulo de formación se representará con diagramas de casos de uso, de componentes y de despliegue. El diseño se evaluará funcionalmente con una matriz de trazabilidad entre objetivos, requisitos y módulos, y con una rúbrica basada en las dimensiones propuestas en [13] (tecnología, pedagogía, diseño y contenido), a las que se añade la analítica.

*Cambio:* este párrafo absorbe la evaluación funcional del diseño, que antes correspondía al cuarto objetivo.

**[REEMPLAZADO]** Para el cuarto objetivo, se compararán los puntajes del cuestionario y los cuatro indicadores entre M₁ y M₂ mediante estadística descriptiva y la prueba de rangos con signo de Wilcoxon, adecuada para muestras pequeñas y emparejadas. Luego, con la correlación de Spearman, se analizará si los analistas que aumentaron su autoeficacia son también quienes mejoraron su desempeño. Los registros de uso de la aplicación servirán para interpretar estos cambios.

**[MODIFICADO]** El objetivo general se alcanzará al integrar estos productos: los instrumentos validados, la aplicación diseñada y evaluada, el cambio observado en la autoeficacia digital y su relación con el desempeño operativo.

### 5.4 Fases de ejecución

**[SIN CAMBIOS]** Las actividades se organizan en nueve fases con dependencias y están previstas para ejecutarse en días laborables entre marzo y diciembre de 2027.

**[MODIFICADO]** La Fase 1, preparación metodológica, atiende al primer objetivo. En ella se delimitará el proceso de gestión de incidentes que se evaluará; se definirán la población, la unidad de análisis y las reglas para calcular los indicadores; y se gestionarán el acceso al ITSM, las exportaciones y la anonimización. También se prepararán los instrumentos MT-1 a MT-4 y se validará el cuestionario de autoeficacia.

**[MODIFICADO]** La Fase 2, preparación tecnológica, atiende a los objetivos segundo y tercero. Se diagnosticará la infraestructura disponible, se definirán los requisitos y, a partir de ellos, se seleccionarán las tecnologías y se diseñarán la arquitectura y los módulos. Se elegirá la técnica predictiva, se definirá su integración con el módulo de formación y con el registro de eventos, se evaluará el diseño con la matriz de trazabilidad y se desarrollará el prototipo.

**[MODIFICADO]** La Fase 3, medición inicial, atiende a los objetivos primero, segundo y cuarto. Se realizará durante el desarrollo del prototipo, ya que los indicadores se calculan con datos históricos. Se tomarán los incidentes de los tres meses previos, se validará su integridad excluyendo los tickets sin categoría o sin fecha y se calcularán los indicadores por analista y mes en MT-3; el valor de M₁ de cada analista será el promedio mensual de ese periodo, para que sea comparable con el mes medido en el piloto. Con los mismos datos se entrenará el modelo predictivo. El cuestionario de autoeficacia se aplicará al final de esta fase, en la semana previa al inicio del piloto, para que el puntaje refleje la situación inmediatamente anterior a la intervención.

**[MODIFICADO]** La Fase 4, implementación de la intervención, está vinculada al tercer objetivo. Comprende preparar el entorno, configurar los usuarios, los permisos y las conexiones con el ITSM, orientar a los analistas y mantener la aplicación disponible durante cinco semanas.

**[SIN CAMBIOS]** La Fase 5, estabilización, se centra en el objetivo general. Abarcará la primera de las cinco semanas e incluirá el registro de los problemas de uso y la resolución de incidencias técnicas para atenuar los primeros efectos del aprendizaje de la herramienta. Finalizará con la verificación de la estabilidad del sistema.

**[MODIFICADO]** La Fase 6, medición posterior, atiende a los objetivos primero y cuarto, y abarca el mes de operación estable que sigue a la estabilización. Al cerrar el piloto, se extraerán los incidentes de ese mes con los mismos criterios de M₁, se comprobará que las definiciones, las fuentes y las unidades no hayan cambiado y se calcularán los indicadores en MT-3. En paralelo, se aplicará por segunda vez el cuestionario de autoeficacia.

**[MODIFICADO]** Las fases 7 a 9 completarán el estudio. La fase de procesamiento y análisis, vinculada a los objetivos segundo y cuarto, consolidará y depurará la base de datos, comparará M₁ y M₂ y analizará la relación entre autoeficacia y desempeño. La fase de interpretación relacionará los resultados con todos los objetivos y con la literatura. La de elaboración del informe comenzará en paralelo con la anterior y organizará la evidencia para redactar los resultados, la discusión y las conclusiones.

### 5.5 Consideraciones éticas y viabilidad

**[MODIFICADO]** La información se exportará formalmente con el permiso de la organización. Los datos se limitarán a los campos necesarios para los indicadores, y el identificador de cada analista se reemplazará por un código antes del análisis. Los participantes serán informados del propósito del piloto y darán su consentimiento para responder el cuestionario, cuyas respuestas serán confidenciales. Se aclarará que ni el cuestionario ni los indicadores se utilizarán para evaluar individualmente a las personas.

**[MODIFICADO]** La viabilidad del estudio se apoya en que los datos de desempeño de la medición inicial ya existen en el ITSM y no dependen de la aplicación, y en que el equipo y la unidad de análisis son los mismos en ambas mediciones. El estudio requiere que el ITSM registre de manera consistente las fechas, categorías, escalamientos, reaperturas y primeras acciones de cada ticket, y que los analistas respondan el cuestionario en los dos momentos. Como limitación, los resultados de un piloto de cinco semanas en un solo equipo no permitirán generalizar a otras organizaciones, pero sí orientar implementaciones posteriores.

---

## 6. CRONOGRAMA DE TRABAJO – Solo filas que cambian

El cronograma mantiene el periodo del 1 de marzo al 6 de diciembre de 2027 (40 semanas). Las actividades nuevas se ubican en paralelo con otras porque dependen de tiempos de respuesta externos (expertos o analistas), que es la misma regla de superposición que ya usa el cronograma. Por eso **no se alteran las fechas existentes del Gantt**.

### 6.1 Cambios en la columna "Objetivo" de la matriz de fases

| Fase | Antes | Ahora |
|---|---|---|
| 2. Preparación tecnológica | OE2, OE3, OE4 | OE2, OE3 |
| 3. Medición inicial | OG, OE1, OE2 | OE1, OE2, OE4 |
| 4. Implementación de la intervención | OG, OE3, OE4 | OG, OE3 |
| 6. Medición posterior | OG, OE1 | OE1, OE4 |
| 7. Procesamiento y análisis | OG, OE2 | OE2, OE4 |

### 6.2 Actividades modificadas y agregadas (matriz de fases y actividades)

| N.º | Estado | Actividad | Producto o evidencia esperada |
|---|---|---|---|
| 1.5 | MODIFICADO | Precisar las variables, los cuatro indicadores y las dimensiones de la autoeficacia digital | Ficha de definición de variables e indicadores |
| 1.7 | MODIFICADO | Preparar los instrumentos | MT-1, MT-2, MT-3 y **MT-4 Cuestionario de autoeficacia digital (versión preliminar)** |
| 1.10 | AGREGADO | Validar el cuestionario de autoeficacia (juicio de expertos, prueba piloto y alfa de Cronbach) | MT-4 validado; informe de validez y confiabilidad |
| 3.7 | AGREGADO | Aplicar el cuestionario de autoeficacia (pretest) | Puntajes de autoeficacia M₁ registrados en MT-3 |
| 6.4 | MODIFICADO | Calcular los valores posteriores de los cuatro indicadores y del cuestionario | Valores de M₂ consolidados en MT-3 |
| 6.6 | AGREGADO | Aplicar el cuestionario de autoeficacia (postest) | Puntajes de autoeficacia M₂ registrados en MT-3 |
| 7.3 | MODIFICADO | Calcular estadísticas descriptivas de la autoeficacia y de cada indicador por periodo | Tablas descriptivas del pretest y el postest |
| 7.4 | MODIFICADO | Estimar diferencias absolutas y relativas M₁–M₂ en la autoeficacia y en cada indicador | Tabla comparativa de variables |
| 7.5 | MODIFICADO | Aplicar la prueba de Wilcoxon, analizar la relación autoeficacia–desempeño con Spearman y validar el modelo | Resultados estadísticos; matriz de correlaciones; métricas finales del modelo |
| 8.1 | MODIFICADO | Examinar la magnitud y la dirección de los cambios en la autoeficacia digital y en T-01 a T-04 | Síntesis interpretativa por variable |
| 8.2 | MODIFICADO | Relacionar los cambios en autoeficacia con los de desempeño y con los objetivos | Matriz objetivos–hallazgos completada |

### 6.3 Justificación de duraciones (filas nuevas)

| Actividad | Duración estimada | Periodo en Gantt | Justificación |
|---|---|---|---|
| 1.10 Validar el cuestionario de autoeficacia | 10 días laborables | Abril (15–28/04) | La duración depende del tiempo de respuesta de los expertos y de los analistas de la prueba piloto; por ello se ejecuta en paralelo con 2.1–2.3 |
| 3.7 Aplicar el cuestionario (pretest) | 3 días laborables | Agosto (04–06/08) | Se aplica en la semana previa al piloto, antes de la orientación (4.3), para que el puntaje refleje la situación anterior a la intervención; corre en paralelo con 4.1 |
| 6.6 Aplicar el cuestionario (postest) | 3 días laborables | Septiembre (21–23/09) | Se aplica al cierre del piloto, en paralelo con la extracción de registros (6.2) |

En la tabla de justificación también cambia el texto de **7.5**: "Se aplicará la prueba de Wilcoxon a la autoeficacia y a cada indicador, se calculará la correlación de Spearman entre sus cambios y se obtendrán las métricas del modelo predictivo". Su duración se mantiene en 4 días.

---

## 7. BIBLIOGRAFÍA

**[SIN CAMBIOS]** Las referencias [1] a [14] se mantienen igual que en el APF3.

**[AGREGADO]**

[15] D. R. Compeau and C. A. Higgins, "Computer self-efficacy: Development of a measure and initial test," *MIS Quarterly*, vol. 19, no. 2, pp. 189–211, Jun. 1995, doi: 10.2307/249688.

Ahora las 15 referencias se citan al menos una vez en el texto. Las fuentes [10] y [11], que antes solo aparecían en un párrafo eliminado, ahora se citan en el Panorama.

---

## 8. TABLA DE CONTROL DE CAMBIOS

### 8.1 Problema, objetivos y justificación

| Párrafo en el APF3 (inicio) | Acción | Qué cambió |
|---|---|---|
| Título | Modificado | Se quitó "Propuesta de" y se añadieron "microaprendizaje" y "mesa de ayuda" |
| Resumen | Agregado | Nuevo, según la sesión S14-1 |
| "Los departamentos de TI proporcionan…" | Sin cambios | — |
| "La actitud del personal hacia las nuevas plataformas…" | Sin cambios | — |
| (nuevo) "Conviene distinguir la autoeficacia digital…" | Agregado | Diferencia autoeficacia y desempeño, como pidió el docente |
| "Existe una brecha creciente…" y "La participación es medible…" | Modificado | Unidos en un solo párrafo; formato de citas IEEE |
| "Hablando de analítica de aprendizaje…" | Modificado | Redacción y formato de citas |
| Problema principal | Modificado | Incluye la relación con el desempeño |
| Problemas secundarios | Reemplazado | Alineados con los nuevos objetivos específicos |
| "En este sentido, la presente investigación se inscribe…" | Modificado | Se quitó la referencia al sistema educativo nacional y a futuros profesionales |
| "Asimismo, se dispone en las competencias del egresado…" | Modificado | Se quitó la referencia a educación virtual y futuros estudiantes |
| Objetivo general | Reemplazado | Se quitó "a partir del diseño arquitectónico" y se añadió la relación con el desempeño |
| OE1 a OE4 | Reemplazado | OE1 incluye el cuestionario; OE2 vincula el modelo con la autoeficacia; OE3 absorbe la evaluación del diseño; OE4 evalúa los cambios y su relación |
| "La investigación se apoya en cuatro frentes…" | Sin cambios | — |
| "En las empresas, casi todo servicio digital pasa por TI…" | Modificado | Añade la medición directa de la autoeficacia |
| "En tecnología, hoy es razonable combinar…" | Modificado | Se quitaron citas que se repetían en el estado del arte |
| "En lo académico, el trabajo cruza…" | Modificado | Menciona que se medirán ambas variables |
| "Se esperan tres aportes…" | Modificado | Pasan a cuatro aportes, con el cuestionario adaptado |

### 8.2 Estado del arte

| Párrafo en el APF3 (inicio) | Acción | Nueva ubicación | Qué cambió |
|---|---|---|---|
| P1 "Se revisaron artículos relacionados…" | Modificado | Introducción | Bases, términos y periodo (por completar); se quitó "determinó brechas" |
| P2 "La investigación se centró en…" | Modificado | 4.1 Panorama | Ordenado en tres líneas, con citas por línea; incorpora [10] y [11] |
| P3 "En el área de la capacitación corporativa…" | Modificado | 4.1 Panorama | Señala que la evidencia viene sobre todo de educación; se quitaron citas que no respaldaban la idea |
| P4 "Los trabajadores digitales demuestran baja autoeficacia…" | Reemplazado | 4.2.1 | Se eliminó la generalización a "trabajadores digitales" y se describe la población real de cada fuente |
| P5 "La variabilidad respecto a la creencia…" | Modificado | 4.2.1 | Cada factor se atribuye a su fuente |
| P6 "La investigación sobre la autoeficacia de los empleados de TI… es escasa" | Modificado | 4.3 Balance crítico | Se mantiene la primera idea; se quitó la segunda frase porque sus citas eran de educación |
| P7 "La flexibilidad del personal de TI…" | Eliminado | — | Casi sin citas y fuera del problema |
| P8 "Los eventos que ocurren debido a no cumplir con un SLA…" | Modificado | 4.2.2 | Se quitó la primera frase, que era informal; se añadió el contraste entre fuentes |
| P9 "Los niveles de confianza digital… tickets" | Modificado | 4.3 Balance crítico | Pasa a presentarse como vacío: las métricas de mesa de ayuda no miden directamente la autoeficacia |
| P10 "La confianza digital y la autoeficacia digital pueden medirse…" | Modificado | 4.2.1 | Se centra en la medición con cuestionarios y añade [15]; se quitó la frase del tablero |
| P11 "Debido a la falta de estudios de caso transdisciplinarios…" | Modificado | 4.3 Balance crítico | Se aclara que es un riesgo de los modelos no interpretables |
| P12 "La naturaleza del trabajo y la frecuencia de despliegue…" | Modificado | 4.2.3 | Reescrito como síntesis de [4] y [9] |
| P13 "La falta de datos dificulta…" | Modificado | 4.2.2 | Reducido y sustituido por el aporte metodológico de [14] |
| P14 "Existen numerosos problemas… just-in-time" | Modificado | 4.2.3 | Se quitó "Predecir… es fácil"; la idea de integración pasa al balance crítico |
| P15 "La retroalimentación inteligente utilizará reglas…" | Modificado | 4.2.3 | Se eliminó la frase sobre depurar programas, que no correspondía a [4] |
| P16 "Existe una variedad de factores…" | Modificado | 4.2.4 | Unido con P17 |
| P17 "Prever cuán exitosamente se empleará…" | Modificado | 4.2.4 | Unido con P16; añade la limitación del contexto infantil |
| (nuevo) "La evidencia revisada permite sostener tres ideas…" | Agregado | 4.3 Balance crítico | Síntesis de lo que sí se puede afirmar |
| (nuevo) "Por último, la literatura aborda los componentes por separado…" | Agregado | 4.3 Balance crítico | Recoge la idea de integración de P14 |
| P18 "Hay producción abundante…" | Modificado | 4.4 Fundamentación | Redacción e introducción a la tabla |
| Tabla de vacíos | Modificado | 4.4 Fundamentación | Citas en cada fila, una fila nueva de desempeño y orientación actualizada |
| P19 "Las principales brechas como…" | Reemplazado | 4.4 Fundamentación | Frase sin verbo sustituida por el cierre que conecta el vacío con el objetivo |
| P20 "Ha habido algunos estudios…" | Eliminado (fusionado) | 4.3 | Su idea queda integrada en el balance crítico |
| P21 "Existen numerosos métodos…" | Eliminado | — | Presentaba como hecho lo que aún no se ha investigado |
| P22 "Hay muchas oportunidades de reciclaje…" | Eliminado | — | Primera persona y fuera del problema |
| P23 "La tecnología que actualmente está disponible…" | Eliminado | — | Primera persona, "clientes" y pensamiento de diseño |

### 8.3 Metodología

| Párrafo en el APF3 (inicio) | Acción | Qué cambió |
|---|---|---|
| "Para determinar la contribución…" | Reemplazado | Dos variables por momento (cuestionario e ITSM) |
| "Esta investigación adoptará un enfoque cuantitativo…" | Modificado | Incluye los puntajes de autoeficacia; se quitaron citas que no respaldaban la ciencia del diseño |
| "Tendrá un alcance de carácter explicativo…" | Reemplazado | Se eliminó "no se evaluará mediante escalas psicométricas"; se separan los conceptos |
| "Se implementará un diseño preexperimental…" | Modificado | M₁ y M₂ incluyen el cuestionario |
| "El diseño responde a las condiciones…" | Sin cambios | — |
| "El personal para el estudio serán…" | Modificado | Añade el consentimiento y el cuestionario como fuente |
| "La variable independiente es…" | Reemplazado | VD principal: autoeficacia; VD complementaria: desempeño |
| (nuevo) Cuestionario MT-4 | Agregado | Instrumento, adaptación, validación y confiabilidad |
| "La variable dependiente se medirá…" y "El indicador T-01…" | Modificado | Unidos y condensados; se quitaron citas no pertinentes |
| "La técnica de recolección…" | Modificado | Encuesta más análisis de registros |
| "La matriz de definición (MT-1)…" | Modificado | Añade MT-4 y el puntaje en MT-3 |
| Procedimiento OE1 | Modificado | Incluye la construcción del cuestionario |
| Procedimiento OE2 | Modificado | Etiqueta del modelo y comprobación con el cuestionario |
| Procedimiento OE3 | Modificado | Absorbe la evaluación funcional del diseño |
| Procedimiento OE4 | Reemplazado | Wilcoxon y Spearman sobre autoeficacia y desempeño |
| "El objetivo general se alcanzará…" | Modificado | Integra los nuevos productos |
| "Las actividades se organizan en 9 fases…" | Sin cambios | — |
| Fases 1, 2, 3, 4, 6 y 7–9 | Modificado | Nuevas actividades del cuestionario y objetivos reasignados |
| Fase 5 | Sin cambios | — |
| "La información se exportará formalmente…" | Modificado | Dividido en ética y viabilidad; añade el consentimiento; se corrigió la frase "no justifica un despliegue amplio" |

---

## 9. PUNTOS QUE DEBES VERIFICAR

1. **[COMPLETAR]** Las bases de datos y el periodo de búsqueda de tu RSL, en la introducción del estado del arte.
2. Confirma en los artículos [2] y [6] que midieron la autoeficacia con cuestionarios, porque el texto lo afirma en 4.2.1 y en la metodología.
3. Confirma que [13] use las dimensiones de contenido, tecnología y pedagogía, y que [14] mencione la importancia de la calidad de los datos.
4. Actualiza el Gantt en Microsoft Project con las actividades 1.10, 3.7 y 6.6.
5. Actualiza el índice con los nuevos subtítulos del estado del arte y de la metodología.
