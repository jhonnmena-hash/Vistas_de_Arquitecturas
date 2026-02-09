<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arquitectura General - Microservicios Cloud Híbrido |  Infraestructura</title>
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700;900&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #0a4d92;
            --primary-light: #1565c0;
            --secondary: #00695c;
            --accent: #ff6f00;
            --dark: #0d1b2a;
            --gray-900: #1b263b;
            --gray-800: #283747;
            --gray-700: #415a77;
            --gray-300: #e0e1dd;
            --gray-100: #f8f9fa;
            --success: #2e7d32;
            --warning: #f57c00;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'DM Sans', -apple-system, BlinkMacSystemFont, sans-serif;
            background: linear-gradient(135deg, #0d1b2a 0%, #1b263b 50%, #283747 100%);
            min-height: 100vh;
            padding: 40px 20px;
        }

        .document-wrapper {
            max-width: 1600px;
            margin: 0 auto;
            background: #ffffff;
            border-radius: 16px;
            overflow: hidden;
            box-shadow: 0 30px 90px rgba(0, 0, 0, 0.6);
        }

        /* Professional Header */
        .doc-header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            padding: 50px 60px;
            position: relative;
            overflow: hidden;
        }

        .doc-header::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -10%;
            width: 500px;
            height: 200%;
            background: linear-gradient(45deg, rgba(255,255,255,0.1) 0%, transparent 100%);
            transform: rotate(-15deg);
        }

        .doc-header::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: var(--accent);
        }

        .header-content {
            position: relative;
            z-index: 2;
        }

        .doc-type {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            padding: 8px 24px;
            border-radius: 6px;
            font-size: 12px;
            font-weight: 700;
            color: white;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            margin-bottom: 20px;
            border: 1px solid rgba(255, 255, 255, 0.3);
        }

        .doc-header h1 {
            font-size: 44px;
            font-weight: 900;
            color: white;
            margin-bottom: 12px;
            line-height: 1.2;
            letter-spacing: -0.5px;
        }

        .doc-header h2 {
            font-size: 22px;
            font-weight: 500;
            color: rgba(255, 255, 255, 0.95);
            margin-bottom: 30px;
        }

        .header-meta {
            display: flex;
            gap: 35px;
            flex-wrap: wrap;
            margin-top: 25px;
        }

        .meta-item {
            display: flex;
            align-items: center;
            gap: 10px;
            color: rgba(255, 255, 255, 0.9);
            font-size: 14px;
            font-weight: 500;
        }

        .meta-icon {
            width: 36px;
            height: 36px;
            background: rgba(255, 255, 255, 0.15);
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
        }

        /* Content Area */
        .doc-content {
            padding: 60px;
        }

        /* Executive Summary Banner */
        .exec-summary {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-left: 6px solid var(--primary);
            padding: 35px 40px;
            border-radius: 8px;
            margin-bottom: 60px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
        }

        .exec-summary h3 {
            font-size: 16px;
            font-weight: 900;
            color: var(--primary);
            text-transform: uppercase;
            letter-spacing: 1.2px;
            margin-bottom: 16px;
        }

        .exec-summary p {
            font-size: 15px;
            line-height: 1.8;
            color: var(--gray-800);
        }

        /* Architecture Title */
        .arch-title {
            text-align: center;
            margin-bottom: 50px;
        }

        .arch-title h2 {
            font-size: 36px;
            font-weight: 900;
            color: var(--dark);
            margin-bottom: 12px;
            letter-spacing: -0.5px;
        }

        .arch-title p {
            font-size: 16px;
            color: var(--gray-700);
            font-weight: 500;
        }

        /* Architecture Layers Container */
        .arch-layers {
            max-width: 1400px;
            margin: 0 auto;
            position: relative;
        }

        /* Connector Lines */
        .arch-layers::before {
            content: '';
            position: absolute;
            left: 40px;
            top: 70px;
            bottom: 100px;
            width: 3px;
            background: linear-gradient(180deg, var(--primary) 0%, var(--accent) 100%);
            border-radius: 10px;
        }

        /* Layer Card */
        .layer {
            display: flex;
            gap: 25px;
            margin-bottom: 35px;
            position: relative;
            animation: fadeInUp 0.7s ease-out backwards;
        }

        .layer:nth-child(1) { animation-delay: 0.1s; }
        .layer:nth-child(2) { animation-delay: 0.2s; }
        .layer:nth-child(3) { animation-delay: 0.3s; }
        .layer:nth-child(4) { animation-delay: 0.4s; }
        .layer:nth-child(5) { animation-delay: 0.5s; }
        .layer:nth-child(6) { animation-delay: 0.6s; }
        .layer:nth-child(7) { animation-delay: 0.7s; }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Layer Number Badge */
        .layer-badge {
            flex-shrink: 0;
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 38px;
            font-weight: 900;
            color: white;
            box-shadow: 0 10px 30px rgba(10, 77, 146, 0.4);
            position: relative;
            z-index: 2;
        }

        /* Layer Content Card */
        .layer-card {
            flex: 1;
            background: white;
            border: 2px solid var(--gray-300);
            border-radius: 12px;
            overflow: hidden;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.06);
        }

        .layer-card:hover {
            border-color: var(--primary);
            box-shadow: 0 12px 40px rgba(10, 77, 146, 0.15);
            transform: translateY(-3px);
        }

        .layer-header {
            background: linear-gradient(135deg, var(--gray-900) 0%, var(--gray-800) 100%);
            padding: 22px 30px;
            border-bottom: 3px solid var(--accent);
        }

        .layer-name {
            font-size: 20px;
            font-weight: 900;
            color: white;
            margin-bottom: 6px;
            letter-spacing: -0.3px;
        }

        .layer-type {
            font-size: 13px;
            color: rgba(255, 255, 255, 0.75);
            text-transform: uppercase;
            letter-spacing: 0.8px;
            font-weight: 600;
        }

        .layer-body {
            padding: 30px;
        }

        /* Components Grid */
        .components {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
            gap: 18px;
        }

        .component {
            background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
            border: 2px solid var(--gray-300);
            border-radius: 10px;
            padding: 20px;
            transition: all 0.3s ease;
            cursor: default;
        }

        .component:hover {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            border-color: var(--primary);
            transform: translateY(-4px) scale(1.02);
            box-shadow: 0 12px 28px rgba(10, 77, 146, 0.25);
        }

        .component:hover .comp-icon {
            transform: scale(1.15) rotate(5deg);
            filter: brightness(0) invert(1);
        }

        .component:hover .comp-name,
        .component:hover .comp-desc {
            color: white;
        }

        .comp-icon {
            font-size: 36px;
            margin-bottom: 14px;
            display: block;
            transition: all 0.3s ease;
        }

        .comp-name {
            font-size: 15px;
            font-weight: 700;
            color: var(--dark);
            margin-bottom: 8px;
            transition: color 0.3s ease;
        }

        .comp-desc {
            font-size: 12px;
            color: var(--gray-700);
            line-height: 1.6;
            transition: color 0.3s ease;
            font-family: 'JetBrains Mono', monospace;
        }

        /* Key Features Section */
        .features-section {
            margin-top: 70px;
            background: linear-gradient(135deg, var(--dark) 0%, var(--gray-900) 100%);
            border-radius: 16px;
            padding: 55px;
            color: white;
            position: relative;
            overflow: hidden;
        }

        .features-section::before {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 40%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 111, 0, 0.1));
            pointer-events: none;
        }

        .features-section h3 {
            font-size: 32px;
            font-weight: 900;
            text-align: center;
            margin-bottom: 45px;
            position: relative;
            z-index: 2;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 28px;
            position: relative;
            z-index: 2;
        }

        .feature {
            background: rgba(255, 255, 255, 0.06);
            backdrop-filter: blur(10px);
            border: 2px solid rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            padding: 32px;
            transition: all 0.3s ease;
        }

        .feature:hover {
            background: rgba(255, 255, 255, 0.12);
            border-color: var(--accent);
            transform: translateY(-6px);
        }

        .feature-icon {
            width: 64px;
            height: 64px;
            background: linear-gradient(135deg, var(--accent) 0%, #ff8f00 100%);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            margin-bottom: 22px;
            box-shadow: 0 8px 24px rgba(255, 111, 0, 0.4);
        }

        .feature-title {
            font-size: 19px;
            font-weight: 700;
            margin-bottom: 14px;
        }

        .feature-desc {
            font-size: 14px;
            line-height: 1.75;
            opacity: 0.9;
        }

        /* Tech Stack Section */
        .tech-section {
            margin-top: 70px;
            padding: 55px;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 16px;
        }

        .tech-section h3 {
            font-size: 32px;
            font-weight: 900;
            color: var(--dark);
            text-align: center;
            margin-bottom: 45px;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
        }

        .tech-category {
            background: white;
            border: 2px solid var(--gray-300);
            border-radius: 12px;
            padding: 32px;
            transition: all 0.3s ease;
        }

        .tech-category:hover {
            border-color: var(--primary);
            box-shadow: 0 10px 35px rgba(10, 77, 146, 0.15);
        }

        .tech-header {
            display: flex;
            align-items: center;
            gap: 14px;
            margin-bottom: 24px;
        }

        .tech-icon {
            width: 48px;
            height: 48px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
        }

        .tech-title {
            font-size: 18px;
            font-weight: 700;
            color: var(--dark);
        }

        .tech-list {
            list-style: none;
        }

        .tech-item {
            padding: 13px 0;
            border-bottom: 1px solid var(--gray-300);
            font-size: 14px;
            color: var(--gray-800);
            display: flex;
            align-items: center;
            gap: 12px;
            font-family: 'JetBrains Mono', monospace;
        }

        .tech-item:last-child {
            border-bottom: none;
        }

        .tech-item::before {
            content: "▹";
            color: var(--primary);
            font-weight: bold;
            font-size: 18px;
        }

        /* Footer */
        .doc-footer {
            background: var(--gray-900);
            padding: 35px 60px;
            border-top: 4px solid var(--accent);
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .footer-left {
            color: rgba(255, 255, 255, 0.8);
            font-size: 13px;
            line-height: 1.6;
        }

        .footer-left strong {
            color: white;
            font-weight: 700;
            display: block;
            margin-bottom: 4px;
        }

        .footer-right {
            display: flex;
            gap: 30px;
        }

        .footer-badge {
            display: flex;
            align-items: center;
            gap: 8px;
            color: rgba(255, 255, 255, 0.8);
            font-size: 13px;
            font-weight: 600;
        }

        @media (max-width: 1200px) {
            .components {
                grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            }
        }

        @media (max-width: 768px) {
            .doc-content {
                padding: 30px 20px;
            }

            .doc-header {
                padding: 30px 20px;
            }

            .layer {
                flex-direction: column;
            }

            .arch-layers::before {
                display: none;
            }

            .components,
            .features-grid,
            .tech-grid {
                grid-template-columns: 1fr;
            }

            .doc-footer {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <div class="document-wrapper">
        <!-- Document Header -->
        <div class="doc-header">
            <div class="header-content">
                <div class="doc-type">Arquitectura General de Infraestructura Cloud</div>
                <h1>Arquitectura General</h1>
                <h2>Microservicios en Cloud Híbrido (Cloud-First con Edge Computing)</h2>
                <div class="header-meta">
                    <div class="meta-item">
                        <div class="meta-icon">🏢</div>
                        <span>Centro Comercial Virtual</span>
                    </div>
                    <div class="meta-item">
                        <div class="meta-icon">📅</div>
                        <span>Febrero 2026</span>
                    </div>
                    <div class="meta-item">
                        <div class="meta-icon">👤</div>
                        <span>Arquitecto de Infraestructura Cloud</span>
                    </div>
                    <div class="meta-item">
                        <div class="meta-icon">📊</div>
                        <span>Documento v1.0</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Document Content -->
        <div class="doc-content">
            <!-- Executive Summary -->
            <div class="exec-summary">
                <h3>Resumen Ejecutivo de Arquitectura</h3>
                <p>
                    La arquitectura propuesta implementa un modelo cloud-first de 7 capas con microservicios distribuidos, 
                    diseñado para soportar de 10,000 a 100,000+ usuarios concurrentes sin rediseño arquitectónico fundamental. 
                    Integra edge computing mediante Cloudflare CDN (150+ PoPs globales), arquitectura híbrida que combina 
                    servicios gestionados (PaaS) con infraestructura containerizada, y observabilidad total mediante APM, 
                    distributed tracing y monitoreo 24/7. El diseño garantiza SLA 99.5% uptime, tiempos de respuesta API <500ms (p95), 
                    First Contentful Paint <3s, y escalabilidad horizontal automática basada en métricas de CPU, memoria y throughput.
                </p>
            </div>

            <!-- Architecture Title -->
            <div class="arch-title">
                <h2>Arquitectura de 7 Capas - Cloud Híbrido</h2>
                <p>Modelo de referencia para plataforma digital de microempresas</p>
            </div>

            <!-- Architecture Layers -->
            <div class="arch-layers">
                <!-- Layer 1 -->
                <div class="layer">
                    <div class="layer-badge">1</div>
                    <div class="layer-card">
                        <div class="layer-header">
                            <div class="layer-name">Capa de Usuarios</div>
                            <div class="layer-type">Client Access Layer - Múltiples Puntos de Entrada</div>
                        </div>
                        <div class="layer-body">
                            <div class="components">
                                <div class="component">
                                    <span class="comp-icon">🌐</span>
                                    <div class="comp-name">Web Browsers</div>
                                    <div class="comp-desc">Chrome 90+, Firefox 88+, Safari 14+, Edge 90+</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📱</span>
                                    <div class="comp-name">Mobile Apps</div>
                                    <div class="comp-desc">iOS 14+, Android 10+, PWA responsive</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🔌</span>
                                    <div class="comp-name">API Clients</div>
                                    <div class="comp-desc">RESTful, GraphQL, Webhooks, OpenAPI 3.0</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Layer 2 -->
                <div class="layer">
                    <div class="layer-badge">2</div>
                    <div class="layer-card">
                        <div class="layer-header">
                            <div class="layer-name">CDN + Seguridad Edge</div>
                            <div class="layer-type">Edge Computing - Cloudflare Global Network (150+ PoPs)</div>
                        </div>
                        <div class="layer-body">
                            <div class="components">
                                <div class="component">
                                    <span class="comp-icon">🌍</span>
                                    <div class="comp-name">Cloudflare CDN</div>
                                    <div class="comp-desc">150+ PoPs, Smart Routing, Brotli compression</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🛡️</span>
                                    <div class="comp-name">WAF + DDoS Protection</div>
                                    <div class="comp-desc">130 Tbps capacity, OWASP Top 10, Bot Management</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🔒</span>
                                    <div class="comp-name">SSL/TLS 1.3</div>
                                    <div class="comp-desc">Auto-certificates, HTTP/2, HTTP/3 QUIC</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">⚡</span>
                                    <div class="comp-name">Edge Workers</div>
                                    <div class="comp-desc">Serverless <50ms, KV Storage, geo-routing</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Layer 3 -->
                <div class="layer">
                    <div class="layer-badge">3</div>
                    <div class="layer-card">
                        <div class="layer-header">
                            <div class="layer-name">Balanceador de Carga</div>
                            <div class="layer-type">Load Balancing - Distribución y Alta Disponibilidad</div>
                        </div>
                        <div class="layer-body">
                            <div class="components">
                                <div class="component">
                                    <span class="comp-icon">⚖️</span>
                                    <div class="comp-name">Application LB</div>
                                    <div class="comp-desc">Round-Robin, Sticky sessions, Path routing</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">❤️</span>
                                    <div class="comp-name">Health Checks</div>
                                    <div class="comp-desc">HTTP checks 10s, Failover <30s, 3-strikes</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📈</span>
                                    <div class="comp-name">Auto-Scaling</div>
                                    <div class="comp-desc">CPU >70%, Memory >80%, RPS >1K. Min:2 Max:20</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Layer 4 -->
                <div class="layer">
                    <div class="layer-badge">4</div>
                    <div class="layer-card">
                        <div class="layer-header">
                            <div class="layer-name">Capa de Aplicación</div>
                            <div class="layer-type">Application Tier - Frontend SSR & Backend API</div>
                        </div>
                        <div class="layer-body">
                            <div class="components">
                                <div class="component">
                                    <span class="comp-icon">⚛️</span>
                                    <div class="comp-name">Next.js 14 Frontend</div>
                                    <div class="comp-desc">SSR/SSG/ISR, React 18, TypeScript, Tailwind</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🟢</span>
                                    <div class="comp-name">Node.js 20 LTS Backend</div>
                                    <div class="comp-desc">Express/Fastify, 2GB RAM, 2vCPU, 200-300 conn</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🔄</span>
                                    <div class="comp-name">Instance Pool</div>
                                    <div class="comp-desc">Stateless, Rolling updates, Zero-downtime</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Layer 5 -->
                <div class="layer">
                    <div class="layer-badge">5</div>
                    <div class="layer-card">
                        <div class="layer-header">
                            <div class="layer-name">Microservicios Distribuidos</div>
                            <div class="layer-type">Service Layer - 9 Servicios Independientes Escalables</div>
                        </div>
                        <div class="layer-body">
                            <div class="components">
                                <div class="component">
                                    <span class="comp-icon">🔐</span>
                                    <div class="comp-name">Auth Service</div>
                                    <div class="comp-desc">JWT 24h, OAuth 2.0, MFA, Sessions Redis</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🏢</span>
                                    <div class="comp-name">Business Service</div>
                                    <div class="comp-desc">CRUD empresas, Profiles, Geo, Categories</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📦</span>
                                    <div class="comp-name">Product Service</div>
                                    <div class="comp-desc">Inventory, Variants, Pricing, Stock sync</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📢</span>
                                    <div class="comp-name">Campaign Service</div>
                                    <div class="comp-desc">Ads, Scheduler, Meta API, Email campaigns</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📊</span>
                                    <div class="comp-name">Analytics Service</div>
                                    <div class="comp-desc">Events, KPIs (CTR/ROI), Reports, Dashboards</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">💳</span>
                                    <div class="comp-name">Payment Service</div>
                                    <div class="comp-desc">Stripe, PayPal, Subscriptions, Webhooks</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🔔</span>
                                    <div class="comp-name">Notification Service</div>
                                    <div class="comp-desc">Email SendGrid/SES, SMS Twilio, Push FCM</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🖼️</span>
                                    <div class="comp-name">Media Service</div>
                                    <div class="comp-desc">Upload, Compress, Resize, WebP, CDN sync</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🔍</span>
                                    <div class="comp-name">Search Service</div>
                                    <div class="comp-desc">Meilisearch, Full-text, Autocomplete <50ms</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Layer 6 -->
                <div class="layer">
                    <div class="layer-badge">6</div>
                    <div class="layer-card">
                        <div class="layer-header">
                            <div class="layer-name">Capa de Datos</div>
                            <div class="layer-type">Data Layer - Persistencia, Cache, Message Queue</div>
                        </div>
                        <div class="layer-body">
                            <div class="components">
                                <div class="component">
                                    <span class="comp-icon">🐘</span>
                                    <div class="comp-name">PostgreSQL 15+ Primary</div>
                                    <div class="comp-desc">25GB SSD, 2GB RAM, JSONB, Backups 30d</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📖</span>
                                    <div class="comp-name">Read Replica</div>
                                    <div class="comp-desc">Async replication, Lag <5s, RTO 30s</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">⚡</span>
                                    <div class="comp-name">Redis 7+ Cache</div>
                                    <div class="comp-desc">1GB RAM, 1M cmd/day, TTL 5-15min, LRU</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🐰</span>
                                    <div class="comp-name">RabbitMQ 3.12+</div>
                                    <div class="comp-desc">1M msg/month, DLQ, Retry 3x exponential</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🔎</span>
                                    <div class="comp-name">Meilisearch</div>
                                    <div class="comp-desc">100K docs, Typo tolerance, Faceting</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Layer 7 -->
                <div class="layer">
                    <div class="layer-badge">7</div>
                    <div class="layer-card">
                        <div class="layer-header">
                            <div class="layer-name">Storage & Integraciones</div>
                            <div class="layer-type">Integration Layer - Object Storage & External Services</div>
                        </div>
                        <div class="layer-body">
                            <div class="components">
                                <div class="component">
                                    <span class="comp-icon">☁️</span>
                                    <div class="comp-name">Cloudflare R2</div>
                                    <div class="comp-desc">100GB storage, S3-compatible, Zero egress</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📧</span>
                                    <div class="comp-name">SendGrid / SES</div>
                                    <div class="comp-desc">50K emails/mo, Templates, Tracking, DKIM</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📱</span>
                                    <div class="comp-name">Meta Business API</div>
                                    <div class="comp-desc">FB/IG Ads, Campaign creation, Analytics</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">💬</span>
                                    <div class="comp-name">WhatsApp Business API</div>
                                    <div class="comp-desc">Messaging, Templates, Catalog integration</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">💰</span>
                                    <div class="comp-name">Stripe / PayPal</div>
                                    <div class="comp-desc">Payments, PCI-DSS L1, Webhooks, Invoicing</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">🐛</span>
                                    <div class="comp-name">Sentry APM</div>
                                    <div class="comp-desc">Error tracking, Performance, 50K events/mo</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📈</span>
                                    <div class="comp-name">BetterStack</div>
                                    <div class="comp-desc">Uptime 60s checks, 5 locations, Alerting</div>
                                </div>
                                <div class="component">
                                    <span class="comp-icon">📊</span>
                                    <div class="comp-name">Plausible Analytics</div>
                                    <div class="comp-desc">100K pageviews/mo, GDPR, Privacy-friendly</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Key Features -->
            <div class="features-section">
                <h3>Características Clave de la Arquitectura</h3>
                <div class="features-grid">
                    <div class="feature">
                        <div class="feature-icon">🔒</div>
                        <div class="feature-title">Seguridad Multi-Capa</div>
                        <div class="feature-desc">
                            WAF con DDoS protection 130 Tbps, TLS 1.3 encryption end-to-end, JWT + OAuth 2.0 authentication, 
                            Bcrypt password hashing (cost 12), cumplimiento GDPR automático, audit logs completos con retención 90 días.
                        </div>
                    </div>
                    <div class="feature">
                        <div class="feature-icon">📈</div>
                        <div class="feature-title">Escalabilidad Horizontal Ilimitada</div>
                        <div class="feature-desc">
                            Auto-scaling automático de 2 a 20+ instancias basado en CPU >70%, memoria >80%, RPS >1000. 
                            Arquitectura stateless permite escalar de 10K a 100K+ usuarios sin cambios arquitectónicos fundamentales.
                        </div>
                    </div>
                    <div class="feature">
                        <div class="feature-icon">⚡</div>
                        <div class="feature-title">Rendimiento de Clase Mundial</div>
                        <div class="feature-desc">
                            CDN 150+ PoPs globales, Redis cache L1/L2, Edge computing <50ms. Garantiza FCP <3s (p95), 
                            API response <500ms (p95), database queries <100ms (p99). Throughput sostenido 5K+ RPS.
                        </div>
                    </div>
                    <div class="feature">
                        <div class="feature-icon">🔄</div>
                        <div class="feature-title">Alta Disponibilidad Garantizada</div>
                        <div class="feature-desc">
                            SLA 99.5% uptime con penalización contractual, health checks cada 10s, failover automático <30s, 
                            backups diarios con retención 30 días, deployment multi-zona, RTO 4 horas, RPO 1 hora.
                        </div>
                    </div>
                    <div class="feature">
                        <div class="feature-icon">🧩</div>
                        <div class="feature-title">Desacoplamiento Total de Servicios</div>
                        <div class="feature-desc">
                            9 microservicios independientes con deployments separados, circuit breakers automáticos, 
                            message queues (RabbitMQ) para procesamiento asíncrono, event-driven architecture, contracts versionados.
                        </div>
                    </div>
                    <div class="feature">
                        <div class="feature-icon">📊</div>
                        <div class="feature-title">Observabilidad Total 360°</div>
                        <div class="feature-desc">
                            APM con Sentry (distributed tracing), uptime monitoring 24/7 desde 5 ubicaciones globales, 
                            log aggregation centralizado, alerting multi-canal (email/SMS/Slack), dashboards en tiempo real con KPIs de negocio.
                        </div>
                    </div>
                </div>
            </div>

            <!-- Tech Stack -->
            <div class="tech-section">
                <h3>Stack Tecnológico Completo por Categoría</h3>
                <div class="tech-grid">
                    <div class="tech-category">
                        <div class="tech-header">
                            <div class="tech-icon">⚛️</div>
                            <div class="tech-title">Frontend</div>
                        </div>
                        <ul class="tech-list">
                            <li class="tech-item">Next.js 14 (App Router SSR/SSG)</li>
                            <li class="tech-item">React 18 + TypeScript 5+</li>
                            <li class="tech-item">Tailwind CSS + shadcn/ui</li>
                            <li class="tech-item">React Query + Zustand</li>
                        </ul>
                    </div>

                    <div class="tech-category">
                        <div class="tech-header">
                            <div class="tech-icon">🟢</div>
                            <div class="tech-title">Backend</div>
                        </div>
                        <ul class="tech-list">
                            <li class="tech-item">Node.js 20 LTS</li>
                            <li class="tech-item">Express.js / Fastify</li>
                            <li class="tech-item">TypeScript + Prisma ORM</li>
                            <li class="tech-item">Zod / Joi validation</li>
                        </ul>
                    </div>

                    <div class="tech-category">
                        <div class="tech-header">
                            <div class="tech-icon">💾</div>
                            <div class="tech-title">Bases de Datos</div>
                        </div>
                        <ul class="tech-list">
                            <li class="tech-item">PostgreSQL 15+ (Primary + Replica)</li>
                            <li class="tech-item">Redis 7+ (Cache in-memory)</li>
                            <li class="tech-item">Meilisearch (Full-text search)</li>
                            <li class="tech-item">RabbitMQ 3.12+ (Message queue)</li>
                        </ul>
                    </div>

                    <div class="tech-category">
                        <div class="tech-header">
                            <div class="tech-icon">☁️</div>
                            <div class="tech-title">Infraestructura Cloud</div>
                        </div>
                        <ul class="tech-list">
                            <li class="tech-item">Vercel (Frontend deployment)</li>
                            <li class="tech-item">Railway / Render (Backend PaaS)</li>
                            <li class="tech-item">DigitalOcean (Managed databases)</li>
                            <li class="tech-item">Cloudflare (CDN + WAF + R2)</li>
                        </ul>
                    </div>

                    <div class="tech-category">
                        <div class="tech-header">
                            <div class="tech-icon">🔐</div>
                            <div class="tech-title">Seguridad</div>
                        </div>
                        <ul class="tech-list">
                            <li class="tech-item">JWT tokens + OAuth 2.0</li>
                            <li class="tech-item">Bcrypt password hashing</li>
                            <li class="tech-item">TLS 1.3 encryption</li>
                            <li class="tech-item">Cloudflare WAF + DDoS 130 Tbps</li>
                        </ul>
                    </div>

                    <div class="tech-category">
                        <div class="tech-header">
                            <div class="tech-icon">📊</div>
                            <div class="tech-title">Monitoreo & DevOps</div>
                        </div>
                        <ul class="tech-list">
                            <li class="tech-item">Sentry (APM + Error tracking)</li>
                            <li class="tech-item">BetterStack (Uptime monitoring)</li>
                            <li class="tech-item">Plausible (Web analytics GDPR)</li>
                            <li class="tech-item">GitHub Actions (CI/CD pipelines)</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <!-- Document Footer -->
        <div class="doc-footer">
            <div class="footer-left">
                <strong>Centro Comercial Virtual</strong>
                Arquitectura General - Microservicios en Cloud Híbrido con Edge Computing<br>
                Grupo 4 Proyecto II
            </div>
            <div class="footer-right">
                <div class="footer-badge">
                    <span>📅</span>
                    <span>Febrero 2026</span>
                </div>
                <div class="footer-badge">
                    <span>📄</span>
                    <span>Versión 1.0</span>
                </div>
                <div class="footer-badge">
                    <span>🔒</span>
                    <span>Confidencial</span>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
