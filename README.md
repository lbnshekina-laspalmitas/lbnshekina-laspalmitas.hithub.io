
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lo Esencial para Conectar: Guía de Amistades Geniales</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #F8F4FF;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .section-card {
            background-color: white;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.05);
            padding: 2.5rem;
            margin-bottom: 3rem;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 2px solid;
            border-image: linear-gradient(45deg, #FF69B4, #8A2BE2) 1;
        }
        .section-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 35px rgba(0, 0, 0, 0.1);
        }
        .flow-arrow {
            font-size: 2.5rem;
            color: #8A2BE2;
            margin: 0 1rem;
            align-self: center;
        }
    </style>
</head>
<body class="text-gray-800">

    <div class="container mx-auto p-4 md:p-8 max-w-5xl">

        <header class="text-center mb-16">
            <h1 class="text-4xl md:text-6xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-pink-500 to-purple-600 mb-4">Lo Esencial para Conectar</h1>
            <p class="text-lg md:text-xl text-purple-700 font-medium">Una Guía para Amistades Geniales y Cero Miedo</p>
        </header>

        <main>
            <section id="slide-1" class="section-card text-center bg-purple-600 text-white">
                <h2 class="text-3xl font-bold mb-2">Lámina 1: El Fundamento de Todo</h2>
                <p class="text-lg">Las conexiones profundas no son un extra, ¡son la base de todo! Vamos a ver cómo construir amistades que duren de verdad, sin importar los obstáculos del camino.</p>
            </section>

            <section id="slide-2" class="section-card text-center">
                <h2 class="text-3xl font-bold text-purple-700 mb-4">Lámina 2: El Gran "Desconector": El Miedo</h2>
                <p class="text-lg mb-4">El miedo es el peor enemigo de las amistades. Miedo a que nos rechacen, a que nos hagan daño, a mostrarnos como somos. Esto nos hace retroceder y poner muros, impidiendo que la magia de una amistad suceda.</p>
                <div class="bg-purple-100 text-purple-800 p-4 rounded-xl">
                    <p class="font-bold text-xl">"Dios no nos dio un espíritu de temor, sino de poder, amor y autodisciplina."</p>
                    <p class="text-right mt-2 font-medium">- 2 Timoteo 1:7</p>
                </div>
            </section>

            <section id="slide-3" class="section-card grid md:grid-cols-2 gap-8 items-center">
                <div>
                    <h2 class="text-3xl font-bold text-purple-700 mb-4">Lámina 3: Efectos del Miedo (Parte 1)</h2>
                    <p class="text-lg mb-4">El miedo nos afecta en la vida real. Primero, nos vuelve a la defensiva, haciendo que reaccionemos mal a cualquier crítica. Segundo, nos hace distantes, evitando que la gente se nos acerque de verdad.</p>
                    <ul class="list-disc list-inside text-lg space-y-2">
                        <li><span class="font-bold">Modo "defensa":</span> Reaccionamos ante cualquier "tirón de orejas".</li>
                        <li><span class="font-bold">Modo "distancia":</span> No mostramos nuestros verdaderos sentimientos.</li>
                    </ul>
                </div>
                <div>
                    <div class="chart-container">
                        <canvas id="fearEffectsChart"></canvas>
                    </div>
                </div>
            </section>
            
            <section id="slide-4" class="section-card grid md:grid-cols-2 gap-8 items-center">
                 <div>
                    <div class="chart-container">
                        <canvas id="insecurityControlChart"></canvas>
                    </div>
                </div>
                <div class="md:text-right">
                    <h2 class="text-3xl font-bold text-purple-700 mb-4">Lámina 4: Efectos del Miedo (Parte 2)</h2>
                    <p class="text-lg mb-4">El miedo nos vuelve controladores. Cuanto más inseguros nos sentimos, más queremos controlar todo a nuestro alrededor, ¡y eso ahuyenta a cualquiera!</p>
                     <p class="text-lg font-bold">Modo "control": la inseguridad nos hace querer dominarlo todo.</p>
                </div>
            </section>
            
            <section id="slide-5" class="section-card">
                <h2 class="text-3xl font-bold text-purple-700 mb-6 text-center">Lámina 5: La Solución a Prueba de Miedo</h2>
                <p class="text-lg text-center mb-8">La respuesta al miedo no es esconderse, es activar un espíritu diferente que nos da Dios. Se compone de tres súper poderes que nos dan la confianza para conectar de verdad.</p>
                <div class="flex flex-col md:flex-row justify-around text-center gap-6">
                    <div class="flex-1 p-6 bg-purple-100 rounded-xl shadow">
                        <div class="text-4xl mb-3">💪</div>
                        <h3 class="text-2xl font-bold text-purple-800">Poder</h3>
                        <p>La fuerza para dar el primer paso, aunque te dé pánico.</p>
                    </div>
                    <div class="flex-1 p-6 bg-pink-100 rounded-xl shadow">
                         <div class="text-4xl mb-3">💖</div>
                        <h3 class="text-2xl font-bold text-pink-800">Amor</h3>
                        <p>La gasolina para conectar, más fuerte que el miedo al rechazo.</p>
                    </div>
                    <div class="flex-1 p-6 bg-yellow-100 rounded-xl shadow">
                         <div class="text-4xl mb-3">🕹️</div>
                        <h3 class="text-2xl font-bold text-yellow-800">Autodisciplina</h3>
                        <p>El control para que tus emociones no te dominen.</p>
                    </div>
                </div>
            </section>

            <section id="slide-6" class="section-card">
                <h2 class="text-3xl font-bold text-purple-700 mb-4 text-center">Lámina 6: El Pilar que Sostiene Todo: El Compromiso</h2>
                <p class="text-lg text-center mb-8">El compromiso es lo único que mantiene una amistad unida cuando los tiempos se ponen feos. No es solo un sentimiento, es una decisión de no rendirte, ¡sin importar qué!</p>
                <div class="text-center">
                    <p class="text-5xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-pink-500 to-purple-600">1</p>
                    <p class="text-2xl text-purple-700">Un compromiso ante Dios es la clave.</p>
                </div>
                 <p class="text-center mt-6 text-lg italic">"Tener amigos es genial, y un amigo de verdad es mejor que un hermano." - Proverbios 18:24</p>
            </section>
            
            <section id="slide-7" class="section-card">
                 <h2 class="text-3xl font-bold text-purple-700 mb-4 text-center">Lámina 7: Calidad vs. Cantidad</h2>
                 <p class="text-lg text-center mb-8">En la era de las redes, es fácil acumular miles de "amigos". Pero la verdad es que la vida no necesita muchos, sino unos pocos que sean de verdad. ¡Invierte tu energía en cultivar intimidad, no en socializar sin rumbo!</p>
                 <div class="chart-container">
                    <canvas id="qualityVsQuantityChart"></canvas>
                </div>
                 <div class="mt-8 bg-purple-100 text-purple-800 p-4 rounded-xl">
                    <p class="font-bold text-xl">Tus 500 amigos de IG no van a estar ahí cuando los necesites, pero un amigo de verdad sí.</p>
                </div>
            </section>

            <section id="slide-8" class="section-card">
                <h2 class="text-3xl font-bold text-purple-700 mb-6 text-center">Lámina 8: El Camino Hacia una Amistad Real</h2>
                 <p class="text-lg text-center mb-8">Las conexiones que valen la pena no son por casualidad. Es un proceso que empieza con una decisión y se cultiva con esfuerzo. ¡Aquí está el mapa!</p>
                <div class="flex flex-col md:flex-row items-center justify-center text-center">
                    <div class="p-4 bg-purple-100 rounded-xl shadow">
                        <h3 class="text-xl font-bold text-purple-800">1. Compromiso</h3>
                        <p>Decide estar ahí para el otro.</p>
                    </div>
                    <div class="flow-arrow hidden md:block">➡️</div>
                     <div class="flow-arrow md:hidden text-3xl my-4">⬇️</div>
                    <div class="p-4 bg-purple-100 rounded-xl shadow">
                        <h3 class="text-xl font-bold text-purple-800">2. Esfuerzo</h3>
                        <p>Invierte tiempo y energía para conectar.</p>
                    </div>
                     <div class="flow-arrow hidden md:block">➡️</div>
                     <div class="flow-arrow md:hidden text-3xl my-4">⬇️</div>
                    <div class="p-4 bg-purple-100 rounded-xl shadow">
                        <h3 class="text-xl font-bold text-purple-800">3. Intimidad</h3>
                        <p>La recompensa: una conexión que lo es todo.</p>
                    </div>
                </div>
            </section>

            <section id="slide-9" class="section-card bg-purple-600 text-white text-center">
                <h2 class="text-3xl font-bold mb-4">Lámina 9: Conclusión y Next Steps</h2>
                <p class="text-lg mb-6">Conectar de verdad requiere valor para superar el miedo y dedicación. No necesitas mil "amigos", solo unos pocos que valgan oro. ¡Empieza hoy a cultivar esas amistades que te cambiarán la vida!</p>
                <div class="text-left inline-block">
                    <ul class="list-disc list-inside text-lg space-y-2">
                        <li>Cambia el miedo por poder, amor y autodisciplina.</li>
                        <li>Honra tus compromisos, son el pilar.</li>
                        <li>Busca calidad, no cantidad en tus amigos.</li>
                    </ul>
                </div>
            </section>

        </main>
    </div>

<script>
    const tooltipTitleCallback = (tooltipItems) => {
        const item = tooltipItems[0];
        let label = item.chart.data.labels[item.dataIndex];
        return Array.isArray(label) ? label.join(' ') : label;
    };

    const wrapLabel = (label) => {
        const maxLength = 16;
        if (label.length <= maxLength) return label;
        const words = label.split(' ');
        let lines = [];
        let currentLine = '';
        for (const word of words) {
            if ((currentLine + ' ' + word).trim().length > maxLength) {
                lines.push(currentLine.trim());
                currentLine = word;
            } else {
                currentLine = (currentLine + ' ' + word).trim();
            }
        }
        lines.push(currentLine.trim());
        return lines;
    };
    
    const colors = {
        purple: '#8A2BE2',
        pink: '#FF69B4',
        yellow: '#F59E0B',
        gray: '#6B7280'
    };
    
    new Chart(document.getElementById('fearEffectsChart'), {
        type: 'doughnut',
        data: {
            labels: ['Modo "defensa"', 'Modo "distancia"'],
            datasets: [{
                label: 'Efectos del Miedo',
                data: [50, 50],
                backgroundColor: [colors.pink, colors.purple],
                borderColor: '#FFFFFF',
                borderWidth: 4
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: { position: 'top' },
                title: { display: true, text: 'Principales Reacciones Impulsadas por el Miedo', font: { size: 16 } },
                tooltip: { callbacks: { title: tooltipTitleCallback } }
            }
        }
    });

    new Chart(document.getElementById('insecurityControlChart'), {
        type: 'bar',
        data: {
            labels: ['Confiado', 'Un poco Inseguro', 'Súper Inseguro'],
            datasets: [{
                label: 'Necesidad de Control',
                data: [15, 60, 95],
                backgroundColor: [colors.yellow, colors.pink, colors.purple],
                borderRadius: 5
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            scales: { y: { beginAtZero: true, max: 100 } },
            plugins: {
                legend: { display: false },
                title: { display: true, text: 'Inseguridad vs. Necesidad de Control', font: { size: 16 } },
                tooltip: { callbacks: { title: tooltipTitleCallback } }
            }
        }
    });

    new Chart(document.getElementById('qualityVsQuantityChart'), {
        type: 'bar',
        data: {
            labels: [wrapLabel('Muchos Amigos (Cantidad)'), wrapLabel('Pocos Amigos (Calidad)')],
            datasets: [
                {
                    label: 'Satisfacción',
                    data: [45, 90],
                    backgroundColor: colors.purple,
                    borderColor: colors.purple,
                    borderWidth: 1,
                    borderRadius: 5
                },
                {
                    label: 'Esfuerzo invertido',
                    data: [20, 75],
                    backgroundColor: colors.pink,
                    borderColor: colors.pink,
                    borderWidth: 1,
                    borderRadius: 5
                }
            ]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            scales: {
                y: {
                    beginAtZero: true,
                    max: 100,
                    title: { display: true, text: 'Nivel (0-100)' }
                }
            },
            plugins: {
                legend: { position: 'top' },
                title: { display: true, text: 'Calidad vs. Cantidad de Amistades', font: { size: 16 } },
                tooltip: { callbacks: { title: tooltipTitleCallback } }
            }
        }
    });

</script>
</body>
</html>
