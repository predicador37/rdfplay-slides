Me gustaría comenzar citando una Comunicación de la Comisión Europea, sobre el Plan de Acción de Educación. En ella se advierte de que la transformación digital plantea un gran riesgo: el de una sociedad mal preparada para el futuro. El uso de las TIC se queda atrás en el ámbito educativo, tanto en adopción como en competencias. El Plan de Acción propone llegar a un mejor uso de la tecnología digital en el aprendizaje y en la enseñanza. En este contexto, la UNED y su departamento de IA, se proponen mejorar la calidad del sistema educativo y facilitar al alumnado la adquisición de competencias digitales concretas. Entre dichas competencias se encuentran conceptos como Web Semántica y datos enlazados que se explicarán a continuación.

--

El concepto de Web Semántica apareció por primera vez en un artículo de Tim Berners-Lee, el padre de la Web tradicional, en Scientific American (2001). En él se define la Web Semántica como aquella en la que agentes automáticos (programas de ordenador) pueden acceder y recopilar datos y su significado a través de hiperenlaces e inferencia lógica, en contraposición con una Web tradicional para humanos que consumen contenidos accediendo a documentos a través de hiperenlaces. 

Paralelamente, el concepto de linked open data o datos abiertos y enlazados propugna, por un lado, la publicación en línea de estos datos de forma estructurada, y por otro, el establecimiento de relaciones entre términos o conceptos en dichos datos. Es decir, publicar y enlazar conjuntos de datos internamente y entre sí.

Los pilares de la Web Semántica son tres: RDF (para el modelado de conocimiento mediante ternas o tripletas), XML (lenguaje de marcado para construir y definir documentos de estructura arbitraria) y las ontologías, que no son más que documentos que definen formalmente las relaciones entre los distintos conceptos. A estos pilares habría que añadir la tecnología de consulta SPARQL, que permite resolver consultas complejas entre grafos.

Por tanto, la Web Semántica no es más que una gran base de datos distribuida en varios grafos conectados; su principal característica en contraposición con las bases de datos relacionales es su flexibilidad para extender los modelos de datos.

--
En el ámbito académico la Web Semántica se encuadra dentro de la Gestión Avanzada de la Información y el Conocimiento. El cambio de paradigma frente al modelo relacional es brusco; su adopción fuera de la academia parece aún tímida (se cita el caso de los congresos de estadística semántica, este año con 4 papers para revisar). Esta dificultad en el aprendizaje e interiorización de la utilidad de las tecnologías de la Web Semántica motivan la idea de desarrollar este proyecto, que las acerque al público en general.

Entre los objetivos que se establecen están el desarrollar una herramienta sencilla de instalar y usar, que permita modelado y consulta con tecnologías de la Web Semántica, sea flexible y facilite el aprendizaje a los alumnos.
--

Se llevó a cabo de un estudio de trabajos previos donde se encontraron carencias: SPARQL playground solo permite consultas, rdfforms ni siquiera funcionaba correctamente y Protégé está orientada al modelado únicamente.

Se evaluaron distintas tecnologías y sus buques insigna en Web Semántica, llegando a la conclusión de que JS puro permitía interfaces de usuario ricas y nada más que un servidor web como infraestructura. Dentro de JS, RDF.js será el estándar a seguir (fusionará todas las bibliotecas usadas de una u otra manera en el proyecto), implementando el draft del W3C de la especificación de RDF en JS.

