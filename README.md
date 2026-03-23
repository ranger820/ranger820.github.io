# ranger820.github.io
    body {
        font-family: 'Arial', sans-serif;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        color: #333;
        min-height: 100vh;
    }

    nav {
        background: rgba(0, 0, 0, 0.3);
        padding: 20px 0;
        position: sticky;
        top: 0;
        z-index: 100;
    }

    nav .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    nav h1 {
        color: white;
        font-size: 1.8em;
    }

    nav a {
        color: white;
        text-decoration: none;
        margin-left: 30px;
        font-weight: bold;
        transition: color 0.3s;
    }

    nav a:hover {
        color: #FFD700;
    }

    .hero {
        max-width: 1200px;
        margin: 0 auto;
        padding: 60px 20px;
        text-align: center;
        color: white;
    }

    .hero h1 {
        font-size: 4em;
        margin-bottom: 20px;
        text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.4);
    }

    .hero p {
        font-size: 1.3em;
        margin-bottom: 10px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }

    .cta-button {
        display: inline-block;
        margin-top: 30px;
        padding: 20px 50px;
        background: #FF0000;
        color: white;
        text-decoration: none;
        font-size: 1.5em;
        font-weight: bold;
        border-radius: 15px;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        transition: all 0.3s;
        cursor: pointer;
        border: none;
    }

    .cta-button:hover {
        transform: scale(1.1);
        box-shadow: 0 15px 40px rgba(229, 57, 53, 0.5);
    }

    .cta-button:active {
        transform: scale(0.95);
    }

    .features {
        max-width: 1200px;
        margin: 60px auto;
        padding: 0 20px;
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 30px;
    }

    .feature-card {
        background: rgba(255, 255, 255, 0.95);
        padding: 30px;
        border-radius: 15px;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        text-align: center;
        animation: slide-up 0.6s ease-out;
    }

    .feature-card h3 {
        font-size: 1.5em;
        margin-bottom: 15px;
        color: #667eea;
    }

    .feature-card p {
        color: #666;
        line-height: 1.6;
    }

    @keyframes slide-up {
        from {
            opacity: 0;
            transform: translateY(30px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    .stats {
        max-width: 1200px;
        margin: 60px auto;
        padding: 0 20px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }

    .stat-item {
        background: rgba(255, 255, 255, 0.9);
        padding: 20px;
        border-radius: 10px;
        text-align: center;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    }

    .stat-item .number {
        font-size: 2.5em;
        font-weight: bold;
        color: #FF0000;
    }

    .stat-item .label {
        color: #666;
        margin-top: 10px;
    }

    footer {
        background: rgba(0, 0, 0, 0.3);
        color: white;
        text-align: center;
        padding: 30px 20px;
        margin-top: 60px;
    }

    footer a {
        color: #FFD700;
        text-decoration: none;
    }

    @media (max-width: 768px) {
        .hero h1 {
            font-size: 2.5em;
        }

        .stats {
            grid-template-columns: 1fr;
        }

        nav .container {
            flex-direction: column;
            gap: 15px;
        }

        nav a {
            margin-left: 0;
        }
    }
</style>
</style>
