<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QUETRIX.pro - 2016 Revival</title>
    <style>
        :root {
            --bg-dark: #0b0914;
            --card-bg: #151124;
            --purple-primary: #7b2cbf;
            --purple-hover: #9d4edd;
            --silver-text: #c7c7c7;
            --silver-border: #3c3856;
            --white: #ffffff;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: var(--bg-dark); color: var(--silver-text); min-height: 100vh; display: flex; flex-direction: column; }

        header {
            background-color: var(--card-bg);
            border-bottom: 2px solid var(--purple-primary);
            display: flex; justify-content: space-between; align-items: center;
            padding: 15px 30px;
        }

        .logo-area { display: flex; align-items: center; gap: 12px; }
        .logo-box {
            width: 40px; height: 40px;
            background: linear-gradient(135deg, var(--purple-primary), #3c1361);
            border: 2px solid var(--silver-border); border-radius: 6px;
            display: flex; justify-content: center; align-items: center;
            font-size: 24px; font-weight: bold; color: var(--white);
            box-shadow: 0 0 10px rgba(123, 44, 191, 0.4);
        }
        .brand-name { font-size: 22px; font-weight: 800; color: var(--white); letter-spacing: 1px; }

        nav ul { list-style: none; display: flex; gap: 20px; }
        nav a {
            color: var(--silver-text); text-decoration: none; font-weight: 600; padding: 8px 12px;
            border-radius: 4px; transition: 0.2s; cursor: pointer;
        }
        nav a:hover, nav a.active { color: var(--white); background-color: var(--purple-primary); }

        .container { max-width: 1100px; margin: 25px auto; padding: 0 20px; flex: 1; width: 100%; }
        .tab-content { display: none; }
        .tab-content.active { display: block; }

        .hero {
            background: linear-gradient(135deg, #151124, #241b3e);
            border: 1px solid var(--silver-border); border-radius: 8px; padding: 30px;
            text-align: center; margin-bottom: 30px;
        }
        .hero h1 { color: var(--white); font-size: 32px; margin-bottom: 10px; }
        .btn {
            background-color: var(--purple-primary); color: var(--white); border: none;
            padding: 10px 20px; border-radius: 6px; font-weight: bold; cursor: pointer; transition: 0.2s;
        }
        .btn:hover { background-color: var(--purple-hover); }

        .game-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 20px; }
        .game-card {
            background: var(--card-bg); border: 1px solid var(--silver-border);
            border-radius: 6px; overflow: hidden; padding: 12px; cursor: pointer; transition: 0.2s;
        }
        .game-card:hover { border-color: var(--purple-primary); transform: translateY(-3px); }
        .game-thumb { height: 120px; background: #231c3a; border-radius: 4px; display: flex; align-items: center; justify-content: center; font-weight: bold; color: #5a5278; }

        /* In-website Community Chat */
        .chat-box {
            background: var(--card-bg); border: 1px solid var(--silver-border);
            border-radius: 8px; height: 350px; display: flex; flex-direction: column; overflow: hidden;
        }
        .chat-messages { flex: 1; padding: 15px; overflow-y: auto; display: flex; flex-direction: column; gap: 10px; }
        .chat-msg { background: #1e1833; padding: 8px 12px; border-radius: 6px; font-size: 14px; }
        .chat-msg strong { color: var(--purple-hover); }
        .chat-input-area { display: flex; border-top: 1px solid var(--silver-border); }
        .chat-input-area input {
            flex: 1; background: transparent; border: none; padding: 12px; color: var(--white); outline: none;
        }

        footer { text-align: center; padding: 20px; border-top: 1px solid var(--silver-border); margin-top: 40px; font-size: 13px; }
    </style>
</head>
<body>

    <header>
        <div class="logo-area">
            <div class="logo-box">Q</div>
            <div class="brand-name">QUETRIX.pro</div>
        </div>
        <nav>
            <ul>
                <li><a onclick="showTab('games')" class="active" id="nav-games">Games</a></li>
                <li><a onclick="showTab('chat')" id="nav-chat">Community Feed</a></li>
                <li><a onclick="showTab('studio')" id="nav-studio">Studio</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <!-- GAMES TAB -->
        <div id="games" class="tab-content active">
            <div class="hero">
                <h1>QUETRIX 2016 Revival</h1>
                <p>Classic blocky avatars, R6 & R15 support, and built-in community chat.</p><br>
                <button class="btn" onclick="alert('Launcher ready!')">📱 QUETRIX Client Active</button>
            </div>
            <h2>Featured Places</h2><br>
            <div class="game-grid">
                <div class="game-card">
                    <div class="game-thumb">Crossroads</div>
                    <h4 style="margin-top:10px; color:white;">Classic Crossroads</h4>
                    <p style="font-size:12px;">🟢 42 Playing</p>
                </div>
                <div class="game-card">
                    <div class="game-thumb">Heights IV</div>
                    <h4 style="margin-top:10px; color:white;">Sword Fight on Heights</h4>
                    <p style="font-size:12px;">🟢 28 Playing</p>
                </div>
            </div>
        </div>

        <!-- COMMUNITY CHAT TAB -->
        <div id="chat" class="tab-content">
            <h2>Community Feed (No Discord Required)</h2>
            <p style="margin-bottom:15px; font-size:14px;">Talk with other players right here on the website!</p>
            <div class="chat-box">
                <div class="chat-messages" id="chat-messages">
                    <div class="chat-msg"><strong>System:</strong> Welcome to QUETRIX.pro!</div>
                    <div class="chat-msg"><strong>Builder2016:</strong> Awesome revival site!</div>
                </div>
                <div class="chat-input-area">
                    <input type="text" id="chat-input" placeholder="Type a message...">
                    <button class="btn" onclick="sendMessage()">Send</button>
                </div>
            </div>
        </div>

        <!-- STUDIO TAB -->
        <div id="studio" class="tab-content">
            <h2>QUETRIX Studio</h2>
            <p>Publish your own blocky creations here for everyone to play.</p>
        </div>
    </div>

    <footer>&copy; 2026 QUETRIX.pro Revival Project</footer>

    <script>
        function showTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(t => t.classList.remove('active'));
            document.querySelectorAll('nav a').forEach(a => a.classList.remove('active'));
            document.getElementById(tabId).classList.add('active');
            document.getElementById('nav-' + tabId).classList.add('active');
        }

        function sendMessage() {
            const input = document.getElementById('chat-input');
            if(!input.value.trim()) return;
            const msgBox = document.getElementById('chat-messages');
            const msg = document.createElement('div');
            msg.className = 'chat-msg';
            msg.innerHTML = `<strong>You:</strong> ${input.value}`;
            msgBox.appendChild(msg);
            input.value = '';
            msgBox.scrollTop = msgBox.scrollHeight;
        }
    </script>
</body>
</html>
