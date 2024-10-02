## 1. Ejercicio sobre usabilidad en los textos

### El siguiente fragmentos de código HTML contiene varios errores de usabilidad relacionados con la usabilidad de los textos. Corregimos estos errores para mejorar la experiencia del usuario y la accesibilidad de los textos.

#### - Organización de la información: Se usaron encabezados para dividir el contenido en secciones claras.

 ```
    - <h3>La Revolución de la informática</h3>

    - <h1>La Revolución de la informática</h1>
 ```


#### - Claridad y sencillez: Se simplificó el texto para hacerlo más fácil de entender y se eliminaron las palabras complicadas.
#### - Mejor legibilidad: Se cambió la fuente a Arial y se aumentó el tamaño a 16px para que sea más fácil de leer

```
- <p>El campo de la ciberseguridad ha experimentado un cambio de paradigma significativo, pasando de enfoques reactivos a proactivos, donde la detección de amenazas se basa en algoritmos heurísticos
y análisis de comportamiento para anticipar y mitigar posibles vulnerabilidades antes de que sean explotadas.</p>

 - <p>El campo de la ciberseguridad ha experimentado un cambio de paradigma significativo, pasando de enfoques reactivos a proactivos, donde la detección de amenazas se basa en algoritmos heurísticos
y análisis de comportamiento para anticipar y mitigar posibles vulnerabilidades antes de que sean explotadas.</p>
```

#### - Listas y viñetas: Se presentó información importante en listas con viñetas para que sea más fácil de seguir.

```
  Implementar firewalls robustos
  Utilizar software antivirus actualizado
  Capacitar a los empleados en prácticas de seguridad

<ul>
    <li>Implementar firewalls robustos</li>
    <li>Utilizar software antivirus actualizado</li>
    <li>Capacitar a los empleados en prácticas de seguridad</li>
  </ul>
```
  
#### - Corrección de errores: Se revisó el texto para corregir errores de ortografía y gramática y se cambio el tamaño para facilitar la lectura.
#### - Accesibilidad: Se tuvo en cuenta que el texto sea fácil de leer para personas con problemas visuales y se acortaron los párrafos para facilitar la lectura.

```
- <h4>Nuevas tecnologías</h4>
  <p style="font-size: 9px;">Las nuevas tecnologías como la computación cuántica y la inteligencia artificial están transformando la manera en que procesamos la información y tomamos decisiones.</p>

- <h2>Nuevas tecnologías</h2>
  <p>Las nuevas tecnologías como la computación cuántica y la inteligencia artificial están transformando la manera en que procesamos la información y tomamos decisiones.</p>
```

#### - Enlaces más claros: Se mejoró la redacción de los enlaces, evitando frases como "pinche aquí."

```
 - <p>Para saber más <a href="#">pinche aquí</a></p>
  
 - <p><a href="#">Más información sobre la revolución de la informática</a></p>
```
 

### El siguiente fragmentos de código CSS contiene varios errores de usabilidad relacionados con la usabilidad de los textos. Corregimos estos errores para mejorar la experiencia del usuario y la accesibilidad de los textos.

#### - Mejor legibilidad: Se cambió la fuente a Arial y sans-serif se aumentó el tamaño a 16px  y se cambio el color de fondo y texto para que sea más fácil de leer

```
 body {
  background-color: #f0f0f0;
  color: #888888;
  font-family: 'Times New Roman', Times, serif;
  font-size: 12px;
  max-width: 600px;
  margin: 0 auto;
}


body {
  background-color: #ffffff;
  color: #333333;
  font-family: Arial, sans-serif;
  font-size: 16px;
  line-height: 1.6;
  max-width: 600px;
  margin: 0 auto;
}
```

#### - Organización de la información: Se usaron encabezados para dividir el contenido en secciones claras.

```
h1 {
  font-size: 24px;
  text-transform: uppercase;
}

h1, h2 {
  color: #222222;
  margin-top: 20px;
}
 ```

#### - Accesibilidad: Se tuvo en cuenta que el texto sea fácil de leer y se cambio el color y estilo.

```
a {
  color: #0000ff;
}

a {
  color: #0066cc;
  text-decoration: underline;
}
 ```


### - Mejorar el tamaño de letra, y se mejoro el formulario y mostrando una señal de * de campo importante 

```
 .content-box {
  background-color: #999999;
  color: #aaaaaa;
  padding: 10px;
  margin: 20px 0;
}

}
.form-field input[type="text"]:focus,
.form-field textarea:focus {
  border.submit-button {
  background-color: #007BFF;
  color: #fff;
  border: none;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  border-radius: 4px;
}
.submit-button:hover {
  background-color: #0056b3;
}
 ```

## 2. Ejercicio sobre usabilidad en formularios

### El siguiente fragmento de código HTML contiene varios errores de usabilidad en un formulario. Corrige estos errores para mejorar la experiencia del usuario al interactuar con el formulario, teniendo en cuenta también la accesibilidad en los formularios.


#### - Organización de la información: Se usaron encabezados para dividir el contenido en secciones claras.

``` <h1>Formulario</h1>
  <h1>Formulario de Contacto</h1>
``` 
 
#### - Formato claro y orden lógico: Los campos están organizados en un orden lógico con 

  ```
<label>Nombre</label>

<label for="nombre">Nombre <span class="required">*</span></label>
   ```    

#### - Etiquetas Descriptivas: Las etiquetas de los campos son más descriptivas, utilizando atributos for e id para mejorar la accesibilidad.
  ```
  <input type="text" name="nombre">
   
  <input type="text" id="nombre" name="nombre" required placeholder="Ingresa tu nombre completo">

```
 
#### - Campos Obligatorios: Los campos que son obligatorios están claramente marcados con un asterisco rojo, lo que ayuda al usuario a identificar qué información es necesaria.
  
  ```
   <label>Correo electrónico</label>
   <input type="text" name="email">
```

  ```
   <label for="email">Correo electrónico <span class="required">*</span></label>
   <input type="email" id="email" name="email" required placeholder="nombre@ejemplo.com">
```
  
#### - Formato Claro y Orden Lógico: Los campos están organizados de manera lógica y con suficiente espacio entre ellos para facilitar la navegación.
 
   ```
    <label>Teléfono</label>
     <input type="text" name="telefono">
 
    <div class="form-field">
      <label>Mensaje</label>
      <textarea name="mensaje"></textarea>
    </div>
 ```
#### - Ayuda Contextual: Se ha añadido ayuda contextual mediante el uso de placeholder dentro de los campos y mensajes de ayuda para guiar al usuario sobre el formato de la información que debe ingresar.
 
   ```
    <div class="form-field">
      <label for="telefono">Teléfono</label>
      <input type="tel" id="telefono" name="telefono" placeholder="123-456-7890">
    </div>
    <div class="form-field">
      <label for="mensaje">Mensaje</label>
      <textarea id="mensaje" name="mensaje" rows="5" placeholder="Escribe tu mensaje aquí"></textarea>
    </div>
```
  
### El siguiente fragmento de código CSS contiene varios errores de usabilidad en un formulario. Corrige estos errores para mejorar la experiencia del usuario al interactuar con el formulario, teniendo en cuenta también la accesibilidad en los formularios.

