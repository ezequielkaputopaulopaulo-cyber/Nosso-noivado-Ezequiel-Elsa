# Gerar o arquivo index.html completo do convite para download
html_content = """<!DOCTYPE html>
<html lang="pt-AO">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noivado de Ezequiel & Elsa | Alambamento</title>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700;900&family=Montserrat:wght@300;400;600;700&family=Pinyon+Script&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --dark-earth: #24140b;
            --medium-brown: #3d2314;
            --burgundy: #611823;
            --soft-gold: #dcc2a3;
            --off-white: #faf7f2;
            --accent-gold: #c5a059;
            --shadow-dark: rgba(0, 0, 0, 0.4);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--off-white);
            color: var(--dark-earth);
            font-family: 'Montserrat', sans-serif;
            overflow-x: hidden;
            background-image: radial-gradient(var(--soft-gold) 0.75px, transparent 0.75px);
            background-size: 24px 24px;
        }

        h1, h2, h3, .font-cinzel {
            font-family: 'Cinzel', serif;
        }

        .font-script {
            font-family: 'Pinyon Script', cursive;
        }

        /* --- TELA DE ENTRADA / ENVELOPE --- */
        #envelope-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background-color: var(--dark-earth);
            z-index: 9999;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            transition: opacity 1s ease-in-out, visibility 1s;
        }

        #envelope-screen.hidden {
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
        }

        .envelope-wrapper {
            position: relative;
            width: 320px;
            height: 220px;
            background-color: var(--medium-brown);
            border-radius: 8px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.6);
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            perspective: 1000px;
            border: 2px solid var(--soft-gold);
        }

        .envelope-flap {
            position: absolute;
            top: 0;
            left: 0;
            width: 0;
            height: 0;
            border-left: 160px solid transparent;
            border-right: 160px solid transparent;
            border-top: 120px solid #2f1b0f;
            transform-origin: top;
            transition: transform 0.8s ease;
            z-index: 3;
        }

        .envelope-wrapper.open .envelope-flap {
            transform: rotateX(180deg);
        }

        .wax-seal {
            position: absolute;
            width: 75px;
            height: 75px;
            background: radial-gradient(circle, #801f2e 0%, var(--burgundy) 70%, #3b0e15 100%);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: var(--soft-gold);
            font-family: 'Cinzel', serif;
            font-weight: bold;
            font-size: 1.3rem;
            box-shadow: 0 4px 10px rgba(0,0,0,0.5), inset 0 0 8px rgba(0,0,0,0.4);
            border: 2px dashed rgba(220, 194, 163, 0.4);
            z-index: 4;
            transition: transform 0.3s ease;
        }

        .envelope-wrapper:hover .wax-seal {
            transform: scale(1.08);
        }

        .envelope-hint {
            margin-top: 35px;
            color: var(--soft-gold);
            font-size: 0.9rem;
            letter-spacing: 2px;
            text-transform: uppercase;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 0.5; }
            50% { opacity: 1; }
        }

        /* --- MODAIS (RSVP & RESTRITO) --- */
        .modal-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: rgba(15, 8, 4, 0.85);
            backdrop-filter: blur(5px);
            z-index: 10000;
            display: flex;
            justify-content: center;
            align-items: center;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.4s ease, visibility 0.4s;
            padding: 20px;
        }

        .modal-overlay.active {
            opacity: 1;
            visibility: visible;
        }

        .modal-card {
            background-color: var(--off-white);
            border: 2px solid var(--soft-gold);
            padding: 35px 25px;
            border-radius: 12px;
            width: 100%;
            max-width: 450px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            text-align: center;
            position: relative;
        }

        .modal-card h3 {
            color: var(--burgundy);
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .modal-card p {
            font-size: 0.9rem;
            color: var(--medium-brown);
            margin-bottom: 20px;
        }

        .form-group {
            margin-bottom: 18px;
            text-align: left;
        }

        .form-group label {
            display: block;
            font-size: 0.8rem;
            font-weight: 600;
            color: var(--dark-earth);
            margin-bottom: 5px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid var(--soft-gold);
            border-radius: 6px;
            background-color: #fff;
            font-family: 'Montserrat', sans-serif;
            font-size: 0.95rem;
            outline: none;
            transition: border-color 0.3s;
        }

        .form-control:focus {
            border-color: var(--burgundy);
        }

        .btn-submit {
            width: 100%;
            padding: 14px;
            background-color: var(--burgundy);
            color: var(--off-white);
            border: none;
            border-radius: 6px;
            font-family: 'Cinzel', serif;
            font-weight: 700;
            letter-spacing: 1px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .btn-submit:hover {
            background-color: var(--medium-brown);
        }

        /* --- CONTEÚDO PRINCIPAL DO CONVITE --- */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 40px 20px 20px;
            position: relative;
        }

        .restricted-link {
            position: absolute;
            top: 15px;
            right: 15px;
            font-size: 0.75rem;
            color: var(--medium-brown);
            text-decoration: none;
            opacity: 0.4;
            transition: opacity 0.3s;
            cursor: pointer;
        }

        .restricted-link:hover {
            opacity: 0.9;
        }

        .subtitle-header {
            font-size: 0.85rem;
            letter-spacing: 4px;
            text-transform: uppercase;
            color: var(--burgundy);
            font-weight: 700;
            margin-bottom: 10px;
        }

        .couple-names {
            font-size: 3rem;
            color: var(--dark-earth);
            line-height: 1.2;
            margin: 15px 0;
        }

        .bible-verse {
            font-style: italic;
            font-size: 0.95rem;
            color: var(--medium-brown);
            max-width: 600px;
            margin: 20px auto;
            line-height: 1.6;
            padding: 0 15px;
            border-left: 2px solid var(--soft-gold);
            border-right: 2px solid var(--soft-gold);
        }

        .event-date-badge {
            display: inline-block;
            background-color: var(--dark-earth);
            color: var(--soft-gold);
            padding: 8px 25px;
            border-radius: 20px;
            font-family: 'Cinzel', serif;
            font-size: 0.9rem;
            letter-spacing: 1px;
            margin-top: 15px;
        }

        /* --- SEÇÕES & CARDS --- */
        section {
            background-color: #ffffff;
            border: 1px solid var(--soft-gold);
            border-radius: 12px;
            padding: 30px 20px;
            margin: 30px 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.03);
            position: relative;
        }

        .section-title {
            text-align: center;
            color: var(--burgundy);
            font-size: 1.4rem;
            margin-bottom: 25px;
            position: relative;
            padding-bottom: 10px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 50px;
            height: 2px;
            background-color: var(--soft-gold);
        }

        /* Contagem Regressiva */
        .countdown-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            text-align: center;
        }

        .countdown-box {
            background-color: var(--off-white);
            border: 1px solid var(--soft-gold);
            border-radius: 8px;
            padding: 12px;
            min-width: 70px;
        }

        .countdown-value {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--dark-earth);
            font-family: 'Cinzel', serif;
        }

        .countdown-label {
            font-size: 0.65rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--medium-brown);
            margin-top: 4px;
        }

        /* Local */
        .location-card {
            text-align: center;
        }

        .location-title {
            font-size: 1.2rem;
            font-weight: 700;
            margin-bottom: 5px;
        }

        .location-sub {
            color: #666;
            font-size: 0.9rem;
            margin-bottom: 20px;
        }

        .map-buttons {
            display: flex;
            justify-content: center;
            gap: 12px;
            flex-wrap: wrap;
        }

        .btn-map {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 10px 18px;
            border-radius: 20px;
            text-decoration: none;
            font-size: 0.85rem;
            font-weight: 600;
            transition: transform 0.2s, opacity 0.2s;
        }

        .btn-map:hover {
            transform: translateY(-2px);
            opacity: 0.9;
        }

        .btn-gmaps {
            background-color: #4285F4;
            color: #fff;
        }

        .btn-waze {
            background-color: #33CCFF;
            color: #333;
        }

        /* Manual dos Convidados */
        .rules-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 15px;
        }

        .rule-card {
            background-color: var(--off-white);
            padding: 15px;
            border-radius: 8px;
            border-left: 3px solid var(--burgundy);
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .rule-number {
            font-family: 'Cinzel', serif;
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--burgundy);
        }

        .rule-text {
            font-size: 0.85rem;
            color: var(--dark-earth);
            font-weight: 500;
        }

        /* Cronograma (Timeline) */
        .timeline {
            position: relative;
            max-width: 500px;
            margin: 0 auto;
        }

        .timeline::before {
            content: '';
            position: absolute;
            top: 0;
            bottom: 0;
            left: 80px;
            width: 2px;
            background-color: var(--soft-gold);
        }

        .timeline-item {
            display: flex;
            margin-bottom: 25px;
            position: relative;
        }

        .timeline-time {
            width: 70px;
            font-weight: 700;
            font-size: 0.85rem;
            color: var(--burgundy);
            text-align: right;
            padding-right: 15px;
            padding-top: 2px;
        }

        .timeline-dot {
            position: absolute;
            left: 76px;
            top: 5px;
            width: 10px;
            height: 10px;
            background-color: var(--burgundy);
            border-radius: 50%;
            border: 2px solid var(--off-white);
        }

        .timeline-content {
            padding-left: 25px;
            flex: 1;
        }

        .timeline-title {
            font-weight: 700;
            font-size: 0.95rem;
            color: var(--dark-earth);
        }

        .timeline-desc {
            font-size: 0.8rem;
            color: #666;
            margin-top: 3px;
        }

        /* Mural de Recados */
        .message-form {
            margin-bottom: 25px;
        }

        .message-list {
            display: flex;
            flex-direction: column;
            gap: 12px;
            max-height: 300px;
            overflow-y: auto;
            padding-right: 5px;
        }

        .message-card {
            background-color: var(--off-white);
            border: 1px solid #eee;
            padding: 12px 15px;
            border-radius: 8px;
        }

        .message-author {
            font-weight: 700;
            font-size: 0.85rem;
            color: var(--burgundy);
            margin-bottom: 4px;
        }

        .message-text {
            font-size: 0.85rem;
            color: #444;
            line-height: 1.4;
        }

        .message-date {
            font-size: 0.65rem;
            color: #999;
            text-align: right;
            margin-top: 5px;
        }

        /* Player Flutuante */
        .audio-player-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: var(--burgundy);
            color: var(--soft-gold);
            border: 2px solid var(--soft-gold);
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            z-index: 9000;
            transition: transform 0.3s;
        }

        .audio-player-btn:hover {
            transform: scale(1.1);
        }

        .audio-player-btn.playing i {
            animation: spin 3s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Tabela Área dos Noivos */
        .table-responsive {
            overflow-x: auto;
            margin-top: 15px;
        }

        .guests-table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.85rem;
            text-align: left;
        }

        .guests-table th, .guests-table td {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }

        .guests-table th {
            background-color: var(--medium-brown);
            color: var(--soft-gold);
            font-family: 'Cinzel', serif;
        }

        footer {
            text-align: center;
            padding: 30px 20px;
            font-size: 0.8rem;
            color: var(--medium-brown);
            opacity: 0.8;
        }

        @media (max-width: 600px) {
            .couple-names { font-size: 2.2rem; }
            .countdown-value { font-size: 1.4rem; }
            .countdown-box { min-width: 55px; padding: 8px; }
            .timeline::before { left: 60px; }
            .timeline-time { width: 50px; font-size: 0.75rem; }
            .timeline-dot { left: 56px; }
        }
    </style>
</head>
<body>

    <!-- 1. TELA DE ENTRADA (ENVELOPE INTERATIVO) -->
    <div id="envelope-screen">
        <div class="envelope-wrapper" id="envelope" onclick="openEnvelope()">
            <div class="envelope-flap"></div>
            <div class="wax-seal">E&E</div>
        </div>
        <div class="envelope-hint">Toque no lacre para abrir</div>
    </div>

    <!-- MODAL RSVP INICIAL (PORTÃO DE ENTRADA) -->
    <div class="modal-overlay" id="rsvp-modal">
        <div class="modal-card">
            <h3>Confirmação de Presença</h3>
            <p>Seja bem-vindo ao nosso convite digital! Por favor, informe seus dados para ter acesso completo.</p>
            <form id="rsvp-form" onsubmit="saveRSVP(event)">
                <div class="form-group">
                    <label for="guest-name">Seu Nome Completo *</label>
                    <input type="text" id="guest-name" class="form-control" placeholder="Ex: Maria Silva" required>
                </div>
                <div class="form-group">
                    <label for="partner-name">Nome do Acompanhante / Par</label>
                    <input type="text" id="partner-name" class="form-control" placeholder="Ex: João Silva (Opcional)">
                </div>
                <button type="submit" class="btn-submit">Acessar Convite</button>
            </form>
        </div>
    </div>

    <!-- MODAL ÁREA RESTRITA DOS NOIVOS -->
    <div class="modal-overlay" id="bride-modal">
        <div class="modal-card" style="max-width: 600px;">
            <h3>Área dos Noivos</h3>
            <p>Lista de Convidados Confirmados (RSVP)</p>
            <div class="table-responsive">
                <table class="guests-table">
                    <thead>
                        <tr>
                            <th>#</th>
                            <th>Convidado</th>
                            <th>Acompanhante</th>
                            <th>Data</th>
                        </tr>
                    </thead>
                    <tbody id="guests-list-body">
                        <!-- Preenchido via JS -->
                    </tbody>
                </table>
            </div>
            <br>
            <button class="btn-submit" onclick="closeBrideModal()" style="background-color: var(--medium-brown);">Fechar</button>
        </div>
    </div>

    <!-- CONTEÚDO DO CONVITE -->
    <div class="container">
        
        <!-- CABEÇALHO -->
        <header>
            <span class="restricted-link" onclick="openBrideArea()">Área dos Noivos</span>
            <div class="subtitle-header">Convite de Noivado / Alambamento</div>
            <h1 class="couple-names font-script">Ezequiel Paulo<br>& Elsa Nené</h1>
            
            <div class="bible-verse">
                "Para que todos vejam, e saibam, e considerem, e juntamente entendam que a mão do Senhor fez isto, e o Santo de Israel o criou."
                <br><strong>— Isaías 41:20</strong>
            </div>

            <div class="event-date-badge">28 de Novembro de 2026 • 18h30</div>
        </header>

        <!-- CONTAGEM REGRESSIVA -->
        <section>
            <h2 class="section-title">Contagem Regressiva</h2>
            <div class="countdown-container">
                <div class="countdown-box">
                    <div class="countdown-value" id="cd-days">00</div>
                    <div class="countdown-label">Dias</div>
                </div>
                <div class="countdown-box">
                    <div class="countdown-value" id="cd-hours">00</div>
                    <div class="countdown-label">Horas</div>
                </div>
                <div class="countdown-box">
                    <div class="countdown-value" id="cd-minutes">00</div>
                    <div class="countdown-label">Min</div>
                </div>
                <div class="countdown-box">
                    <div class="countdown-value" id="cd-seconds">00</div>
                    <div class="countdown-label">Seg</div>
                </div>
            </div>
        </section>

        <!-- LOCAL -->
        <section>
            <h2 class="section-title">Local do Evento</h2>
            <div class="location-card">
                <div class="location-title">Resort Chile no Sequele</div>
                <div class="location-sub">Sequele, Luanda - Angola</div>
                <div class="map-buttons">
                    <a href="https://maps.google.com/?q=Resort+Chile+Sequele+Luanda" target="_blank" class="btn-map btn-gmaps">
                        <i class="fa-solid fa-location-dot"></i> Google Maps
                    </a>
                    <a href="https://waze.com/ul?q=Resort+Chile+Sequele" target="_blank" class="btn-map btn-waze">
                        <i class="fa-solid fa-car"></i> Waze
                    </a>
                </div>
            </div>
        </section>

        <!-- MANUAL DOS CONVIDADOS -->
        <section>
            <h2 class="section-title">Manual dos Convidados</h2>
            <div class="rules-grid">
                <div class="rule-card">
                    <span class="rule-number">01</span>
                    <span class="rule-text">Convidado não convida.</span>
                </div>
                <div class="rule-card">
                    <span class="rule-number">02</span>
                    <span class="rule-text">Preservar os utensílios encontrados.</span>
                </div>
                <div class="rule-card">
                    <span class="rule-number">03</span>
                    <span class="rule-text">Explore o africano que há em ti.</span>
                </div>
                <div class="rule-card">
                    <span class="rule-number">04</span>
                    <span class="rule-text">Seja pontual.</span>
                </div>
                <div class="rule-card">
                    <span class="rule-number">05</span>
                    <span class="rule-text">Tire muitas fotos.</span>
                </div>
                <div class="rule-card">
                    <span class="rule-number">06</span>
                    <span class="rule-text">Divirta-se bastante!</span>
                </div>
            </div>
        </section>

        <!-- CRONOGRAMA (TIMELINE) -->
        <section>
            <h2 class="section-title">Cronograma Oficial</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-time">15:00</div>
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-title">Recepção & Boas-Vindas</div>
                        <div class="timeline-desc">Acolhimento caloroso entre as famílias e convidados.</div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-time">16:00</div>
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-title">Momento Solene do Noivado</div>
                        <div class="timeline-desc">Cerimónia tradicional do Alambamento.</div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-time">18:00</div>
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-title">Banquete & Jantar de Celebração</div>
                        <div class="timeline-desc">Copo d'água e degustação da gastronomia especial.</div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-time">20:00</div>
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-title">Festa & Confraternização</div>
                        <div class="timeline-desc">Música, dança e muita comemoração.</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- MURAL DE RECADOS -->
        <section>
            <h2 class="section-title">Mural de Recados</h2>
            <form class="message-form" id="msg-form" onsubmit="saveMessage(event)">
                <div class="form-group">
                    <input type="text" id="msg-author" class="form-control" placeholder="Seu Nome" required>
                </div>
                <div class="form-group">
                    <textarea id="msg-text" class="form-control" rows="3" placeholder="Deixe uma mensagem carinhosa para os noivos..." required></textarea>
                </div>
                <button type="submit" class="btn-submit">Enviar Mensagem</button>
            </form>

            <div class="message-list" id="messages-container">
                <!-- Recados renderizados via JS -->
            </div>
        </section>

        <footer>
            Com carinho, Ezequiel Paulo & Elsa Nené • 2026
        </footer>
    </div>

    <!-- BOTÃO PLAYER FLUTUANTE DE ÁUDIO -->
    <button class="audio-player-btn" id="audio-btn" onclick="toggleAudio()" title="Tocar / Pausar Música">
        <i class="fa-solid fa-music"></i>
    </button>
    <audio id="bg-music" loop>
        <!-- Trilha de Fundo instrumental Sax/Jazz -->
        <source src="https://cdn.pixabay.com/download/audio/2022/05/27/audio_1808fbf07a.mp3" type="audio/mpeg">
    </audio>

    <!-- JAVASCRIPT INTEGRADO -->
    <script>
        // Data do evento: 28 de Novembro de 2026, 18:30
        const eventDate = new Date("November 28, 2026 18:30:00").getTime();

        // Inicialização
        document.addEventListener("DOMContentLoaded", () => {
            initCountdown();
            loadMessages();
            checkRSVPStatus();
        });

        // 1. Envelope & Modal RSVP
        function openEnvelope() {
            const envelope = document.getElementById("envelope");
            envelope.classList.add("open");
            
            setTimeout(() => {
                document.getElementById("rsvp-modal").classList.add("active");
            }, 800);
        }

        function checkRSVPStatus() {
            const confirmedGuest = localStorage.getItem("ee_rsvp_guest");
            if (confirmedGuest) {
                document.getElementById("envelope-screen").classList.add("hidden");
            }
        }

        function saveRSVP(e) {
            e.preventDefault();
            const guestName = document.getElementById("guest-name").value.trim();
            const partnerName = document.getElementById("partner-name").value.trim() || "Nenhum";

            if (!guestName) return;

            // Salva dados locais
            let rsvpList = JSON.parse(localStorage.getItem("ee_rsvp_list") || "[]");
            rsvpList.push({
                guest: guestName,
                partner: partnerName,
                date: new Date().toLocaleDateString('pt-AO') + ' ' + new Date().toLocaleTimeString('pt-AO', {hour: '2-digit', minute:'2-digit'})
            });

            localStorage.setItem("ee_rsvp_list", JSON.stringify(rsvpList));
            localStorage.setItem("ee_rsvp_guest", guestName);

            // Esconde modal e envelope
            document.getElementById("rsvp-modal").classList.remove("active");
            document.getElementById("envelope-screen").classList.add("hidden");

            // Tenta dar play no áudio
            playAudio();
        }

        // 2. Área Restrita dos Noivos
        function openBrideArea() {
            const password = prompt("Digite a senha de acesso à Área dos Noivos:");
            if (password === "1996-2002") {
                renderGuestsTable();
                document.getElementById("bride-modal").classList.add("active");
            } else if (password !== null) {
                alert("Senha incorreta!");
            }
        }

        function closeBrideModal() {
            document.getElementById("bride-modal").classList.remove("active");
        }

        function renderGuestsTable() {
            const tbody = document.getElementById("guests-list-body");
            const rsvpList = JSON.parse(localStorage.getItem("ee_rsvp_list") || "[]");

            if (rsvpList.length === 0) {
                tbody.innerHTML = `<tr><td colspan="4" style="text-align:center; color:#888;">Nenhum convidado confirmado ainda.</td></tr>`;
                return;
            }

            tbody.innerHTML = rsvpList.map((item, index) => `
                <tr>
                    <td>${index + 1}</td>
                    <td><strong>${escapeHtml(item.guest)}</strong></td>
                    <td>${escapeHtml(item.partner)}</td>
                    <td><small>${item.date}</small></td>
                </tr>
            `).join('');
        }

        // 3. Player Flutuante
        const audio = document.getElementById("bg-music");
        const audioBtn = document.getElementById("audio-btn");
        let isPlaying = false;

        function toggleAudio() {
            if (isPlaying) {
                audio.pause();
                audioBtn.classList.remove("playing");
                audioBtn.innerHTML = '<i class="fa-solid fa-music"></i>';
                isPlaying = false;
            } else {
                playAudio();
            }
        }

        function playAudio() {
            audio.play().then(() => {
                isPlaying = true;
                audioBtn.classList.add("playing");
                audioBtn.innerHTML = '<i class="fa-solid fa-compact-disc"></i>';
            }).catch(() => {
                isPlaying = false;
            });
        }

        // 4. Contagem Regressiva
        function initCountdown() {
            function update() {
                const now = new Date().getTime();
                const distance = eventDate - now;

                if (distance < 0) {
                    document.getElementById("cd-days").innerText = "00";
                    document.getElementById("cd-hours").innerText = "00";
                    document.getElementById("cd-minutes").innerText = "00";
                    document.getElementById("cd-seconds").innerText = "00";
                    return;
                }

                const days = Math.floor(distance / (1000 * 60 * 60 * 24));
                const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((distance % (1000 * 60)) / 1000);

                document.getElementById("cd-days").innerText = String(days).padStart(2, '0');
                document.getElementById("cd-hours").innerText = String(hours).padStart(2, '0');
                document.getElementById("cd-minutes").innerText = String(minutes).padStart(2, '0');
                document.getElementById("cd-seconds").innerText = String(seconds).padStart(2, '0');
            }

            update();
            setInterval(update, 1000);
        }

        // 5. Mural de Recados
        function saveMessage(e) {
            e.preventDefault();
            const author = document.getElementById("msg-author").value.trim();
            const text = document.getElementById("msg-text").value.trim();

            if (!author || !text) return;

            let messages = JSON.parse(localStorage.getItem("ee_messages") || "[]");
            messages.unshift({
                author: author,
                text: text,
                date: new Date().toLocaleDateString('pt-AO')
            });

            localStorage.setItem("ee_messages", JSON.stringify(messages));
            
            document.getElementById("msg-author").value = "";
            document.getElementById("msg-text").value = "";

            loadMessages();
        }

        function loadMessages() {
            const container = document.getElementById("messages-container");
            let messages = JSON.parse(localStorage.getItem("ee_messages") || "[]");

            if (messages.length === 0) {
                container.innerHTML = `<div style="text-align:center; color:#888; font-size:0.85rem; padding: 10px;">Seja o primeiro a deixar uma mensagem de felicitações!</div>`;
                return;
            }

            container.innerHTML = messages.map(msg => `
                <div class="message-card">
                    <div class="message-author">${escapeHtml(msg.author)}</div>
                    <div class="message-text">${escapeHtml(msg.text)}</div>
                    <div class="message-date">${msg.date}</div>
                </div>
            `).join('');
        }

        function escapeHtml(text) {
            return text
                .replace(/&/g, "&amp;")
                .replace(/</g, "&lt;")
                .replace(/>/g, "&gt;")
                .replace(/"/g, "&quot;")
                .replace(/'/g, "&#039;");
        }
    </script>
</body>
</html>
"""

with open("index.html", "w", encoding="utf-8") as f:
    f.write(html_content)

print("Arquivo index.html criado com sucesso.")