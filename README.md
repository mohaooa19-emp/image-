[index.html](https://github.com/user-attachments/files/28178995/index.html)
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Précepteur - Cours à domicile en Guinée</title>
    <style>
        /* Styles Globaux */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f7f6;
            color: #333;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* 1. En-tête (Navigation) */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 10%;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        header .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #1a365d;
            letter-spacing: 1px;
        }
        header nav a {
            text-decoration: none;
            color: #4a5568;
            margin-left: 20px;
            font-weight: 500;
        }

        /* 2. Section Héros (Présentation) */
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 60px 10%;
            background: linear-gradient(135deg, #ffffff 0%, #e2e8f0 100%);
            gap: 40px;
            flex-wrap: wrap;
        }
        .hero-content {
            flex: 1;
            min-width: 300px;
            text-align: left;
        }
        .hero-content h1 {
            color: #1a365d;
            font-size: 3rem;
            margin: 0 0 20px 0;
        }
        .hero-content p {
            font-size: 1.25rem;
            color: #4a5568;
            line-height: 1.6;
        }
        .hero-image {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        .hero-image img {
            max-width: 100%;
            height: auto;
            border-radius: 12px;
        }

        /* 3. Section Offres */
        .offres {
            padding: 60px 10%;
            text-align: center;
        }
        .offres h2 {
            color: #1a365d;
            font-size: 2rem;
            margin-bottom: 40px;
        }
        .offres-grid {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        .carte-offre {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 10px 15px rgba(0,0,0,0.05);
            width: 300px;
            text-align: left;
            border-top: 5px solid #2b6cb0;
        }
        .carte-offre.secondaire {
            border-top-color: #319795;
        }
        .icone-offre {
            width: 60px;
            height: auto;
            margin-bottom: 15px;
        }
        .carte-offre h3 {
            color: #2d3748;
            margin: 10px 0;
            font-size: 1.3rem;
        }
        .carte-offre ul {
            padding-left: 20px;
            color: #4a5568;
            line-height: 1.8;
        }

        /* 4. Section Zone d'intervention */
        .zone {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 60px 10%;
            background-color: white;
            gap: 40px;
            flex-wrap: wrap;
        }
        .zone-text {
            flex: 1;
            min-width: 300px;
            text-align: left;
        }
        .zone-text h3 {
            color: #1a365d;
            font-size: 1.8rem;
            margin-top: 0;
        }
        .zone-text p {
            font-size: 1.1rem;
            color: #4a5568;
            line-height: 1.6;
        }
        .zone-map {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        .zone-map img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        /* 5. Section Appel (Footer) */
        footer {
            background-color: #feebc8;
            padding: 40px 20px;
            text-align: center;
            border-top: 2px solid #fbd38d;
        }
        footer p {
            font-size: 1.2rem;
            color: #744210;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .bouton-appel {
            display: inline-block;
            background-color: #dd6b20;
            color: white;
            text-decoration: none;
            padding: 15px 40px;
            font-size: 1.2rem;
            border-radius: 30px;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.2s, background-color 0.2s;
        }
        .bouton-appel:hover {
            background-color: #c05621;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>

    <!-- 1. En-tête (Header) -->
    <header>
        <div class="logo">PRECEPTEUR</div>
        <nav>
            <a href="#">Nos Offres</a>
            <a href="#">Zone</a>
            <a href="#">Tarifs</a>
            <a href="#">Inscription</a>
        </nav>
    </header>

    <!-- 2. Section Héros (Hero) -->
    <section class="hero">
        <div class="hero-content">
            <h1>PRECEPTEUR</h1>
            <p><strong>Un accompagnement scolaire personnalisé pour révéler le potentiel de chaque élève.</strong></p>
        </div>
        <div class="hero-image">
            <img src="http://googleusercontent.com/image_generation_content/2" alt="Enseignante et élèves Précepteur">
        </div>
    </section>

    <!-- 3. Section Offres -->
    <section class="offres">
        <h2>NOS OFFRES SUR-MESURE</h2>
        <div class="offres-grid">
            <!-- Carte Primaire -->
            <div class="carte-offre primaire">
                <img src="http://googleusercontent.com/image_generation_content/3" alt="Icône Primaire" class="icone-offre">
                <h3>NIVEAU PRIMAIRE 🎒</h3>
                <ul>
                    <li>Lecture & Écriture</li>
                    <li>Calcul & Mathématiques</li>
                    <li>Mise en confiance</li>
                </ul>
            </div>
            <!-- Carte Collège/Lycée -->
            <div class="carte-offre secondaire">
                <img src="http://googleusercontent.com/image_generation_content/4" alt="Icône Secondaire" class="icone-offre">
                <h3>COLLÈGE & LYCÉE 🎓</h3>
                <ul>
                    <li>Maths & Physique-Chimie</li>
                    <li>Français & Anglais</li>
                    <li>Méthodologie de révision</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- 4. Section Zone d'intervention -->
    <section class="zone">
        <div class="zone-text">
            <h3>NOTRE ZONE D'INTERVENTION</h3>
            <p>📍 Un précepteur chez vous, où que vous soyez : du centre-ville de <strong>Conakry</strong>, jusqu'à <strong>Dubréka</strong> et <strong>Coyah</strong>.</p>
        </div>
        <div class="zone-map">
            <img src="http://googleusercontent.com/image_generation_content/5" alt="Carte de la zone d'intervention Précepteur">
        </div>
    </section>

    <!-- 5. Appel à l'action (Footer) -->
    <footer>
        <p>Besoin d'un accompagnement sur-mesure pour votre enfant ?</p>
        <!-- Pensez à remplacer par votre vrai numéro à la place de tel:+224620000000 -->
        <a href="tel:+224620000000" class="bouton-appel">📞 APPELER UN CONSEILLER</a>
    </footer>

</body>
</html>
