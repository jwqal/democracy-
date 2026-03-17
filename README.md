
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The T-Ward Action Plan | Reclaiming Mulund in 2026</title>
    <meta name="description" content="Read the grassroots policy plan to fix Mulund's traffic, footpaths, and water issues. Join the citizen-led movement for the 2026 BMC Elections.">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Space+Grotesk:wght@400;700&display=swap" rel="stylesheet">

    <style>
        /* CSS Variables for our Campaign Palette */
        :root {
            --electric-purple: #8A2BE2;
            --neon-yellow: #E6FF00;
            --deep-black: #111111;
            --pure-white: #FFFFFF;
            --font-display: 'Bebas Neue', sans-serif;
            --font-body: 'Space Grotesk', sans-serif;
        }

        /* Global Reset & Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--deep-black);
            color: var(--pure-white);
            font-family: var(--font-body);
            line-height: 1.6;
            overflow-x: hidden;
        }

        h1, h2, h3 {
            font-family: var(--font-display);
            letter-spacing: 1px;
            text-transform: uppercase;
            line-height: 1.1;
        }

        /* Brutalist Button Styles */
        .btn {
            display: inline-block;
            background-color: var(--neon-yellow);
            color: var(--deep-black);
            font-family: var(--font-display);
            font-size: 1.5rem;
            padding: 15px 30px;
            text-decoration: none;
            border: 4px solid var(--deep-black);
            box-shadow: 6px 6px 0px var(--electric-purple);
            transition: all 0.2s ease;
            cursor: pointer;
            text-transform: uppercase;
        }

        .btn:hover {
            transform: translate(4px, 4px);
            box-shadow: 2px 2px 0px var(--electric-purple);
        }

        .btn-secondary {
            background-color: var(--electric-purple);
            color: var(--pure-white);
            box-shadow: 6px 6px 0px var(--neon-yellow);
        }

        /* Hero Section - The Front Cover */
        .hero {
            min-height: 90vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 5%;
            background-color: var(--deep-black);
            border-bottom: 10px solid var(--neon-yellow);
            background-image: radial-gradient(var(--electric-purple) 1px, transparent 1px);
            background-size: 20px 20px; /* Gives a subtle dotted/risograph texture */
        }

        .hero h1 {
            font-size: clamp(4rem, 10vw, 8rem);
            color: var(--neon-yellow);
            text-shadow: 4px 4px 0px var(--electric-purple);
            margin-bottom: 10px;
        }

        .hero p.sub-header {
            font-size: clamp(1.2rem, 3vw, 2rem);
            max-width: 800px;
            margin-bottom: 40px;
            background-color: var(--electric-purple);
            color: var(--pure-white);
            display: inline-block;
            padding: 10px 20px;
            transform: rotate(-1deg);
        }

        .hero-actions {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        /* The Manifesto / Policy Section */
        .manifesto {
            padding: 8% 5%;
            background-color: var(--pure-white);
            color: var(--deep-black);
        }

        .policy-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            margin-top: 50px;
        }

        /* High-contrast policy cards */
        .policy-card {
            background-color: var(--pure-white);
            border: 6px solid var(--deep-black);
            padding: 30px;
            box-shadow: 12px 12px 0px var(--electric-purple);
            transition: transform 0.2s;
        }

        .policy-card:nth-child(even) {
            box-shadow: 12px 12px 0px var(--neon-yellow);
        }

        .policy-card:hover {
            transform: translateY(-5px);
        }

        .policy-card h2 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            border-bottom: 4px solid var(--deep-black);
            padding-bottom: 10px;
        }

        .policy-card ul {
            margin-top: 20px;
            padding-left: 20px;
        }

        .policy-card li {
            margin-bottom: 15px;
            font-weight: 700;
        }

        /* Documentary Section */
        .media-section {
            padding: 8% 5%;
            background-color: var(--electric-purple);
            border-top: 10px solid var(--deep-black);
            border-bottom: 10px solid var(--deep-black);
        }

        .media-section h3 {
            font-size: 3.5rem;
            color: var(--neon-yellow);
            text-shadow: 3px 3px 0px var(--deep-black);
            margin-bottom: 10px;
        }

        .media-section p {
            font-size: 1.2rem;
            margin-bottom: 40px;
            font-weight: bold;
        }

        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        /* Placeholders for documentary videos */
        .video-placeholder {
            background-color: var(--deep-black);
            aspect-ratio: 16 / 9;
            border: 4px solid var(--neon-yellow);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--neon-yellow);
            font-family: var(--font-display);
            font-size: 1.5rem;
            text-align: center;
            padding: 20px;
        }

        /* Footer */
        footer {
            padding: 5% 5%;
            text-align: center;
            background-color: var(--deep-black);
            color: var(--pure-white);
        }

        footer h2 {
            font-size: 4rem;
            color: var(--neon-yellow);
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <header class="hero">
        <h1>UNBLOCK MULUND.</h1>
        <p class="sub-header">Amcha Mulund, Amcha Hakk. We are transitioning T-Ward from a contractor-led money pit to a citizen-led neighborhood.</p>
        <div class="hero-actions">
            <a href="#manifesto" class="btn">Read The Plan</a>
            <a href="#" class="btn btn-secondary">Join The Movement</a>
        </div>
    </header>

    <section id="manifesto" class="manifesto">
        <div style="text-align: center; margin-bottom: 40px;">
            <h2 style="font-size: 4rem; color: var(--electric-purple);">The T-Ward Action Plan</h2>
            <p style="font-weight: bold; font-size: 1.2rem;">2026 BMC ELECTION DRAFT</p>
        </div>

        <div class="policy-grid">
            
            <div class="policy-card">
                <h2>🚧 Infrastructure First</h2>
                <p>Development is necessary, but the foundation must come first. We are stopping the concrete squeeze.</p>
                <ul>
                    <li>The Mega-Tower Freeze until utility pipelines are upgraded.</li>
                    <li>Unblocking Veena Nagar and LBS Marg arteries immediately.</li>
                    <li>Escrow-backed 5-Year Pothole Guarantees from all contractors.</li>
                </ul>
            </div>

            <div class="policy-card">
                <h2>🚶‍♂️ The Right to Walk</h2>
                <p>Walking to the station shouldn't be an extreme sport. Dignity for pedestrians and vendors.</p>
                <ul>
                    <li>100% cleared primary footpaths on Gokhale & RRT Road.</li>
                    <li>Micro-zoned, regulated hawking areas on secondary streets.</li>
                    <li>Reclaiming dead under-flyover spaces for free public sports turfs.</li>
                </ul>
            </div>

            <div class="policy-card">
                <h2>⚖️ Equitable Planning</h2>
                <p>Mulund is a community, not a dumping ground for the BMC’s poor planning.</p>
                <ul>
                    <li>Fierce legislative opposition to centralized PAP dumping in Mulund East.</li>
                    <li>Mandating upfront capital funding for MT Agarwal Hospital before relocations.</li>
                </ul>
            </div>

            <div class="policy-card">
                <h2>📂 Radical Transparency</h2>
                <p>No more closed doors. We are bringing the Right to Information directly to the streets.</p>
                <ul>
                    <li>Real-time public dashboard for all T-Ward civic contracts and budgets.</li>
                    <li>Legal sign-offs required by local ALMs before contractors are paid.</li>
                    <li>Mandatory monthly open-air town halls in local public parks.</li>
                </ul>
            </div>

        </div>
    </section>

    <section id="documentary" class="media-section">
        <h3>🎥 The Reality of T-Ward</h3>
        <p>Look past the BMC press releases. Watch our on-the-ground documentary breakdowns.</p>
        
        <div class="video-grid">
            <div class="video-placeholder">[ Documenting the Veena Nagar Gridlock ]</div>
            <div class="video-placeholder">[ Where Does Your Tax Money Go? ]</div>
            <div class="video-placeholder">[ The Fight for Footpaths ]</div>
        </div>
    </section>

    <footer>
        <h2>DON'T JUST SCROLL. STROLL TO THE POLLS.</h2>
        <a href="#" class="btn" style="margin-top: 20px;">Volunteer Today</a>
        <p style="margin-top: 50px; color: #666;">Paid for by the Citizens of T-Ward • 2026 BMC Elections</p>
    </footer>

</body>
</html>
