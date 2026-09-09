<div align="center">

<img src="assets/img/cover/upc-logo.png" alt="UPC Logo" width="70"/>

Universidad Peruana de Ciencias Aplicadas

Carrera de Ingeniería de Software

**1ACC0238**

**Aplicaciones para Dispositivos Móviles**

NRC: **4945**

### Informe del Trabajo Final

Docente: **Mayta Guillermo, Jorge Luis**

<br>

Equipo

**VitalCare**

Proyecto

**Serenia**

<br>

Integrantes

| Código | Apellidos y Nombres |
|---|---|
| u202414802 | Contreras Torres, Arturo Valentino |
| u202414970 | Gallardo Morales, Carla Alejandra |
| u202012001 | García Paredes, Victor Manuel |
| u202410239 | Salinas Guzman, Brianna Cristina |
| u202418645 | Sandoval Aiquipa, Kelber Yamir |

<br>

**Período 2026-20**

**Septiembre 2026**

</div>

<br>

---

# Registro de Versiones del Informe

<table>
  <tr>
    <th>Versión</th>
    <th>Fecha</th>
    <th>Autor</th>
    <th>Descripción de modificación</th>
  </tr>

  <tr>
    <td><b>Primera Entrega (AV1)</b></td>
    <td>XX/09/2026</td>
    <td>
      Contreras Torres, Arturo Valentino <br>
      <p></p>
      Gallardo Morales, Carla Alejandra <br>
      <p></p>
      García Paredes, Victor Manuel <br>
      <p></p>
      Salinas Guzman, Brianna Cristina <br>
      <p></p>
      Sandoval Aiquipa, Kelber Yamir <br>
    </td>
    <td>
      Capítulo I: Presentación <br>
      Capítulo II: Requirements Development and Software Solution Design <br>
    </td>
  </tr>
  </table>

<br>

  ---

# Project Report Collaboration Insights

El informe del proyecto fue desarrollado de manera colaborativa por el equipo mediante repositorios de GitHub creados para la gestión del Project Report y de los diferentes componentes del proyecto. Estos repositorios contienen los archivos del informe, diagramas, evidencias, wireframes, mockups y el historial de versiones correspondiente a cada entrega.

URL del repositorio (report): https://github.com/upc-pre-202620-1acc0238-4945-vitalcare/serenia-report <br>

**Primera Entrega (AV1)**

<br>

---

# Contenido

## Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Presentación](#capítulo-i-presentación)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      - [Misión](#misión)
      - [Visión](#visión)
      - [Valores](#valores)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
      - [Segmento 1: Adultos mayores que viven solos](#segmento-1-adultos-mayores-que-viven-solos)
      - [Segmento 2: Familiares a distancia](#segmento-2-familiares-a-distancia)
- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
      - [Segmento 1: Adultos mayores que viven solos](#segmento-1-adultos-mayores-que-viven-solos-1)
      - [Segmento 2: Familiares a distancia](#segmento-2-familiares-a-distancia-1)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. Big Picture EventStorming](#235-big-picture-eventstorming)
    - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
  - [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](#243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
    - [2.5.1. EventStorming](#251-eventstorming)
      - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
      - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
      - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
      - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
      - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
      - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.x. Bounded Context: ](#26x-bounded-context-)
      - [2.6.x.1. Domain Layer](#26x1-domain-layer)
      - [2.6.x.2. Interface Layer](#26x2-interface-layer)
      - [2.6.x.3. Application Layer](#26x3-application-layer)
      - [2.6.x.4 Infrastructure Layer](#26x4-infrastructure-layer)
      - [2.6.x.5. Bounded Context Software Architecture Component Level Diagrams](#26x5-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.x.6. Bounded Context Software Architecture Code Level Diagrams](#26x6-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.x.6.1. Bounded Context Domain Layer Class Diagrams](#26x61-bounded-context-domain-layer-class-diagrams)
        - [2.6.x.6.2. Bounded Context Database Design Diagram](#26x62-bounded-context-database-design-diagram)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
  - [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
      - [3.1.2.1. Organization Systems](#3121-organization-systems)
      - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      - [3.1.2.4. Searching Systems](#3124-searching-systems)
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
      - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
      - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
      - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
      - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
      - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
      - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
      - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
- [Capítulo IV: Product Implementation \& Validation](#capítulo-iv-product-implementation--validation)
  - [4. Product Implementation \& Validation](#4-product-implementation--validation)
  - [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.1.3. Source Code Style Guide \& Conventions](#413-source-code-style-guide--conventions)
    - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Landing Page \& Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
    - [4.2.1. Sprint n](#421-sprint-n)
      - [4.2.1.1. Sprint Planning n](#4211-sprint-planning-n)
      - [4.2.1.2. Aspect Leaders and Collaborators](#4212-aspect-leaders-and-collaborators)
      - [4.2.1.3. Sprint Backlog n](#4213-sprint-backlog-n)
      - [4.2.1.4. Development Evidence for Sprint Review](#4214-development-evidence-for-sprint-review)
      - [4.2.1.5. Testing Suite Evidence for Sprint Review](#4215-testing-suite-evidence-for-sprint-review)
      - [4.2.1.6. Execution Evidence for Sprint Review](#4216-execution-evidence-for-sprint-review)
      - [4.2.1.7. Services Documentation Evidence for Sprint Review](#4217-services-documentation-evidence-for-sprint-review)
      - [4.2.1.8. Software Deployment Evidence for Sprint Review](#4218-software-deployment-evidence-for-sprint-review)
      - [4.2.1.9. Team Collaboration Insights during Sprint](#4219-team-collaboration-insights-during-sprint)
  - [4.3. Validation Interviews](#43-validation-interviews)
    - [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)
    - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)
    - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)
  - [Video App Validation](#video-app-validation)
  - [Video About the product](#video-about-the-product)
  - [Video About the team](#video-about-the-team)
- [Glosario](#glosario)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<br>

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 7**

**Criterio:** *La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7.

<table>
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
      <td><b>Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.</b></td>
      <td>
            <b>Contreras Torres, Arturo Valentino</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>Gallardo Morales, Carla Alejandra</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>García Paredes, Victor Manuel</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>Salinas Guzman, Brianna Cristina</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>Sandoval Aiquipa, Kelber Yamir</b><br>
            <u>AV1</u><br>
            <br><br>
        </td>
        <td>
            <u>AV1</u><br>
        </td>
    </tr>
      <tr>
      <td><b>Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.</b></td>
      <td>
            <b>Contreras Torres, Arturo Valentino</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>Gallardo Morales, Carla Alejandra</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>García Paredes, Victor Manuel</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>Salinas Guzman, Brianna Cristina</b><br>
            <u>AV1</u><br>
            <br><br>
            <b>Sandoval Aiquipa, Kelber Yamir</b><br>
            <u>AV1</u><br>
            <br><br>
        </td>
        <td>
            <u>AV1</u><br>
        </td>
    </tr>
</table>

---

# Objetivos SMART

<br>

# Capítulo I: Presentación
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

Vivir lejos de un padre o una madre mayor genera una tensión particular: la necesidad de saber que están bien sin querer invadir su día a día con llamadas constantes. Esta dinámica se ha vuelto cada vez más común en el Perú, donde, según el INEI, 1 de cada 4 hogares liderados por adultos mayores en Lima es unipersonal. Muchos de estos adultos mayores optan por no contar cuando algo no anda bien, para no generar preocupación en sus familias, lo que termina alejando a ambas partes justo cuando más necesitan estar conectadas.

VitalCare nace para sanar esta desconexión apostando por tecnología que acompaña, no que vigila. Nuestro primer producto, Serenia, permite al adulto mayor compartir como se siente con un solo toque desde su dispositivo, sin necesidad de dar largas explicaciones. Mientras tanto, la familia recibe actualizaciones sobre su bienestar en tiempo real, sin tener que preguntar todo el tiempo.

El corazón de Serenia es que cada interacción se sienta como una charla genuina y no como un chequeo médico. Incluye preguntas ligeras, un espacio para grabar anécdotas y alertas familiares que solo suenan cuando de verdad hacen falta. Queremos devolver la naturalidad al cuidado a distancia: dándole tranquilidad a la familia y respetando siempre la autonomía del adulto mayor.

<br>

## Misión

Dar a los adultos mayores que viven solos una forma simple y natural de comunicar su día a día, y a sus familias, la tranquilidad de saber cómo están. Reducimos la ansiedad de la distancia conectándolos desde el afecto, sin caer en el monitoreo invasivo.

<br>

## Visión

Ser la plataforma de compañía digital que transforme cómo las familias de Latinoamérica se cuidan a distancia. Queremos fortalecer el vínculo emocional por encima del reporte clínico, logrando que ningún adulto mayor enfrente la soledad en silencio.

<br>

## Valores

- **Cercanía:** <br>
  Diseñamos cada interacción con un lenguaje cálido y humano. Cuidar no debe sentirse como una obligación ni leerse como un historial médico.

- **Autonomía:** <br>
  El adulto mayor decide qué y cuándo compartir. Respetamos su independencia y evitamos que se sienta incapaz de gestionar su vida.

- **Confianza:** <br>
  Más que vigilancia constante, ofrecemos información honesta y alertas oportunas para darle verdadera tranquilidad a ambas partes.
  
- **Conexión emocional:** <br>
  Celebramos lo bueno de la rutina. Fomentamos espacios como "cuéntame algo" para registrar pequeñas victorias y reforzar el cariño diario, no solo para alertar sobre problemas.

<br>

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <td rowspan="3" align="center">
      <img src="assets/img/member-profiles/arturo-contreras.PNG" alt="Foto de Arturo Contreras" width="500"/>
    </td>
    <td><b>Nombre:</b> Arturo Valentino Contreras Torres</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202414802</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Arturo Valentino Contreras Torres</b>, tengo 19 años y estudio Ingeniería de Software en la UPC, actualmente en el 6to ciclo. Me gusta aprender y aplicar tecnologías innovadoras para resolver problemas complejos y desarrollar soluciones eficientes. Me apasiona participar en concursos de programación, donde profundizo en programación competitiva y en la creación de nuevas ideas. Tengo conocimiento en frameworks como Vue, Angular y Spring Boot, y disfruto trabajar en equipo bajo metodologías ágiles. También me interesan Clean Architecture, Domain-Driven Design y otras prácticas que ayudan a escribir mejor código.
      <br/>
    </td>
  </tr>

  <tr>
    <td rowspan="3" align="center">
      <img src="assets/img/member-profiles/carla-gallardo.png" alt="Foto de Carla Gallardo" width="500"/>
    </td>
    <td><b>Nombre:</b> Gallardo Morales, Carla Alejandra</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202414970</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Carla Alejandra Gallardo Morales</b>, tengo 19 años. Desde que me incorporé en la Universidad Peruana de Ciencias Aplicadas en el periodo 2024-01, es decir que ahora mismo estoy cursando el sexto ciclo de la carrera de Ing. de Software, he adquirido y desarrollado distintos conocimientos a cerca de la programación, específicamente en el lenguaje C++, JavaScript y TypeScript, además, de forma autodidacta y extracurricular, he profundizado en el lenguaje Python, lo que ha ampliado mi perspectiva sobre la lógica y resolución de problemas.
      <br/><br/>
      Dentro del equipo, mi contribución se basa en el apoyo continuo del desarrollo del frontend de nuestro aplicativo mobile, asimismo ayudo en la implementación del informe de nuestro proyecto.
      <br/>
    </td>
  </tr>

  <tr>
    <td rowspan="3" align="center">
      <img src="assets/img/member-profiles/victor-garcia.png" alt="Foto de Victor García" width="500"/>
    </td>
    <td><b>Nombre:</b> García Paredes, Victor Manuel</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202012001</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Victor Manuel García Paredes</b>, estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), con sólidos conocimientos en desarrollo de aplicaciones, estructuras de datos y programación orientada a objetos. Tengo experiencia en el uso de C++, así como en la gestión de proyectos mediante herramientas como Git y GitHub para el control de versiones. También tengo conocimientos básicos de Python, MSSQL, MongoDB, JavaScript y TypeScript. Me caracterizo por ser una persona responsable, con iniciativa para el aprendizaje autónomo, y con habilidades para el trabajo en equipo y la comunicación efectiva de ideas.
      <br/>
    </td>
  </tr>

  <tr>
    <td rowspan="3" align="center">
      <img src="assets/img/member-profiles/brianna-salinas.png" alt="Foto de Brianna Salinas" width="500"/>
    </td>
    <td><b>Nombre:</b> Salinas Guzman, Brianna Cristina</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202410239</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Brianna Cristina Salinas Guzmán</b>, tengo 19 años y estudio Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), actualmente en el 6to ciclo. Tengo experiencia en desarrollo backend con Spring Boot y Express.js, aplicando Domain-Driven Design (bounded contexts, autenticación JWT, integración con APIs externas), así como en frontend con Angular, React y Vue. Me interesa profundizar en el desarrollo de aplicaciones móviles, tanto nativas como multiplataforma, y disfruto trabajar bajo metodologías ágiles y buenas prácticas de arquitectura de software.
      <br/>
    </td>
  </tr>

  <tr>
    <td rowspan="3" align="center">
      <img src="" alt="Foto de Kelber Sandoval" width="500"/>
    </td>
    <td><b>Nombre:</b> Sandoval Aiquipa, Kelber Yamir</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202418645</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b></b>
      <br/>
    </td>
  </tr>

</table>

<br>

## 1.2. Solution Profile

Serenia es una solución con dos interfaces: una dirigida al adulto mayor que vive solo y otra dirigida al familiar a distancia. Ambos comparten un mismo objetivo: sustituir la llamada telefónica diaria motivada por la ansiedad con una forma de comunicación más simple, natural y menos invasiva del bienestar cotidiano.

Del lado del adulto mayor, la aplicación inicia el contacto de forma proactiva: a una hora determinada del día, le pregunta cómo se encuentra mediante una interacción de un solo toque, alternando preguntas ligeras y variables —no siempre preguntas comunes como "¿cómo estás?", "¿qué haces?", sino también "¿jugaste bingo hoy con tus amigos?" o "¿qué tal te pareció el partido de hoy?"— para que la experiencia se sienta como una conversación real y no como un control constante. Además, cuenta con un espacio de "cuéntame algo" donde puede grabar un audio corto sobre su día, con recordatorios de contacto social más allá de los médicos, con la posibilidad de indicar que ese día no desea que le pregunten nada, con un modo simplificado para jornadas de menor energía, y con un botón de auxilio siempre visible para emergencias.

Del lado del familiar, la aplicación ofrece un panel de estado diario que muestra si el adulto mayor completó su check-in y cómo se sintió, sin necesidad de llamar para averiguarlo. Las alertas solo se activan cuando algo se sale de lo habitual, evitando que el familiar revise la aplicación de forma ansiosa durante todo el día. La aplicación también sugiere acciones suaves cuando el adulto mayor reporta sentirse "no tan bien" varios días seguidos y registra pequeñas victorias además de alertas.

El diferenciador central de Serenia frente a otras soluciones de monitoreo es su enfoque en la compañía por encima de la vigilancia: el lenguaje y las interacciones evitan el tono clínico o de "reporte", priorizando el vínculo emocional cotidiano entre adulto mayor y su familia, sin descuidar la seguridad ante situaciones de emergencia.

<br>

### 1.2.1. Antecedentes y problemática

<br>

### 1.2.2. Lean UX Process

Esta sección desarrolla el Lean UX Process aplicado al dominio del problema de Serenia, siguiendo la metodología de Lean UX (Gothelf & Seiden, 2021). Se parte de un Problem Statement único para todo el proyecto, se derivan los Assumptions organizados según los cinco tipos propuestos por Lean UX, se construyen los Hypothesis Statements correspondientes a cada Feature Assumption, y finalmente se consolida todo en un Lean UX Canvas.

#### 1.2.2.1. Lean UX Problem Statements

El estado actual de **la comunicación entre adultos mayores que viven solos y sus familiares a distancia** se ha enfocado principalmente en **llamadas telefónicas reactivas motivadas por la ansiedad, y en aplicaciones de monitoreo de salud con un enfoque clínico y de vigilancia constante**.

Lo que los productos o servicios existentes no logran resolver es **una forma de comunicación cotidiana, ligera y bidireccional que transmita bienestar emocional sin invadir la autonomía del adulto mayor ni generar una carga de vigilancia sobre el familiar**.

Nuestro producto resolverá esta brecha **ofreciendo un check-in diario de un solo toque para el adulto mayor, con preguntas variables y un tono de compañía (no clínico), y un panel de estado para el familiar que solo emite alertas cuando algo se sale de lo habitual**.

Nuestro enfoque inicial será **adultos mayores de 60 años a más que viven solos en zonas urbanas del Perú, y sus familiares directos de 25 a 59 años que residen en una ciudad o distrito distinto**.

Sabremos que hemos tenido éxito cuando veamos **una alta tasa de check-ins diarios completados por el adulto mayor, una reducción en la frecuencia de llamadas motivadas por ansiedad por parte del familiar, y un uso recurrente del panel de estado sin necesidad de soporte o intervención externa**.

<br>

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**
- Existe un mercado desatendido de soluciones de comunicación familiar a distancia que no dependen de dispositivos médicos ni wearables costosos.
- Un modelo freemium (funciones básicas gratuitas, funciones familiares avanzadas de pago) es viable como estrategia de monetización, dado el bajo costo de adquisición vía recomendación familiar (boca a boca).
- VitalCare puede posicionarse como alternativa a las apps de monitoreo de salud, diferenciándose por su enfoque emocional y no clínico.

**Business Outcome Assumptions**
- El aumento en la cantidad de check-ins completados por semana indicará que la solución se está adoptando como hábito.
- La reducción en el costo de soporte/atención al cliente (menos consultas del tipo "¿cómo sé si está bien mi familiar?") indicará que el panel de estado cumple su función sin fricción.
- El incremento en el número de familiares que se registran a partir de una recomendación de otro usuario validará el boca a boca como canal de adquisición.

**User Assumptions**
- El adulto mayor que vive solo tiene acceso a un smartphone táctil y sabe realizar interacciones simples (tocar un botón, grabar un audio).
- El familiar a distancia revisa su smartphone varias veces al día y está dispuesto a instalar una aplicación adicional para conocer el bienestar de su familiar.
- Ambos segmentos desconfían de soluciones que se sientan "médicas" o de vigilancia constante.

**User Outcome and Benefit Assumptions**
- El adulto mayor obtiene una forma de expresar cómo se siente sin tener que iniciar una llamada ni dar explicaciones extensas.
- El familiar obtiene tranquilidad diaria sin tener que llamar constantemente ni sentir que está invadiendo la rutina del adulto mayor.
- Ambos segmentos fortalecen su vínculo emocional a través de interacciones ligeras (como "cuéntame algo"), en lugar de limitarse a reportes de estado.

**Feature Assumptions**
- Un check-in diario de un solo toque con preguntas variables reducirá la fricción de comunicación para el adulto mayor.
- Un espacio de "cuéntame algo" (audio corto) permitirá capturar momentos cotidianos que fortalezcan el vínculo familiar.
- Un panel de estado con alertas inteligentes (solo ante anomalías) evitará que el familiar revise la aplicación de forma ansiosa.
- Un botón de auxilio siempre visible cubrirá el escenario de emergencia sin necesidad de vigilancia constante.

<br>

#### 1.2.2.3. Lean UX Hypothesis Statements

1. **Check-in diario de un toque**: Creemos que lograremos *una alta tasa de adopción diaria del check-in* si *los adultos mayores que viven solos en zonas urbanas del Perú* logran *comunicar su estado de ánimo sin esfuerzo ni necesidad de dar explicaciones extensas* con *un check-in de un solo toque con preguntas ligeras y variables*.
2. **"Cuéntame algo"**: Creemos que lograremos *un mayor vínculo emocional percibido entre ambos segmentos* si *los adultos mayores y sus familiares a distancia* logran *compartir momentos cotidianos más allá de reportes de bienestar* con *un espacio de grabación de audio corto llamado "cuéntame algo"*.
3. **Panel de estado con alertas inteligentes**: Creemos que lograremos *una reducción en la frecuencia de llamadas motivadas por ansiedad* si *los familiares a distancia* logran *conocer el estado de bienestar de su familiar sin necesidad de preguntar constantemente* con *un panel de estado diario que solo emite alertas cuando se detecta una anomalía*.
4. **Botón de auxilio**: Creemos que lograremos *mayor confianza en la solución como respaldo ante emergencias* si *los adultos mayores que viven solos* logran *solicitar ayuda de forma inmediata en caso de urgencia* con *un botón de auxilio siempre visible y de fácil acceso*.

<br>

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas consolida el Business Problem, los Business Outcomes, los Users, los User Outcomes & Benefits, las Solutions y las Hypotheses desarrolladas en las subsecciones anteriores, junto con la identificación de la asunción de mayor riesgo (Segmento 1 adoptando el check-in diario como hábito) y el experimento de menor esfuerzo para validarla.

<p align="center">
  <img src="assets/img/diagrams/lean-ux-canvas.png" alt="Lean UX Canvas de Serenia" width="900"/>
</p>

URL del archivo en Figma: https://www.figma.com/design/MtWwz8GxmrY0eR7eyc2UC0/Lean-UX-Canvas--Serenia-?node-id=0-1

<br>

## 1.3. Segmentos objetivo

Serenia conecta a dos perfiles de usuarios clave, definidos a partir del problema que resolvemos y respaldados por la realidad demográfica peruana.

#### Segmento 1: Adultos mayores que viven solos

- **Perfil:** Personas de 60 años a más, residentes en zonas urbanas del Perú, que viven solas y cuentan con un teléfono celular.

- **Sustento:** Aunque se suele pensar que la tecnología es una barrera, las cifras dicen lo contrario. En este grupo etario, el uso de celular llega al 97,7%, y la penetración de internet en áreas urbanas alcanza el 56,8% (INEI, 2025b). Además, el 25,3% de los hogares limeños con jefatura adulta mayor son unipersonales (INEI, 2025a). Esto confirma un escenario claro: existe un grupo numeroso de adultos mayores viviendo sin compañía permanente, pero que ya tienen en sus manos el dispositivo necesario para aprovechar una interacción sencilla, de un solo toque, como la que propone Serenia.

#### Segmento 2: Familiares a distancia

- **Perfil:** Hijos, hijas o parientes cercanos de 25 a 59 años que no conviven con el adulto mayor —ya sea por migración a otra ciudad o por vivir en distritos distintos— y buscan saber de ellos sin recurrir a llamadas constantes.

- **Sustento:** Lima concentra el 45,4% de los migrantes internos del país por motivos laborales o educativos (Carrasco Freitas, 2026), evidenciando una alta proporción de familias separadas geográficamente. Para acortar esta distancia, la tecnología es el puente ideal: el 95,4% de hogares peruanos ya cuenta con un smartphone (OSIPTEL, 2026), con una adopción que bordea el 95% en los adultos jóvenes y de mediana edad. Así, este segmento combina perfectamente la necesidad emocional de estar presentes con la fluidez tecnológica para integrar la app en su rutina diaria.

<br>

# Capítulo II: Requirements Development and Software Solution Design
## 2.1. Competidores

<br>

### 2.1.1. Análisis competitivo

<br>

### 2.1.2. Estrategias y tácticas frente a competidores

A partir del análisis competitivo y el FODA desarrollado, se plantean las siguientes estrategias y tácticas preliminares que Serenia aplicará para afrontar las fortalezas de la competencia, aprovechar sus debilidades, y responder al contexto de oportunidades y amenazas del entorno.

<table>
  <tr>
    <th colspan="2" align="center">Matriz de estrategias (TOWS) — Serenia frente a la competencia</th>
  </tr>
  <tr>
    <td width="25%"><b>Fortalezas + Oportunidades (FO)</b><br/>Usar las fortalezas propias para capitalizar oportunidades del entorno</td>
    <td>
      Aprovechar el lenguaje cercano y no clínico de Serenia, junto con su bajo costo de entrada (no requiere comprar hardware, a diferencia de GrandPad), para capturar el mercado peruano y latinoamericano que Alexa Together, GrandPad y Papa aún no atienden, ya que las tres soluciones están diseñadas y comercializadas principalmente para EE. UU. y Reino Unido. Esta ventana se refuerza con la creciente proporción de adultos mayores que viven solos en Lima Metropolitana (Andina, 2025), lo que amplía el mercado objetivo antes de que un jugador global localice su oferta.
    </td>
  </tr>
  <tr>
    <td><b>Fortalezas + Amenazas (FA)</b><br/>Usar las fortalezas propias para neutralizar amenazas externas</td>
    <td>
      Frente a la amenaza de que jugadores globales como Amazon (Alexa Together) o GrandPad ingresen a mercados emergentes, Serenia debe afianzar su ventaja de contexto local (idioma, sensibilidad cultural, alianzas con clínicas geriátricas o EPS peruanas) antes de que estas empresas adapten su oferta a la región. Frente a la resistencia tecnológica del adulto mayor, se mantiene la interacción de un solo toque en el check-in diario como barrera de simplicidad, replicando el principio de "cero curva de aprendizaje" que hace fuerte a GrandPad, pero sin el costo de un dispositivo dedicado.
    </td>
  </tr>
  <tr>
    <td><b>Debilidades + Oportunidades (DO)</b><br/>Corregir debilidades propias apoyándose en oportunidades del entorno</td>
    <td>
      Para compensar la falta de marca instalada y de un canal B2B (a diferencia de Papa, que accede a usuarios mediante seguros y beneficios laborales), Serenia puede buscar alianzas tempranas con EPS, clínicas geriátricas o municipios peruanos que permitan escalar sin depender únicamente de la adquisición directa al consumidor. Asimismo, se debe aprovechar el vacío de mercado identificado para posicionarse antes de que surja un competidor local equivalente.
    </td>
  </tr>
  <tr>
    <td><b>Debilidades + Amenazas (DA)</b><br/>Minimizar debilidades propias y evitar el impacto de amenazas externas</td>
    <td>
      Dado que Serenia depende de que ambos extremos —adulto mayor y familiar— adopten la app de forma consistente, y que existe baja disposición a pagar suscripciones en el segmento peruano, se debe ofrecer un modelo freemium con fricción mínima de onboarding, evitando estrategias de pago agresivas desde el inicio (a diferencia del modelo de suscripción obligatoria de GrandPad). Esto también reduce el riesgo de que sustitutos informales y gratuitos, como los grupos familiares de WhatsApp, sigan siendo la opción por defecto.
    </td>
  </tr>
</table>

<br>

## Tácticas específicas frente a cada competidor

Frente a **Alexa Together**, cuya fortaleza es el ecosistema Amazon/IoT ya instalado, Serenia no compite en hardware ni en monitoreo domótico, sino que diferencia su mensaje de marketing contrastando "compañía" frente a "vigilancia", aprovechando además que Alexa Together no está integrado a flujos clínicos y genera dudas de privacidad no resueltas públicamente.

Frente a **GrandPad**, cuya fortaleza es la simplicidad extrema de un dispositivo dedicado, Serenia ofrece una experiencia igualmente simple (check-in de un solo toque) pero sobre el smartphone que la familia peruana ya posee, evitando el costo de USD 299 más USD 40 mensuales que representa la barrera de entrada más débil de GrandPad.

Frente a **Papa**, cuya fortaleza es la compañía humana presencial, Serenia posiciona su espacio de "cuéntame algo" y el check-in emocional diario como un complemento cotidiano entre visitas físicas esporádicas, no como un sustituto, aprovechando además que Papa depende de contratos con aseguradoras y empleadores estadounidenses y no tiene presencia en el mercado peruano.

<br>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Para conocer mejor a nuestros dos segmentos, se diseñaron dos guías de entrevista: una para adultos mayores que viven solos y otra para familiares a distancia. Las preguntas van de lo general (datos personales, rutina) a lo más específico (vínculo familiar, tecnología, frustraciones), buscando entender tanto hechos concretos como sentimientos y motivaciones de cada entrevistado.

#### Segmento 1: Adultos mayores que viven solos

1. ¿Cuál es su nombre, edad y distrito de residencia?
2. ¿Vive solo/a? ¿Desde hace cuánto tiempo?
3. ¿Cuál es su estado civil? ¿Tiene hijos u otros familiares cercanos?
4. ¿A qué se dedica o se dedicaba usted?
5. ¿Cómo es un día normal para usted?
6. ¿Con qué frecuencia sale de casa y para qué?
7. ¿Con qué frecuencia habla con sus familiares que no viven con usted?
8. Cuando tiene un mal día, ¿se lo cuenta a su familia? ¿Por qué?
9. ¿Qué celular usa: táctil o de botones?
10. ¿Qué aplicaciones usa más seguido?
11. ¿Alguna vez sintió que no quiere "molestar" a su familia contándole algo suyo?
12. ¿Qué le frustra o incomoda de usar aplicaciones o el celular?

#### Segmento 2: Familiares a distancia

1. ¿Cuál es su nombre, edad y distrito de residencia?
2. ¿Cuál es su estado civil y con quién vive actualmente?
3. ¿A qué se dedica actualmente?
4. ¿Quién es su familiar adulto mayor que vive solo y hace cuánto no conviven?
5. ¿Con qué frecuencia se comunica con él/ella y por qué medio?
6. ¿Alguna vez sintió ansiedad por no saber cómo estaba? Cuénteme.
7. ¿Qué es lo que más le preocupa sobre su bienestar?
8. ¿Coordina con otros familiares para comunicarse con él/ella?
9. ¿Qué smartphone usa y qué apps usa con más frecuencia?
10. ¿Ha usado alguna app de monitoreo de salud o bienestar familiar?
11. Si pudiera ver diariamente cómo está su familiar sin llamarlo, ¿qué información le gustaría ver?
12. ¿Qué le generaría desconfianza en una app así?

<br>

### 2.2.2. Registro de entrevistas

<br>

### 2.2.3. Análisis de entrevistas

<br>

## 2.3. Needfinding
### 2.3.1. User Personas

<br>

### 2.3.2. User Task Matrix

<br>

### 2.3.3. User Journey Mapping

<br>

### 2.3.4. Empathy Mapping

<br>

### 2.3.5. Big Picture EventStorming

<br>

### 2.3.6. Ubiquitous Language

<br>

## 2.4. Requirements specification

### 2.4.1. User Stories

<br>

### 2.4.2. Impact Mapping

<br>

### 2.4.3. Product Backlog

<br>

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery

<br>

#### 2.5.1.2. Domain Message Flows Modeling

<br>

#### 2.5.1.3. Bounded Context Canvases

<br>

### 2.5.2. Context Mapping

<br>

### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams

<br>

#### 2.5.3.2. Software Architecture Container Level Diagrams

<br>

#### 2.5.3.3. Software Architecture Deployment Diagrams

<br>

## 2.6. Tactical-Level Domain-Driven Design
### 2.6.x. Bounded Context: <Bounded Context Name>

<br>

#### 2.6.x.1. Domain Layer

<br>

#### 2.6.x.2. Interface Layer

<br>

#### 2.6.x.3. Application Layer

<br>

#### 2.6.x.4 Infrastructure Layer

<br>

#### 2.6.x.5. Bounded Context Software Architecture Component Level Diagrams

<br>

#### 2.6.x.6. Bounded Context Software Architecture Code Level Diagrams

<br>

##### 2.6.x.6.1. Bounded Context Domain Layer Class Diagrams

<br>

##### 2.6.x.6.2. Bounded Context Database Design Diagram

<br>


# Capítulo III: Solution UI/UX Design
## 3.1. Product design
### 3.1.1. Style Guidelines

<br>

#### 3.1.1.1. General Style Guidelines

<br>

### 3.1.2. Information Architecture
#### 3.1.2.1. Organization Systems

<br>

#### 3.1.2.2. Labelling Systems

<br>

#### 3.1.2.3. SEO Tags and Meta Tags

<br>

#### 3.1.2.4. Searching Systems

<br>

#### 3.1.2.5. Navigation Systems

<br>

### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe

<br>

#### 3.1.3.2. Landing Page Mock-up

<br>

### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes

<br>

#### 3.1.4.2. Mobile Applications Wireflow Diagrams

<br>

#### 3.1.4.3. Mobile Applications Mock-ups

<br>

#### 3.1.4.4. Mobile Applications User Flow Diagrams

<br>

#### 3.1.4.5. Mobile Applications Prototyping

<br>

# Capítulo IV: Product Implementation & Validation
## 4. Product Implementation & Validation
## 4.1. Software Configuration Management
### 4.1.1. Software Development Environment Configuration

<br>

### 4.1.2. Source Code Management

<br>

### 4.1.3. Source Code Style Guide & Conventions

<br>

### 4.1.4. Software Deployment Configuration

<br>

## 4.2. Landing Page & Mobile Application Implementation
### 4.2.1. Sprint n
#### 4.2.1.1. Sprint Planning n

<br>

#### 4.2.1.2. Aspect Leaders and Collaborators

<br>

#### 4.2.1.3. Sprint Backlog n

<br>

#### 4.2.1.4. Development Evidence for Sprint Review

<br>

#### 4.2.1.5. Testing Suite Evidence for Sprint Review

<br>

#### 4.2.1.6. Execution Evidence for Sprint Review

<br>

#### 4.2.1.7. Services Documentation Evidence for Sprint Review

<br>

#### 4.2.1.8. Software Deployment Evidence for Sprint Review

<br>

#### 4.2.1.9. Team Collaboration Insights during Sprint

<br>

## 4.3. Validation Interviews
### 4.3.1. Diseño de Entrevistas

<br>

### 4.3.2. Registro de Entrevistas

<br>

### 4.3.3. Evaluaciones según heurísticas

<br>

# Conclusiones

<br>

## Recomendaciones

<br>

## Video App Validation

<br>

## Video About the product

<br>

## Video About the team

<br>

# Glosario

<br>

# Bibliografía

> Carrasco Freitas, M. (2026, 29 de mayo). Lima es el principal destino migratorio: más de 3 millones de peruanos llegaron desde otras regiones, según Censo 2025. Infobae. https://www.infobae.com/peru/2026/05/29/lima-es-el-principal-destrino-migratorio-mas-de-3-millones-de-peruanos-llegaron-desde-otras-regiones-segun-censo-2025/

> Instituto Nacional de Estadística e Informática. (2025a, 26 de marzo). El 42,0 % de los hogares del país tiene entre sus miembros a un adulto mayor. Gob.pe. https://www.gob.pe/institucion/inei/noticias/1133454-el-42-0-de-los-hogares-

> Instituto Nacional de Estadística e Informática. (2025b). Estadísticas de las tecnologías de información y comunicación en los hogares: informe técnico, enero-febrero-marzo 2025. https://www.inei.gob.pe/media/MenuRecursivo/boletines/informe-tecnico_tecnologiasdelainformacion_ene_feb_mar2025.pdf

> Organismo Supervisor de Inversión Privada en Telecomunicaciones. (2026). Erestel 2025: cada vez más hogares peruanos cuentan con un smartphone. https://www.osiptel.gob.pe/portal-del-usuario/noticias/erestel-2025-cada-vez-m%C3%A1s-hogares-peruanos-cuentan-con-un-smartphone-cu%C3%A1ntos-tienen/

> Gothelf, J., & Seiden, J. (2021). *Lean UX: Designing great products with agile teams* (3rd ed.). O'Reilly Media. https://www.oreilly.com/library/view/lean-ux-3rd/9781098116293/

<br>

# Anexos

<br>