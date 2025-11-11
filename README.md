# simulador-omnicanal
Simulador de Rentabilidad Omnicanal (HTML/JS)

Este repositorio contiene un modelo interactivo y autocontenido, construido en un solo archivo HTML, que funciona como un "Simulador tipo Excel". Está diseñado para permitir a estudiantes, analistas y profesionales de retail o marketing explorar y comparar la rentabilidad de diferentes segmentos de clientes.

En el panorama actual del retail, comprender la rentabilidad no es una tarea de un solo canal. Este simulador fue creado como una herramienta educativa para desmitificar la complejidad de la analítica omnicanal. Su objetivo principal es demostrar con datos cuantitativos una hipótesis clave: un cliente omnicanal (Segmento C) genera un valor superior y una rentabilidad a largo plazo en comparación con los clientes de un solo canal (Segmento A: Solo Tienda; Segmento B: Solo Online).

A través de este modelo interactivo, los usuarios pueden manipular variables clave y observar de primera mano el impacto en métricas fundamentales, creando un "caso de negocio" tangible para la transformación omnicanal.

🚀 Cómo Usar el Simulador

No se requiere instalación, dependencias ni servidor.

Descargar: Clona o descarga este repositorio.

Abrir: Simplemente abre el archivo modelo_rentabilidad_omnicanal.html en cualquier navegador web moderno (como Chrome, Firefox, Edge o Safari).

(Opcional: Si está alojado en GitHub Pages, puedes añadir el enlace aquí)

📊 Características Clave del Modelo

El simulador está dividido en cuatro pestañas principales para un análisis detallado:

Dashboard (Resumen): Una vista de alto nivel que consolida los resultados más críticos (CLV, Ratio CAC, Retención) en un solo lugar. Es ideal para presentaciones ejecutivas y para entender el "caso de negocio" de un vistazo.

Cálculo CLV y Ratio CAC: Esta pestaña permite un análisis profundo del valor del cliente. Los usuarios pueden modificar inputs como el Valor Promedio del Pedido (AOV), la Frecuencia de Compra y el Tiempo de Vida del Cliente para cada segmento. El modelo calcula automáticamente el CLV y, crucialmente, el Ratio CLV:CAC, la métrica de oro que determina la sostenibilidad de la adquisición de clientes.

Costos de Cumplimiento (Cost-to-Serve): La rentabilidad omnicanal depende de la eficiencia operativa. Este módulo compara el costo por pedido de tres métodos logísticos fundamentales: Envío desde Almacén (tradicional), Envío desde Tienda (Ship-from-Store) y BOPIS (Recoger en Tienda). Permite entender cómo el BOPIS puede reducir drásticamente los costos de última milla.

Tasa de Retención: La lealtad es un pilar de la rentabilidad. Esta sección modela la Tasa de Retención anual comparando cohortes. Los datos precargados demuestran la hipótesis de que los clientes omnicanal, al estar más integrados en el ecosistema de la marca, tienen una tasa de retención significativamente mayor.

💡 ¿Cómo funciona? (Stack Técnico)

Interfaz: Construida con HTML y Tailwind CSS para una UI limpia y responsiva que simula una hoja de cálculo.

Lógica: Toda la lógica de cálculo reside en JavaScript (vanilla) al final del archivo, sin dependencias externas.

Interactividad: Cambia cualquier valor en las celdas amarillas (inputs) y observa cómo todas las fórmulas (celdas grises y el dashboard) se recalculan automáticamente en tiempo real.

👥 Audiencia y Casos de Uso

Este simulador es una herramienta educativa diseñada para:

Estudiantes de Marketing Digital, Retail o Administración de Empresas que necesiten una herramienta práctica para aplicar conceptos teóricos.

Profesionales de Retail y eCommerce que necesiten crear un "caso de negocio" (business case) para justificar inversiones en tecnología omnicanal.

Analistas de Datos y Finanzas que busquen un modelo base para empezar a medir la segmentación de clientes en su propia empresa.
