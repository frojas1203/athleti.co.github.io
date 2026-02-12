<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Athleti.co | The Transfer Portal, Decoded</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .hero-bg {
            background: linear-gradient(rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 0.8)), 
                        url('https://images.unsplash.com/photo-1526676037777-05a2337746b1?q=80&w=2070&auto=format&fit=crop');
            background-size: cover; background-position: center;
        }
    </style>
</head>
<body class="bg-slate-50">

    <nav class="bg-white border-b border-slate-200 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between h-20 items-center">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-blue-900 rounded-lg flex items-center justify-center text-white font-bold">A</div>
                <span class="text-2xl font-black text-slate-900 tracking-tighter italic">athlet<span class="text-red-600">i.co</span></span>
            </div>
            <div class="hidden md:flex space-x-8 font-bold text-slate-600">
                <a href="#features" class="hover:text-red-600 transition">Solution</a>
                <a href="#pricing" class="hover:text-red-600 transition">Pricing</a>
            </div>
            <button class="bg-blue-900 text-white px-6 py-2 rounded-full font-bold hover:bg-red-600 transition">Join Portal</button>
        </div>
    </nav>

    <header class="hero-bg min-h-[80vh] flex items-center justify-center text-center px-4">
        <div class="max-w-4xl">
            <h1 class="text-5xl md:text-7xl font-black text-white mb-6 uppercase tracking-tight">
                The Transfer Portal, <span class="text-red-500 italic underline decoration-blue-500">Decoded.</span>
            </h1>
            <p class="text-xl md:text-2xl text-slate-300 mb-10 leading-relaxed">
                Stop guessing. Start matching. The all-in-one recruiting operating system for elite athletes and coaches. [cite: 423]
            </p>
            <div class="flex flex-col md:flex-row gap-4 justify-center">
                <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white px-8 py-4 rounded-xl font-black text-lg shadow-2xl transition">CREATE PLAYER PROFILE</a>
                <a href="#" class="bg-red-600 hover:bg-red-700 text-white px-8 py-4 rounded-xl font-black text-lg shadow-2xl transition">FIND YOUR NEXT STAR</a>
            </div>
        </div>
    </header>

    <section id="features" class="py-24 max-w-7xl mx-auto px-4">
        <div class="text-center mb-20">
            <h2 class="text-4xl font-black text-slate-900 mb-4">RECRUITING IS BROKEN</h2> [cite: 260]
            <p class="text-slate-500 max-w-2xl mx-auto">We solve the "Penguin Problem" by providing immediate standalone value to both sides of the portal. [cite: 114, 138]</p>
        </div>
        
        <div class="grid md:grid-cols-2 gap-12">
            <div class="bg-white p-10 rounded-3xl shadow-sm border border-slate-200">
                <div class="bg-blue-100 w-12 h-12 rounded-xl flex items-center justify-center mb-6">
                    <i class="fa-solid fa-running text-blue-900 text-xl"></i>
                </div>
                <h3 class="text-2xl font-black mb-4">FOR ATHLETES</h3> [cite: 425]
                <ul class="space-y-4 text-slate-600">
                    <li class="flex items-center"><i class="fa-solid fa-check text-green-500 mr-3"></i> AI Highlight Engine: Automated game tape cut-ups. [cite: 454]</li>
                    <li class="flex items-center"><i class="fa-solid fa-check text-green-500 mr-3"></i> Fit Probability: See your D1/D2/D3 odds. [cite: 469]</li>
                    <li class="flex items-center"><i class="fa-solid fa-check text-green-500 mr-3"></i> Visibility Boosts: Get seen by more coaches. [cite: 464]</li>
                </ul>
            </div>

            <div class="bg-blue-900 p-10 rounded-3xl shadow-2xl text-white">
                <div class="bg-red-600 w-12 h-12 rounded-xl flex items-center justify-center mb-6">
                    <i class="fa-solid fa-clipboard-list text-white text-xl"></i>
                </div>
                <h3 class="text-2xl font-black mb-4 uppercase">For Coaches</h3> [cite: 483]
                <ul class="space-y-4 text-blue-100">
                    <li class="flex items-center"><i class="fa-solid fa-check text-red-500 mr-3"></i> AI Scouting Assistant: Natural language talent search. [cite: 504]</li>
                    <li class="flex items-center"><i class="fa-solid fa-check text-red-500 mr-3"></i> Recruiting Board: Trello-style pipeline management. [cite: 500]</li>
                    <li class="flex items-center"><i class="fa-solid fa-check text-red-500 mr-3"></i> Team Fit Scores: Identify scheme compatibility. [cite: 513]</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="pricing" class="bg-slate-100 py-24">
        <div class="max-w-5xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-black text-slate-900">CHOOSE YOUR EDGE</h2>
            </div>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-white p-8 rounded-2xl border border-slate-200">
                    <h4 class="font-bold text-slate-500 mb-2 uppercase">Basic</h4>
                    <p class="text-4xl font-black mb-6">$0 <span class="text-base font-normal text-slate-400">/mo</span></p>
                    <ul class="space-y-4 mb-8 text-slate-600">
                        <li>Standardized Profile [cite: 427]</li>
                        <li>10 Coach Messages/mo [cite: 446]</li>
                        <li>Basic Performance Stats [cite: 107]</li>
                    </ul>
                    <button class="w-full py-3 rounded-lg border-2 border-slate-900 font-bold hover:bg-slate-50 transition">Get Started</button>
                </div>
                <div class="bg-white p-8 rounded-2xl border-4 border-red-600 shadow-xl relative">
                    <div class="absolute -top-4 left-1/2 -translate-x-1/2 bg-red-600 text-white px-4 py-1 rounded-full text-xs font-bold uppercase">Most Popular</div>
                    <h4 class="font-bold text-slate-500 mb-2 uppercase">Premium</h4>
                    <p class="text-4xl font-black mb-6">$29 <span class="text-base font-normal text-slate-400">/mo</span></p>
                    <ul class="space-y-4 mb-8 text-slate-600">
                        <li class="font-bold">Everything in Basic</li>
                        <li>Unlimited Messaging [cite: 235]</li>
                        <li>Profile Visibility Boosts [cite: 110]</li>
                        <li>AI Highlight Reel Creator [cite: 108]</li>
                    </ul>
                    <button class="w-full py-3 rounded-lg bg-red-600 text-white font-bold hover:bg-red-700 transition">Go Premium</button>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-12 bg-white text-center border-t border-slate-200">
        <p class="text-slate-400 text-sm font-bold uppercase tracking-widest">&copy; 2026 Athleti.co | SMU Cox School of Business</p>
    </footer>

</body>
</html>
