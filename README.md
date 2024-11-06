<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Historical Places in India</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f3f4f6;
            color: #333;
        }

        /* Header */
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
        }

        header h1 {
            font-size: 1.8rem;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
        }

        /* Main Content */
        .main-content {
            padding-top: 80px;
            padding-bottom: 60px;
            text-align: center;
        }

        .intro {
            padding: 2rem;
            background-color: #ffe0b2;
            color: #333;
        }

        .intro h2 {
            font-size: 2rem;
            margin-bottom: 0.5rem;
        }

        /* Historical Places Section */
        .places {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
            padding: 2rem;
        }

        .place-card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            width: 300px;
            text-align: left;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .place-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .place-card-content {
            padding: 1rem;
        }

        .place-card h3 {
            font-size: 1.5rem;
            margin: 0.5rem 0;
        }

        .place-card p {
            font-size: 1rem;
            color: #666;
        }

        /* Hover Effects */
        .place-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .place-card:hover img {
            transform: scale(1.05);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .places {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Historical Places in India</h1>
    </header>

    <!-- Main Content -->
    <div class="main-content">

        <!-- Introduction Section -->
        <section class="intro">
            <h2>Explore the Rich History of India</h2>
            <p>Discover some of the most iconic historical places in India that represent the country's rich cultural heritage.</p>
        </section>

        <!-- Historical Places Section -->
        <section class="places">
            <!-- Place 1 -->
            <div class="place-card">
                <img src="tajmahal.jpeg" alt="Taj Mahal">
                <div class="place-card-content">
                    <h3>Taj Mahal</h3>
                    <p>A symbol of love, the Taj Mahal is a UNESCO World Heritage Site located in Agra, Uttar Pradesh.</p>
                </div>
            </div>

            <!-- Place 2 -->
            <div class="place-card">
                <img src="qutubminar.jpg" alt="Qutub Minar">
                <div class="place-card-content">
                    <h3>Qutub Minar</h3>
                    <p>The tallest brick minaret in the world, located in Delhi, showcasing Indo-Islamic architecture.</p>
                </div>
            </div>

            <!-- Place 3 -->
            <div class="place-card">
                <img src="hawamahal.jpg" alt="Hawa Mahal">
                <div class="place-card-content">
                    <h3>Hawa Mahal</h3>
                    <p>A stunning palace in Jaipur, Rajasthan, known for its unique architecture with 953 small windows.</p>
                </div>
            </div>

            <!-- Place 4 -->
            <div class="place-card">
                <img src="red fort.jpg" alt="Red Fort">
                <div class="place-card-content">
                    <h3>Red Fort</h3>
                    <p>A symbol of India's independence, located in Delhi, and a UNESCO World Heritage Site.</p>
                </div>
            </div>

            <!-- Place 5 -->
            <div class="place-card">
                <img src="amber.jpg" alt="Amber Fort">
                <div class="place-card-content">
                    <h3>Amber Fort</h3>
                    <p>An impressive fort located in Jaipur, known for its artistic Hindu elements and scenic views.</p>
                </div>
            </div>

            <!-- Place 6 -->
            <div class="place-card">
                <img src="mysore.jpg" alt="Mysore Palace">
                <div class="place-card-content">
                    <h3>Mysore Palace</h3>
                    <p>A grand palace in Karnataka, known for its stunning architecture and vibrant Dussehra celebrations.</p>
                </div>
            </div>

            <!-- Place 7 -->
            <div class="place-card">
                <img src="gateway.jpg" alt="Gateway of India">
                <div class="place-card-content">
                    <h3>Gateway of India</h3>
                    <p>An iconic monument in Mumbai, Maharashtra, built during the British colonial period.</p>
                </div>
            </div>

            <!-- Place 8 -->
            <div class="place-card">
                <img src="charminar.jpg" alt="Charminar">
                <div class="place-card-content">
                    <h3>Charminar</h3>
                    <p>A famous landmark in Hyderabad, Telangana, known for its stunning arches and bustling markets.</p>
                </div>
            </div>

            <!-- Place 9 -->
            <div class="place-card">
                <img src="sanchi.jpg" alt="Sanchi Stupa">
                <div class="place-card-content">
                    <h3>Sanchi Stupa</h3>
                    <p>An ancient Buddhist complex in Madhya Pradesh, and a UNESCO World Heritage Site.</p>
                </div>
            </div>

            <!-- Place 10 -->
            <div class="place-card">
                <img src="meenakshi.jpg" alt="Meenakshi Temple">
                <div class="place-card-content">
                    <h3>Meenakshi Temple</h3>
                    <p>A historic Hindu temple in Madurai, Tamil Nadu, known for its vibrant sculptures and architecture.</p>
                </div>
            </div>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>Designed and Developed by Irfan Ansari</p>
    </footer>

</body>
</html>
