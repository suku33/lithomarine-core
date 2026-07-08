<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Maritime Commodities Exchange</title>
    <style>
        /* 1. Global Setup & Premium Dark Slate Theme Variables */
        :root {
            --bg-slate: #1A1F2C;         /* Premium Deep Slate Grey */
            --bg-sidebar: #11141D;       /* Darker Institutional Panel Grey */
            --accent-emerald: #00C853;   /* Non-Neon Pure Emerald Green */
            --text-white: #F8F9FA;       /* Clean Off-White Text */
            --text-gray: #A0AEC0;        /* Subtle Secondary Text */
            --border-panel: #2D3748;     /* Sleek Terminal Borders */
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body, html {
            width: 100%;
            height: 100%;
            background-color: var(--bg-slate);
            color: var(--text-white);
            font-family: 'Segoe UI', system-ui, sans-serif;
            overflow: hidden; /* Locks screen like a professional desktop application */
        }

        /* 2. Top Header Terminal Bar */
        header {
            width: 100%;
            height: 60px;
            background-color: var(--bg-sidebar);
            border-bottom: 1px solid var(--border-panel);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 30px;
            z-index: 10;
        }

        .logo {
            font-size: 20px;
            font-weight: 700;
            color: var(--accent-emerald);
            letter-spacing: 1.5px;
        }

        .terminal-status {
            font-size: 12px;
            color: var(--accent-emerald);
            background: rgba(0, 200, 83, 0.1);
            padding: 4px 10px;
            border: 1px solid var(--accent-emerald);
            border-radius: 4px;
            font-family: monospace;
        }

        /* 3. Main Interface Layout Wrapper */
        .wrapper {
            display: flex;
            width: 100%;
            height: calc(100% - 60px); /* Fills screen minus header */
        }

        /* 4. Left Institutional Data Sidebar */
        .sidebar {
            width: 320px;
            height: 100%;
            background-color: var(--bg-sidebar);
            border-right: 1px solid var(--border-panel);
            padding: 25px;
            display: flex;
            flex-direction: flex-start;
            flex-direction: column;
            gap: 20px;
            z-index: 5;
        }

        .sidebar h2 {
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--text-gray);
            border-bottom: 1px solid var(--border-panel);
            padding-bottom: 10px;
        }

        .metric-card {
            background: rgba(26, 31, 44, 0.5);
            border: 1px solid var(--border-panel);
            padding: 15px;
            border-radius: 6px;
        }

        .metric-label {
            font-size: 11px;
            text-transform: uppercase;
            color: var(--text-gray);
            margin-bottom: 5px;
        }

        .metric-value {
            font-size: 24px;
            font-weight: 700;
            color: var(--text-white);
        }

        .metric-value.emerald {
            color: var(--accent-emerald);
        }

        /* 5. Center Stage Interactive Map Canvas */
        .map-canvas {
            flex: 1;
            height: 100%;
            position: relative;
            background-color: #151924;
            /* Creates a clean grid mesh pattern over the canvas background */
            background-image: linear-gradient(rgba(45, 55, 72, 0.1) 1px, transparent 1px),
                              linear-gradient(90deg, rgba(45, 55, 72, 0.1) 1px, transparent 1px);
            background-size: 30px 30px;
        }

        /* Glowing Coordinates and Asset Pins */
        .coordinate-grid {
            position: absolute;
            font-family: monospace;
            font-size: 10px;
            color: rgba(0, 200, 83, 0.4);
            padding: 10px;
        }

        .pin {
            position: absolute;
            width: 12px;
            height: 12px;
            background-color: var(--accent-emerald);
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 0 15px var(--accent-emerald);
            transition: transform 0.2s;
        }

        .pin:hover {
            transform: scale(1.4);
        }

        /* Absolute coordinates placement for flagship assets on map */
        #pin-stellar { top: 60%; left: 40%; }
        #pin-deepwater { top: 35%; left: 25%; }
        #pin-britannic { top: 42%; left: 55%; }

        /* Floating Technical Instructions Box */
        .map-overlay-info {
            position: absolute;
            bottom: 25px;
            right: 25px;
            background: rgba(17, 20, 29, 0.85);
            border: 1px solid var(--border-panel);
            backdrop-filter: blur(10px);
            padding: 15px;
            border-radius: 6px;
            max-width: 300px;
            font-size: 12px;
            color: var(--text-gray);
        }

        .map-overlay-info strong {
            color: var(--text-white);
        }
    </style>
</head>
<body>

    <!-- Header Terminal -->
    <header>
        <div class="logo">LITHOMARINE CORE</div>
        <div class="terminal-status">GLOBAL HARDWARE SYNCED // SECURE</div>
    </header>

    <!-- Main Application Split Layout -->
    <div class="wrapper">
        
        <!-- Left Data Sidebar Panel -->
        <div class="sidebar">
            <h2>Asset Matrix Metrics</h2>
            
            <div class="metric-card">
                <div class="metric-label">Registered Material Mass</div>
                <div class="metric-value">264,392 <span style="font-size: 14px; color: var(--text-gray);">TONS</span></div>
            </div>

            <div class="metric-card">
                <div class="metric-label">Estimated Carbon Offset Value</div>
                <div class="metric-value emerald">$11.2M <span style="font-size: 14px; color: var(--accent-emerald);">USD</span></div>
            </div>

            <div class="metric-card">
                <div class="metric-label">Active Regional Ledgers</div>
                <div class="metric-value" style="font-size: 18px; font-family: monospace;">08 OCEANIC BLOCKS</div>
            </div>
        </div>

        <!-- Center Bathymetric Map Window -->
        <div class="map-canvas">
            <!-- Simulated coordinates markers on interface -->
            <div class="coordinate-grid" style="top: 0; left: 0;">LAT: 00.0000° // LONG: 00.0000°</div>
            <div class="coordinate-grid" style="bottom: 0; right: 0; text-align: right;">SYS.REF // GRID-DELTA-BETA</div>

            <!-- Interative Glow Pins mapping the ships directly to visual coordinates -->
            <div class="pin" id="pin-stellar" onclick="alert('Asset: MV Stellar Banner \nMass: 45,000T Structural Steel \nStatus: Verified Reserve')"></div>
            <div class="pin" id="pin-deepwater" onclick="alert('Asset: Deepwater Horizon \nMass: 32,000T High-Grade Steel \nStatus: Deep Extraction Wave')"></div>
            <div class="pin" id="pin-britannic" onclick="alert('Asset: HMHS Britannic \nMass: 48,000T Antique Steel \nStatus: Accessible Sector')"></div>

            <!-- Interactive Information Legend overlay Box -->
            <div class="map-overlay-info">
                <strong>Global Bathymetric Viewport Active</strong><br><br>
                Hover and click on the emerald tracking coordinates pins to select deep-sea material reserves and display cross-border transactional ledger certificates.
            </div>
        </div>

    </div>

</body>
</html>
# lithomarine-core
