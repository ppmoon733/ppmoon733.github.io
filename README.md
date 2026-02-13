<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bautizo Leonardo Damián</title>

    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:wght@500;700&display=swap"
        rel="stylesheet">

    <style>
        :root {
            --azul: #1e78b7;
            --dorado: #9e7424;
            --texto: #1f1f1f;
            --fondo-capa: rgba(255, 255, 255, 0.55);
            --box-bg: rgba(255, 255, 255, 0.92);
        }

        /* MODO OSCURO */
        @media (prefers-color-scheme: dark) {
            :root {
                --azul: #8ec5ff;
                --dorado: #f1c76a;
                --texto: #f0f0f0;
                --fondo-capa: rgba(0, 0, 0, 0.55);
                --box-bg: rgba(20, 20, 20, 0.9);
            }
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            background: #000;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
        }

        /* TARJETA */
        .card {
            width: 100%;
            max-width: 720px;
            min-height: 100vh;
            margin: 0 auto;
            background: url("https://i.pinimg.com/736x/16/bd/af/16bdaf213363e7640a0a23d3e9e63c53.jpg") no-repeat center/cover; 
            box-shadow: 0 20px 60px rgba(0, 0, 0, .4);
        }

        /* CONTENIDO */
        .content {
            min-height: 100vh;
            padding: 70px 55px;
            text-align: center;
            background: var(--fondo-capa);
            color: var(--texto);
        }

        /* TEXTOS */
        .cross {
            font-size: 48px;
            color: var(--dorado);
            margin-bottom: 10px;
        }

        .title {
            font-family: 'Great Vibes', cursive;
            font-size: 64px;
            color: var(--azul);
        }

        .subtitle {
            font-size: 20px;
            margin: 12px 0 26px;
            font-weight: 600;
        }

        .name {
            font-family: 'Great Vibes', cursive;
            font-size: 46px;
            color: var(--dorado);
            margin: 12px 0;
        }

        .small {
            font-size: 18px;
            font-weight: 500;
        }

        .line {
            width: 150px;
            height: 2px;
            background: var(--azul);
            margin: 22px auto;
        }

        /* SECCIONES */
        .section-title {
            font-style: italic;
            font-size: 20px;
            color: var(--azul);
        }

        .section-name {
            font-size: 26px;
            font-weight: 600;
        }

        /* CAJAS */
        .boxes {
            display: flex;
            gap: 22px;
            margin: 36px 0;
        }

        .box {
            flex: 1;
            background: var(--box-bg);
            border-radius: 18px;
            padding: 20px;
        }

        .box h3 {
            color: var(--azul);
            font-size: 20px;
            margin-bottom: 6px;
        }

        .box p {
            font-size: 15px;
            line-height: 1.6;
        }

        /* BOTONES */
        .btn {
            display: inline-block;
            margin-top: 12px;
            padding: 11px 22px;
            background: var(--azul);
            color: #fff;
            border-radius: 25px;
            text-decoration: none;
            font-size: 14px;
            font-weight: 700;
        }

        /* CONFIRMACION */
        .confirm-title {
            font-family: 'Great Vibes', cursive;
            font-size: 34px;
            color: var(--dorado);
            margin-top: 14px;
        }

        .confirm-btns .btn {
            margin: 10px 8px;
        }

        /* CITA */
        .quote {
            font-style: italic;
            font-size: 16px;
            margin-top: 26px;
        }

        /* RESPONSIVE */
        @media(max-width:600px) {
            .content {
                padding: 45px 22px;
            }

            .title {
                font-size: 46px;
            }

            .name {
                font-size: 34px;
            }

            .boxes {
                flex-direction: column;
            }
        }
    </style>
</head>

<body>

    <div class="card">
        <div class="content">

            <div class="cross">✝</div>

            <div class="title">Bautizo</div>
            <div class="subtitle">Con la bendición de Dios</div>

            <div class="name">Leonardo Damián</div>

            <div class="small">recibirá el sacramento del</div>
            <div class="name" style="font-size:34px;">Santo Bautismo</div>

            <div class="line"></div>

            <div class="section-title">Padres</div>
            <div class="section-name">Adriana y Daniel</div>

            <div class="line"></div>

            <div class="section-title">Padrinos</div>
            <div class="section-name">Kristy y Andrés</div>

            <div class="line"></div>

            <p class="small">Te invitamos a acompañarnos en este momento tan especial</p>

            <div class="boxes">
                <div class="box">
                    <h3>⛪ Ceremonia Religiosa</h3>
                    <p>
                        12 pm.<br>
                        Parroquia Santa María de la Cruz<br>
                        Calle López Portillo 41<br>
                        Zapopan, Jal.
                    </p>
                    <a class="btn"
                        href="https://maps.google.com/?q=Parroquia+Santa+María+de+la+Cruz,+Calle+López+Portillo+41,+Francisco+Sarabia,+Zapopan,+Jal."
                        class="btn btn-outline" target="_blank">Ver ubicación</a>
                </div>

                <div class="box">
                    <h3>🌸 Recepción</h3>
                    <p>
                        1 pm.<br>
                        Terraza Valentina<br>
                        C. Francisco Villa 117<br>
                        Zapopan, Jal.
                    </p>
                    <a class="btn"
                        href="https://maps.google.com/?q=Terraza+Valentina,+C.+Francisco+Villa+117,+Francisco+Sarabia,+Zapopan,+Jal."
                        class="btn btn-outline" target="_blank">Ver ubicación</a>
                </div>
            </div>

            <div class="confirm-title">Confirma tu asistencia</div>

            <div class="confirm-btns">
                <a class="btn"
                    href="https://wa.me/523323409630?text=Hola%20😊%20Confirmo%20mi%20asistencia%20al%20bautizo%20de%20Leonardo%20Damián.%20Gracias%20por%20la%20invitación."
                    target="_blank">
                    Mamá - Adriana
                </a>
                <a class="btn"
                    href="https://wa.me/523319625592?text=Hola%20😊%20Confirmo%20mi%20asistencia%20al%20bautizo%20de%20Leonardo%20Damián.%20Gracias%20por%20la%20invitación."
                    target="_blank">
                    Papá - Daniel
                </a>

                <p class="quote">
                    “Yo te bautizo en el nombre del Padre,<br>
                    del Hijo y del Espíritu Santo”
                </p>

                <div class="cross">✝</div>

            </div>
        </div>

</body>

</html>
