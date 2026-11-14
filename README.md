<!DOCTYPE html>
<html lang="en" class="h-full bg-slate-50 dark:bg-slate-950">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SkillBridge AI — Agentic AI Personalized Learning & Career Platform</title>

  <!-- Typography: Plus Jakarta Sans & JetBrains Mono -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600;700&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Core Local Vendor Libraries (Zero Latency, Offline Ready) -->
  <script src="vendor/tailwind.js"></script>
  <script src="vendor/react.production.min.js"></script>
  <script src="vendor/react-dom.production.min.js"></script>
  <script src="vendor/babel.min.js"></script>
  <script src="vendor/lucide.min.js"></script>

  <!-- Tailwind Configuration -->
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['"Plus Jakarta Sans"', 'system-ui', '-apple-system', 'sans-serif'],
            mono: ['"JetBrains Mono"', 'monospace']
          },
          colors: {
            brand: {
              50: '#f5f3ff',
              100: '#ede9fe',
              200: '#ddd6fe',
              300: '#c4b5fd',
              400: '#a78bfa',
              500: '#8b5cf6',
              600: '#7c3aed',
              700: '#6d28d9',
              800: '#5b21b6',
              900: '#4c1d95',
            }
          }
        }
      }
    };
  </script>

  <!-- Application Styles -->
  <link rel="stylesheet" href="styles.css">
</head>
<body class="h-full font-sans text-slate-900 dark:text-slate-100 antialiased bg-slate-50 dark:bg-slate-950">
  <!-- React Mount Point -->
  <div id="root">
    <!-- Initial Loading State while Babel transpiles -->
    <div class="min-h-screen flex items-center justify-center bg-slate-900 text-white p-6">
      <div class="text-center space-y-4 max-w-sm">
        <div className="relative flex items-center justify-center">
          <div class="w-12 h-12 border-4 border-purple-500/20 border-t-purple-500 rounded-full animate-spin mx-auto"></div>
        </div>
        <h3 class="text-lg font-bold">SkillBridge AI</h3>
        <p class="text-xs text-slate-400">Initializing 4-Agent Orchestration Swarm...</p>
      </div>
    </div>
  </div>

  <!-- Pre-compiled High-Performance Application Bundle -->
  <script src="dist/app.compiled.js"></script>
</body>
</html>
