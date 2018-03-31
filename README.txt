skilltree

>> árbol de ficheros:

	skilltree
	├── app.py
	├── README.txt
	├── static
	│   ├── css
	│   │   └── styles.css
	│   ├── img
	│   │   ├── background.jpg
	│   │   ├── lenguajes
	│   │   │   ├── css
	│   │   │   │   └── csslogo.png
	│   │   │   ├── html
	│   │   │   │   └── htmllogo.png
	│   │   │   ├── javascript
	│   │   │   │   └── jslogo.png
	│   │   │   ├── jquery
	│   │   │   │   └── jquerylogo.png
	│   │   │   └── nodejs
	│   │   │       └── nodejslogo.png
	│   │   └── misc
	│   │       └── musthave.png
	│   └── js
	└── templates
	    └── index.html

>> sobre flask:

	playlist de CodeNoSchool en español:

	https://tinyurl.com/flask-tut-es

	cada video encapsula un tema, entre ellos:
		
		cómo setear flask (windows / unix)
		cómo correr el webserver
		cómo validar rutas
		cómo enlazar backend con frontend

	observación:
	
		flask usa jinja2 para preprocesar html

		jinja2 permite comunicar funciones y valores de un archivo python para ser usadas en html, pero jinja2 también permite crear macros, bloques y condicionales dentro del html, para evitar código duplicado.

		si en un archivo html se encuentran estructuras como se muestran abajo, se trata de jinja2:



		{{ función o valor }}



		o bien:



		{% cosa %}
	
		...
	
		{% endcosa %}
