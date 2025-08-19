<!DOCTYPE html><html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GlasUp - Unieke glazen van drankflessen</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.3.2/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans"><!-- Header -->
<header class="bg-green-600 text-white p-6 text-center">
    <h1 class="text-3xl font-bold">GlasUp</h1>
    <p>Unieke glazen gemaakt van gerecyclede drankflessen</p>
</header>

<!-- Hero Section -->
<section class="p-10 text-center">
    <h2 class="text-2xl font-semibold mb-4">Duurzaam & Creatief</h2>
    <p class="mb-6">Elke fles krijgt een tweede leven als prachtig glas voor in huis.</p>
    <a href="#shop" class="bg-green-600 text-white px-6 py-2 rounded hover:bg-green-700">Bekijk ons assortiment</a>
</section>

<!-- Producten Section -->
<section id="shop" class="p-10 bg-white">
    <h2 class="text-2xl font-bold mb-6 text-center">Onze Producten</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="border rounded p-4 text-center shadow hover:shadow-lg transition">
            <img src="https://via.placeholder.com/150" alt="Whisky glas" class="mx-auto mb-4">
            <h3 class="font-semibold mb-2">Whisky Glas</h3>
            <p class="mb-2">Gemaakt van gerecyclede whiskyflessen.</p>
            <p class="font-bold">€12,50</p>
        </div>
        <div class="border rounded p-4 text-center shadow hover:shadow-lg transition">
            <img src="https://via.placeholder.com/150" alt="Wijn glas" class="mx-auto mb-4">
            <h3 class="font-semibold mb-2">Wijn Glas</h3>
            <p class="mb-2">Elegante glazen uit oude wijnflessen.</p>
            <p class="font-bold">€10,00</p>
        </div>
        <div class="border rounded p-4 text-center shadow hover:shadow-lg transition">
            <img src="https://via.placeholder.com/150" alt="Gin Glas" class="mx-auto mb-4">
            <h3 class="font-semibold mb-2">Gin Glas</h3>
            <p class="mb-2">Unieke set van gerecyclede ginflessen.</p>
            <p class="font-bold">€15,00</p>
        </div>
    </div>
</section>

<!-- Over Ons Section -->
<section class="p-10 text-center bg-gray-100">
    <h2 class="text-2xl font-bold mb-4">Over GlasUp</h2>
    <p>Bij GlasUp geloven we in duurzaamheid en creativiteit. Elke fles wordt met de hand omgetoverd tot een prachtig glas dat een verhaal vertelt.</p>
</section>

<!-- Contact Section -->
<section class="p-10 text-center">
    <h2 class="text-2xl font-bold mb-4">Contact</h2>
    <p class="mb-4">Heb je vragen of wil je een bestelling plaatsen? Stuur ons een bericht!</p>
    <form class="max-w-md mx-auto">
        <input type="text" placeholder="Naam" class="border p-2 mb-4 w-full rounded">
        <input type="email" placeholder="Email" class="border p-2 mb-4 w-full rounded">
        <textarea placeholder="Bericht" class="border p-2 mb-4 w-full rounded"></textarea>
        <button type="submit" class="bg-green-600 text-white px-6 py-2 rounded hover:bg-green-700">Verstuur</button>
    </form>
</section>

<!-- Footer -->
<footer class="bg-green-600 text-white p-6 text-center">
    &copy; 2025 GlasUp. Alle rechten voorbehouden.
</footer>

</body>
</html>
