**Responsive Web Design (RWD):**
Responsive Web Design es un enfoque de diseño web que busca proporcionar una experiencia de usuario óptima en una amplia variedad de dispositivos y tamaños de pantalla. La idea principal es adaptar dinámicamente la presentación y disposición de los elementos de una página web según las características del dispositivo en el que se está visualizando. Esto se logra mediante el uso de CSS y fluid grids, permitiendo que los elementos se reorganicen y redimensionen de manera flexible.

**Principales Enfoques de RWD:**
1. **Desktop First (Enfoque de Escritorio Primero):**
   - Se diseña inicialmente para dispositivos de escritorio.
   - Luego se aplican ajustes para adaptarse a dispositivos más pequeños.
   - Ejemplo: Se establecen estilos base para pantallas grandes y se utilizan media queries para modificar el diseño en pantallas más pequeñas.

2. **Mobile First (Enfoque Móvil Primero):**
   - Se diseña inicialmente para dispositivos móviles.
   - Luego se aplican ajustes para adaptarse a pantallas más grandes.
   - Ejemplo: Se establecen estilos base para pantallas pequeñas y se utilizan media queries para mejorar la presentación en pantallas más grandes.

**Media Queries:**
Las media queries son reglas de CSS que permiten aplicar estilos específicos según las características del dispositivo o del entorno de visualización. Se utilizan para adaptar la presentación de una página web a diferentes condiciones, como tamaño de pantalla, resolución, orientación del dispositivo, entre otros.

**Ejemplo Práctico de Media Queries (Desktop First):**
```css
/* Estilos generales para todas las pantallas */
body {
  font-size: 16px;
}

/* Media query para pantallas más pequeñas (ej. tablets) */
@media screen and (max-width: 1024px) {
  body {
    font-size: 14px;
  }
}
```

**Ejemplo Práctico de Media Queries (Mobile First):**
```css
/* Estilos generales para pantallas pequeñas (ej. móviles) */
body {
  font-size: 14px;
}

/* Media query para pantallas más grandes (ej. desktops) */
@media screen and (min-width: 768px) {
  body {
    font-size: 16px;
  }
}
```

En estos ejemplos, se ajusta el tamaño del texto según el tamaño de la pantalla utilizando media queries. En el primer ejemplo, se reduce el tamaño del texto en pantallas más pequeñas (Desktop First), mientras que en el segundo ejemplo, se aumenta el tamaño del texto en pantallas más grandes (Mobile First).