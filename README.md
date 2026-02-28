<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio en GitHub Pages</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        header {
            background: #1e3a8a;
            color: white;
            text-align: center;
            padding: 25px;
        }

        .principal {
            display: flex;
            padding: 40px;
            gap: 40px;
            align-items: center;
        }

        .izquierda, .derecha {
            flex: 1;
        }

        .izquierda img {
            width: 100%;
            border-radius: 10px;
        }

        .descripcion {
            margin-top: 10px;
            font-size: 14px;
            color: #555;
        }

        .galeria {
            text-align: center;
            padding: 40px;
            background: #f4f4f4;
        }

        .imagenes {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .imagenes img {
            width: 200px;
            border-radius: 10px;
        }

        .subseccion {
            display: flex;
            padding: 40px;
            gap: 40px;
            align-items: center;
        }

        .subseccion img {
            width: 300px;
            border-radius: 10px;
        }

        footer {
            background: #1e3a8a;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .principal,
            .subseccion,
            .imagenes {
                flex-direction: column;
                text-align: center;
            }

            .imagenes img {
                width: 100%;
                max-width: 300px;
            }
        }
    </style>
</head>

<body>

    <!-- Encabezado -->
    <header>
        <h1>Mi Página Web en GitHub Pages</h1>
    </header>

    <!-- Sección principal -->
    <section class="principal">
        <div class="izquierda">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQh0-vZuyMvUJ5xEcL69qEbpSZigM7tRvnnhQ&s" alt="Imagen principal">
            <p class="descripcion">Imagina que hay una descripción de la imagen ubicada a la izquierda.</p>
        </div>

        <div class="derecha">
            <h2>Sección de Texto</h2>
            <p>
                Este es el contenido que aparece al lado derecho de la imagen.
                Aquí en este caso se mostrara fotos de gatos como ejemplo.
            </p>
        </div>
    </section>

    <!-- Galería -->
    <section class="galeria">
        <h2>Galería de Imágenes</h2>
        <div class="imagenes">
            <img src="https://media.4-paws.org/d/2/5/f/d25ff020556e4b5eae747c55576f3b50886c0b90/cut%20cat%20serhio%2002-1813x1811-720x719.jpg" alt="Imagen 1">
            <img src="https://www.alleycat.org/wp-content/uploads/2025/11/ow_head.jpg"Imagen 2">
            <img src="https://supertails.com/cdn/shop/articles/cat-3_d15c0254-8ccd-4beb-bc3e-1c988bcc5d51.jpg?v=1766559147" alt="Imagen 3">
        </div>
    </section>

    <!-- Sub sección -->
    <section class="subseccion">
        <div class="texto">
            <h3>Subtítulo de la Sección</h3>
            <p>
                Este texto es otro ejemplo que acompaña la imagen en esta sección.
                Con mas gatos!.
            </p>
        </div>
        <div class="imagen">
            <img src="https://th-thumbnailer.cdn-si-edu.com/ii_ZQzqzZgBKT6z9DVNhfPhZe5g=/fit-in/1600x0/filters:focal(1061x707:1062x708)/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer_public/55/95/55958815-3a8a-4032-ac7a-ff8c8ec8898a/gettyimages-1067956982.jpg" alt="Imagen secundaria">
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Mi Sitio Web | GitHub Pages</p>
    </footer>

</body>
</html>
