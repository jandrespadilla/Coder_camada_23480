# Mercadito Chick
Sitio web creado desde el esqueleto de html

## Paginas que componen el sitio

### Inicio - index.html

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Inicio</title>
</head>
<body>
    <header>
        <ul >
            <a href="./index.html"><li>Inicio</li></a>
            <a href="./pages/noticias.html"><li>Noticias</li></a>
            <a href="./pages/disenos.html"><li>Diseños</li></a>
            <a href="./pages/productos.html">
                <li>Productos</li>
                <ul>
                    <a href="./pages/productos/deco.html"><li>Deco</li></a>
                    <a href="./pages/productos/sustentable.html"><li>Sustentable</li></a>
                    <a href="./pages/productos/gourmet.html"><li>Gourmet</li></a>
                </ul>
            </a>
            <a href="./pages/contactanos.html"><li>Contactanos</li></a>
            <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
        </ul>
    </header>
    <main>
        <!-- Logo-->
        <div>
            <img src="logo.png" alt="Logo-MercaditoChic">
        </div>
         <!-- Imagenes-->
        <div>
            <table>
                <tr>
                    <td><img src="imagen-producto1.png" alt="Producto 1"></td>
                    <td><img src="imagen-producto2.png" alt="Producto 2"></td>
                    <td><img src="imagen-producto3.png" alt="Producto 3"></td>
                </tr>
                <tr>
                    <td>
                        <div>
                            Descripcion Producto 1
                        </div>
                    </td>
                    <td>
                        <div>
                            Descripcion Producto 2
                        </div>
                    </td>
                    <td>
                        <div>
                            Descripcion Producto 3
                        </div>
                    </td>
                </tr>
            </table>
        </div>
         <!-- Videos-->
        <div>
            <ul>
                <li>
                    <div>
                        <video src="video1.avi"></video>
                    </div>
                </li>
                <li>
                    <div>
                        <video src="video2.avi"></video>
                    </div>
                </li>
                <li>
                    <div>
                        <video src="video3.avi"></video>
                    </div>
                </li>                                
            </ul>
        </div>
        <div>
            <form action="mailero" method="post">
                <div>
                    <label for="mail-id">Mail</label>
                    <input type="text" name="mail-name" id="mail-id" placeholder="Escribi tu email">
                </div>
                <div>
                    <label for="name-id">Nombre</label>
                    <input type="text" name="name-name" id="name-id" placeholder="Escribi tu nombre">
                </div>
                <div>
                    <label for="mensaje-id">Mensaje</label>
                    <textarea name="mensaje-name" id="mensaje-id" cols="30" rows="10"></textarea>
                </div>
                <div>
                    <input type="submit" value="Enviar" name="enviar-id" id="enviar-id">
                    <input type="reset" value="Limpiar" name="limpiar-id" id="limpiar-id">
                </div>            
            </form>
        </div>
    </main>
    <footer>
        <div>
            <ul>
                <a href="./index.html"><li>Inicio</li></a>
                <a href="./pages/about.html"><li>Acerca</li></a>
                <a href="./pages/contactanos.html"><li>Contactanos</li></a>
                <a href="./pages/productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div> 
    </footer>
</body>
</html>
```
### Noticias - noticias.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Noticias</title>
</head>
<body>
    <header>
        <ul >
            <a href="../index.html"><li>Inicio</li></a>
            <a href="./noticias.html"><li>Noticias</li></a>
            <a href="./disenos.html"><li>Diseños</li></a>
            <a href="./productos.html">
                <li>Productos</li>
                <ul>
                    <a href="./productos/deco.html"><li>Deco</li></a>
                    <a href="./productos/sustentable.html"><li>Sustentable</li></a>
                    <a href="./productos/gourmet.html"><li>Gourmet</li></a>
                </ul>
            </a>
            <a href="./contactanos.html"><li>Contactanos</li></a>
            <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
        </ul>
    </header>
    <main>
        <h1>Articulos</h1>
        <div>
            <h2>Articulo 1</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque sed ea totam omnis facere eum, dolore repudiandae corporis molestias, aliquid eligendi tempore repellendus laborum vero praesentium voluptas culpa sit dolor?</p>
        </div>
        <div>
            <h2>Articulo 2</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque sed ea totam omnis facere eum, dolore repudiandae corporis molestias, aliquid eligendi tempore repellendus laborum vero praesentium voluptas culpa sit dolor?</p>
        </div>
        <div>
            <h2>Articulo 3</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque sed ea totam omnis facere eum, dolore repudiandae corporis molestias, aliquid eligendi tempore repellendus laborum vero praesentium voluptas culpa sit dolor?</p>
        </div>                
    </main>
    <footer>
        <div>
            <ul>
                <a href="../index.html"><li>Inicio</li></a>
                <a href="./about.html"><li>Acerca</li></a>
                <a href="./contactanos.html"><li>Contactanos</li></a>
                <a href="./productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>       
    </footer>
</body>
</html>
```
### Productos - productos.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Inicio</title>
</head>
<body>
    <header>    
        <ul >
            <a href="../index.html"><li>Inicio</li></a>
            <a href="./noticias.html"><li>Noticias</li></a>
            <a href="./disenos.html"><li>Diseños</li></a>
            <a href="./productos.html">
                <li>Productos</li>
                <ul>
                    <a href="./productos/deco.html"><li>Deco</li></a>
                    <a href="./productos/sustentable.html"><li>Sustentable</li></a>
                    <a href="./productos/gourmet.html"><li>Gourmet</li></a>
                </ul>
            </a>
            <a href="./contactanos.html"><li>Contactanos</li></a>
            <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
        </ul>
    </header>
    <main>
        <h1>Productos</h1>
        <div>
            <h2>Deco</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis blanditiis cupiditate omnis enim consectetur modi sed, placeat maiores saepe fugiat impedit repellendus deleniti, illum autem rem tempora voluptas. Quaerat, at?</p>
            <a href="./productos/deco.html"><img src="logo-deco.png" alt="logo-deco-png"></a>
        </div>
        <div>
            <h2>Sustentables</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis blanditiis cupiditate omnis enim consectetur modi sed, placeat maiores saepe fugiat impedit repellendus deleniti, illum autem rem tempora voluptas. Quaerat, at?</p>
            <a href="./productos/sustentable.html"><img src="logo-sustentable.png" alt="logo-sustentable-png"></a>
        </div>
        <div>
            <h2>Gourmet</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis blanditiis cupiditate omnis enim consectetur modi sed, placeat maiores saepe fugiat impedit repellendus deleniti, illum autem rem tempora voluptas. Quaerat, at?</p>
            <a href="./productos/gourmet.html"><img src="logo-gourmet.png" alt="logo-gourmet-png"></a>

        </div>
    </main>
    <footer>
        <div>
            <ul>
                <a href="../index.html"><li>Inicio</li></a>
                <a href="./about.html"><li>Acerca</li></a>
                <a href="./contactanos.html"><li>Contactanos</li></a>
                <a href="./productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>      
    </footer>
</body>
</html>
```
#### Productos - Deco - deco.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Productos Deco</title>
</head>
<body>
    <header>
        <ul >
            <a href="../../index.html"><li>Inicio</li></a>
            <a href="../noticias.html"><li>Noticias</li></a>
            <a href="../disenos.html"><li>Diseños</li></a>
            <a href="../productos.html">
                <li>Productos</li>
                <ul>
                    <a href="./deco.html"><li>Deco</li></a>
                    <a href="./sustentable.html"><li>Sustentable</li></a>
                    <a href="./gourmet.html"><li>Gourmet</li></a>
                </ul>
            </a>
            <a href="../contactanos.html"><li>Contactanos</li></a>
            <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
        </ul>
    </header>
    <main>
        <h1>Productos Deco</h1>
        <div>
            <h2>Producto 1</h2>
            <img src="imagine-producto1.png" alt="producto1">
            <p>Descripcion producto 1</p>
            <p>Precio producto 1</p>
        </div>
        <div>
            <h2>Producto 2</h2>
            <img src="imagine-producto2.png" alt="producto2">
            <p>Descripcion producto 2</p>
            <p>Precio producto 2</p>
        </div>
        <div>
            <h2>Producto 3</h2>
            <img src="imagine-producto3.png" alt="producto3">
            <p>Descripcion producto 3</p>
            <p>Precio producto 3</p>
        </div>        
    </main>
    <footer>
        <div>
            <ul>
                <a href="../../index.html"><li>Inicio</li></a>
                <a href="../about.html"><li>Acerca</li></a>
                <a href="../contactanos.html"><li>Contactanos</li></a>
                <a href="../productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>        
    </footer>
</body>
</html>
```
#### Productos - Gourmet - gourmet.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Productos Gourmet</title>
</head>
<body>
    <header>
        <ul >
            <a href="../../index.html"><li>Inicio</li></a>
            <a href="../noticias.html"><li>Noticias</li></a>
            <a href="../disenos.html"><li>Diseños</li></a>
            <a href="../productos.html">
                <li>Productos</li>
                <ul>
                    <a href="./deco.html"><li>Deco</li></a>
                    <a href="./sustentable.html"><li>Sustentable</li></a>
                    <a href="./gourmet.html"><li>Gourmet</li></a>
                </ul>
            </a>
            <a href="../contactanos.html"><li>Contactanos</li></a>
            <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
        </ul>
    </header>
    <main>
        <h1>Productos Gourmet</h1>
        <div>
            <h2>Producto 1</h2>
            <img src="imagine-producto1.png" alt="producto1">
            <p>Descripcion producto 1</p>
            <p>Precio producto 1</p>
        </div>
        <div>
            <h2>Producto 2</h2>
            <img src="imagine-producto2.png" alt="producto2">
            <p>Descripcion producto 2</p>
            <p>Precio producto 2</p>
        </div>
        <div>
            <h2>Producto 3</h2>
            <img src="imagine-producto3.png" alt="producto3">
            <p>Descripcion producto 3</p>
            <p>Precio producto 3</p>
        </div>  
    </main>
    <footer>
        <div>
            <ul>
                <a href="../../index.html"><li>Inicio</li></a>
                <a href="../about.html"><li>Acerca</li></a>
                <a href="../contactanos.html"><li>Contactanos</li></a>
                <a href="../productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>       
    </footer>
</body>
</html>
```
#### Productos - Sustentable - sustentable.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Productos Sustentables</title>
</head>
<body>
    <header>
        <ul >
            <a href="../../index.html"><li>Inicio</li></a>
            <a href="../noticias.html"><li>Noticias</li></a>
            <a href="../disenos.html"><li>Diseños</li></a>
            <a href="../productos.html">
                <li>Productos</li>
                <ul>
                    <a href="./deco.html"><li>Deco</li></a>
                    <a href="./sustentable.html"><li>Sustentable</li></a>
                    <a href="./gourmet.html"><li>Gourmet</li></a>
                </ul>
            </a>
            <a href="../contactanos.html"><li>Contactanos</li></a>
            <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
        </ul>
    </header>
    <main>
        <h1>Productos Sustentables</h1>
        <div>
            <h2>Producto 1</h2>
            <img src="imagine-producto1.png" alt="producto1">
            <p>Descripcion producto 1</p>
            <p>Precio producto 1</p>
        </div>
        <div>
            <h2>Producto 2</h2>
            <img src="imagine-producto2.png" alt="producto2">
            <p>Descripcion producto 2</p>
            <p>Precio producto 2</p>
        </div>
        <div>
            <h2>Producto 3</h2>
            <img src="imagine-producto3.png" alt="producto3">
            <p>Descripcion producto 3</p>
            <p>Precio producto 3</p>
        </div> 
    </main>
    <footer>
        <div>
            <ul>
                <a href="../../index.html"><li>Inicio</li></a>
                <a href="../about.html"><li>Acerca</li></a>
                <a href="../contactanos.html"><li>Contactanos</li></a>
                <a href="../productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>    
    </footer>
</body>
</html>
```
### Diceños - disenos.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Inicio</title>
</head>
<body>
    <header>
        <ul >
            <a href="../index.html"><li>Inicio</li></a>
            <a href="./noticias.html"><li>Noticias</li></a>
            <a href="./disenos.html"><li>Diseños</li></a>
            <a href="./productos.html">
                <li>Productos</li>
                <ul>
                    <a href="./productos/deco.html"><li>Deco</li></a>
                    <a href="./productos/sustentable.html"><li>Sustentable</li></a>
                    <a href="./productos/gourmet.html"><li>Gourmet</li></a>
                </ul>
            </a>
            <a href="./contactanos.html"><li>Contactanos</li></a>
            <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
        </ul>
    </header>
    <main>
        <h1>Diseños</h1>
        <div>
            <h2>Diseño 1</h2>
            <p>Descripcion diseño 1</p>
            <img src="imagine-diseno1.png" alt="disenos1">
        </div>
        <div>
            <h2>Diseño 2</h2>
            <p>Descripcion diseño 2</p>
            <img src="imagine-diseno2.png" alt="disenos2">
        </div> 
        <div>
            <h2>Diseño 3</h2>
            <p>Descripcion diseño 3</p>
            <img src="imagine-diseno3.png" alt="disenos3">
        </div>                
    </main>
    <footer>
        <div>
            <ul>
                <a href="../index.html"><li>Inicio</li></a>
                <a href="./about.html"><li>Acerca</li></a>
                <a href="./contactanos.html"><li>Contactanos</li></a>
                <a href="./productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>        
    </footer>
</body>
</html>
```
### Acerca  - about.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Acerca</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <a href="../index.html"><li>Inicio</li></a>
                <a href="./noticias.html"><li>Noticias</li></a>
                <a href="./disenos.html"><li>Diseños</li></a>
                <a href="./productos.html">
                    <li>Productos</li>
                    <ul>
                        <a href="./productos/deco.html"><li>Deco</li></a>
                        <a href="./productos/sustentable.html"><li>Sustentable</li></a>
                        <a href="./productos/gourmet.html"><li>Gourmet</li></a>
                    </ul>
                </a>
                <a href="./contactanos.html"><li>Contactanos</li></a>
                <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Acerca de nosotros</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem modi eius fugit eos consectetur facere ad itaque molestias unde sequi nobis quod laudantium, corporis repellendus obcaecati quibusdam quae laboriosam facilis?</p>
    </main>
    <footer>
        <div>
            <ul>
                <a href="../index.html"><li>Inicio</li></a>
                <a href="./about.html"><li>Acerca</li></a>
                <a href="./contactanos.html"><li>Contactanos</li></a>
                <a href="./productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>        
    </footer>
</body>
</html>
```
### Contactanos - conactanos.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MercaditoChic - Inicio</title>
</head>
<body>
    <header>
        <nav>
            <ul >
                <a href="../index.html"><li>Inicio</li></a>
                <a href="./noticias.html"><li>Noticias</li></a>
                <a href="./disenos.html"><li>Diseños</li></a>
                <a href="./productos.html">
                    <li>Productos</li>
                    <ul>
                        <a href="./productos/deco.html"><li>Deco</li></a>
                        <a href="./productos/sustentable.html"><li>Sustentable</li></a>
                        <a href="./productos/gourmet.html"><li>Gourmet</li></a>
                    </ul>
                </a>
                <a href="./contactanos.html"><li>Contactanos</li></a>
                <li><input type="button" value="Buscar"><input type="text" placeholder="Buscar" ></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Contactanos</h1>
        <form action="mailero" method="post">
            <div>
                <label for="mail-id">Mail</label>
                <input type="text" name="mail-name" id="mail-id" placeholder="Escribi tu email">
            </div>
            <div>
                <label for="name-id">Nombre</label>
                <input type="text" name="name-name" id="name-id" placeholder="Escribi tu nombre">
            </div>
            <div>
                <label for="mensaje-id">Mensaje</label>
                <textarea name="mensaje-name" id="mensaje-id" cols="30" rows="10"></textarea>
            </div>
            <div>
                <input type="submit" value="Enviar" name="enviar-id" id="enviar-id">
                <input type="reset" value="Limpiar" name="limpiar-id" id="limpiar-id">
            </div>            
        </form>
    </main>
    <footer>
        <div>
            <ul>
                <a href="../index.html"><li>Inicio</li></a>
                <a href="./about.html"><li>Acerca</li></a>
                <a href="./contactanos.html"><li>Contactanos</li></a>
                <a href="./productos.html"><li>Productos</li></a>
            </ul>
        </div>
        <div>
            Copyright Andres Padilla
        </div>         
    </footer>
</body>
</html>
```
