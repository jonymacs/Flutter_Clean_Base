# Flutter_Clean_Base
A Flutter clean base for futures projects.

Coments on base:

RecipeApp
1. El build()método de un widget es el punto de entrada para componer otros widgets para crear un nuevo widget.
2. Un tema determina aspectos visuales como el color. El valor predeterminado ThemeDatamostrará los valores predeterminados de material estándar.
3. MaterialAppusa Material Design y es el widget que se incluirá en RecipeApp.
4. El título de la aplicación es una descripción que usa el dispositivo para identificar la aplicación. La interfaz de usuario no mostrará esto.
5. Reemplaza el esquema de color con una copia actualizada le permite cambiar los colores de la aplicación. Aquí, el color primario es Colors.greyy el color secundario es Colors.black.
6. Esto todavía usa el mismo MyHomePagewidget que antes, pero ahora, actualizó el título y lo mostró en el dispositivo.

MyHomePageState (Class)
1. A Scaffoldproporciona la estructura de alto nivel para una pantalla. En este caso, estás usando dos propiedades.
2. AppBarobtiene una propiedad de título mediante el uso de un Textwidget que ha titlepasado de home: MyHomePage(title: 'Recipe Calculator')en el paso anterior.
3. bodytiene SafeArea, lo que evita que la aplicación se acerque demasiado a las interfaces del sistema operativo, como la muesca o áreas interactivas como el indicador de inicio en la parte inferior de algunas pantallas de iOS.
4. SafeAreatiene un childwidget, que es un Containerwidget vacío .
