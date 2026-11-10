# therealsabirs.github.io-engagement-invitation
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aarav & Priya - Engagement Invitation</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">
    <!-- Stylesheet -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Hero Section -->
    <header class="hero">
        <div class="overlay"></div>
        <div class="hero-content">
            <span class="subtitle">We're Getting Engaged!</span>
            <h1>Aarav & Priya</h1>
            <p class="date-badge">Saturday, December 12, 2026</p>
            <a href="#details" class="btn">Join Our Celebration</a>
        </div>
    </header>

    <!-- Invitation Message -->
    <section class="invitation-section" id="details">
        <div class="container">
            <h2>You're Invited</h2>
            <p class="invite-text">
                Together with our families, we joyfully invite you to celebrate the beginning of our forever. 
                Join us for our ring ceremony, dinner, and an evening of joy.
            </p>
            
            <div class="details-grid">
                <div class="card">
                    <h3>💍 Ring Ceremony</h3>
                    <p><strong>Date:</strong> December 12, 2026</p>
                    <p><strong>Time:</strong> 5:00 PM Onwards</p>
                    <p><strong>Venue:</strong> The Grand Ballroom, MG Road, City Center</p>
                </div>
                <div class="card">
                    <h3>✨ Dress Code</h3>
                    <p><strong>Evening Wear:</strong></p>
                    <p>Traditional / Indo-Western / Formal Attire</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Countdown Section -->
    <section class="countdown-section">
        <div class="container">
            <h2>Counting Down to Forever</h2>
            <div id="countdown" class="countdown-grid">
                <div class="time-box"><span id="days">00</span><p>Days</p></div>
                <div class="time-box"><span id="hours">00</span><p>Hours</p></div>
                <div class="time-box"><span id="minutes">00</span><p>Minutes</p></div>
                <div class="time-box"><span id="seconds">00</span><p>Seconds</p></div>
            </div>
        </div>
    </section>

    <!-- RSVP Section -->
    <section class="rsvp-section">
        <div class="container">
            <h2>Are You Attending?</h2>
            <p>Please let us know if you can make it by November 30, 2026.</p>
            <form id="rsvpForm" onsubmit="handleRSVP(event)">
                <input type="text" id="guestName" placeholder="Your Full Name" required>
                <select id="guestStatus" required>
                    <option value="">Will you attend?</option>
                    <option value="Joyfully Accepts">Joyfully Accepts</option>
                    <option value="Regretfully Declines">Regretfully Declines</option>
                </select>
                <button type="submit" class="btn">Send Response</button>
            </form>
            <p id="rsvpMessage" class="hidden">Thank you! Your response has been recorded.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Made with love for Aarav & Priya's Engagement</p>
    </footer>

    <!-- Script File -->
    <script src="script.js"></script>
</body>
</html>
