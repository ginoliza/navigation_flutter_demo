## Navegación entre pantallas
`Navigator.push`, funciona como un `stack`. Cada pantalla va sobre otra

## Usando rutas
`Navigator.pushNamed()` toma un contexto y una ruta. Las rutas deben estar previamente definidas. `MaterialApp` admite `routes` para definirlas, y ya no se usa `home` sino `initialRoute` (no pueden existir ambas).