<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIAWEB.Net - Internet Rápida e Barata</title>
    <style>
        /* ESTILO GERAL */
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        /* HEADER COM NOVA LOGO */
        header {
            background: linear-gradient(135deg, #0066ff, #00ccff);
            color: white;
            text-align: center;
            padding: 30px 0;
        }
        
        .logo-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 8px;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            text-decoration: none;
        }
        
        .wifi-icon {
            width: 40px;
            height: 40px;
            fill: white;
            filter: drop-shadow(0 2px 4px rgba(0,0,0,0.2));
        }
        
        .logo-text {
            font-size: 2.5em;
            font-weight: bold;
            background: linear-gradient(90deg, #ffffff, #e0f7fa);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        
        .logo-tagline {
            font-size: 1.1em;
            opacity: 0.9;
            letter-spacing: 0.5px;
        }
        
        /* RESTANTE DO CSS (MANTIDO COM PEQUENOS AJUSTES) */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .planos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
            margin: 40px 0;
        }
        
        .plano {
            background: white;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            padding: 25px;
            width: 280px;
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .plano:hover {
            transform: translateY(-10px);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
        }
        
        .plano h3 {
            color: #0066ff;
            font-size: 1.8em;
            margin: 0 0 15px;
        }
        
        .plano .preco {
            font-size: 2.2em;
            font-weight: bold;
            color: #333;
            margin: 15px 0;
        }
        
        .btn-whatsapp {
            display: inline-block;
            background: #25D366;
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 6px;
            font-weight: bold;
            margin-top: 15px;
            transition: background 0.3s;
        }
        
        .btn-whatsapp:hover {
            background: #128C7E;
        }
        
        footer {
            text-align: center;
            padding: 25px;
            background: #222;
            color: white;
            margin-top: 40px;
        }
        
        @media (max-width: 768px) {
            .planos {
                flex-direction: column;
                align-items: center;
            }
            
            .logo-text {
                font-size: 2em;
            }
            
            .wifi-icon {
                width: 32px;
                height: 32px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo-container">
                <a href="/" class="logo">
                    <!-- Ícone Wi-Fi SVG -->
                    <svg class="wifi-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12 3C7.8 3 3.7 4.4.4 7c-.5.4-.6 1.1-.1 1.6.4.5 1.1.6 1.6.1 3-2.3 6.5-3.5 10.1-3.5 3.6 0 7.1 1.2 10.1 3.5.5.4 1.2.3 1.6-.1.4-.5.3-1.2-.1-1.6C20.3 4.4 16.2 3 12 3zm0 6c-3.3 0-6.4 1.3-8.7 3.5-.5.4-.5 1.1-.1 1.6.4.5 1.1.5 1.6.1C6 11.9 8.9 11 12 11s6 .9 8.2 2.2c.2.2.5.3.7.3.3 0 .6-.1.8-.4.4-.5.4-1.2-.1-1.6C18.4 10.3 15.3 9 12 9zm0 6c-1.7 0-3.3.6-4.5 1.7-.4.4-.5 1.1-.1 1.6.4.4 1.1.5 1.6.1 1-.9 2.3-1.4 3.6-1.4 1.3 0 2.6.5 3.6 1.4.2.2.5.3.8.3.3 0 .6-.1.8-.4.4-.5.3-1.2-.1-1.6-1.2-1.1-2.8-1.7-4.5-1.7zm2.8 4.8c-.6-.5-1.4-.8-2.2-.8-.8 0-1.6.3-2.2.8-.4.4-.5 1.1-.1 1.6.4.4 1.1.5 1.6.1.2-.2.5-.3.7-.3s.5.1.7.3c.2.2.5.3.8.3.3 0 .6-.1.8-.4.4-.5.3-1.2-.1-1.6z"/>
                    </svg>
                    <span class="logo-text">VIAWEB</span>
                </a>
                <p class="logo-tagline">Internet não te abandona</p>
            </div>
        </div>
    </header>
    
    <div class="container">
        <h2 style="text-align: center;">Nossos Planos de Internet</h2>
        
        <div class="planos">
            <!-- Plano 15 Mega -->
            <div class="plano">
                <h3>15 Mega</h3>
                <div class="preco">R$ 40,00/mês</div>
                <p>Ideal para WhatsApp e redes sociais</p>
                <a href="https://wa.me/5581997675649?text=Quero%20assinar%20o%20plano%20de%2015%20Mega" class="btn-whatsapp">Contratar via WhatsApp</a>
            </div>
            
            <!-- Plano 25 Mega -->
            <div class="plano">
                <h3>25 Mega</h3>
                <div class="preco">R$ 45,00/mês</div>
                <p>Perfeito para vídeos e estudos</p>
                <a href="https://wa.me/5581997675649?text=Quero%20assinar%20o%20plano%20de%2025%20Mega" class="btn-whatsapp">Contratar via WhatsApp</a>
            </div>
            
            <!-- Plano 40 Mega -->
            <div class="plano">
                <h3>40 Mega</h3>
                <div class="preco">R$ 55,00/mês</div>
                <p>Streaming em HD sem travamentos</p>
                <a href="https://wa.me/5581997675649?text=Quero%20assinar%20o%20plano%20de%2040%20Mega" class="btn-whatsapp">Contratar via WhatsApp</a>
            </div>
            
            <!-- Plano 60 Mega -->
            <div class="plano">
                <h3>60 Mega</h3>
                <div class="preco">R$ 65,00/mês</div>
                <p>Famílias pequenas e home office</p>
                <a href="https://wa.me/5581997675649?text=Quero%20assinar%20o%20plano%20de%2060%20Mega" class="btn-whatsapp">Contratar via WhatsApp</a>
            </div>
            
            <!-- Plano 100 Mega -->
            <div class="plano">
                <h3>100 Mega</h3>
                <div class="preco">R$ 80,00/mês</div>
                <p>Jogos online e downloads rápidos</p>
                <a href="https://wa.me/5581997675649?text=Quero%20assinar%20o%20plano%20de%20100%20Mega" class="btn-whatsapp">Contratar via WhatsApp</a>
            </div>
            
            <!-- Plano 200 Mega -->
            <div class="plano">
                <h3>200 Mega</h3>
                <div class="preco">R$ 95,00/mês</div>
                <p>Casa com vários dispositivos conectados</p>
                <a href="https://wa.me/5581997675649?text=Quero%20assinar%20o%20plano%20de%20200%20Mega" class="btn-whatsapp">Contratar via WhatsApp</a>
            </div>
        </div>
    </div>
    
    <footer>
        <div class="container">
            <p>© 2024 VIAWEB.Net - Todos os direitos reservados</p>
            <p>Contato: (81) 99767-5649</p>
        </div>
    </footer>
</body>
</html>
