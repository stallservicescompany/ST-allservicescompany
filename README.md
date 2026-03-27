<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tinku Services | Premium Digital Solutions Basti</title>
    <meta name="description" content="Professional digital services in Ratanpur, Basti. Specializing in Web Development (₹6,999), Thumbnail Design (₹199), and Google Map Reviews (₹299).">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        primary: '#2563eb', 
                        accent: '#f97316',  
                        dark: '#020617',    
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #f8fafc; }
        .glass-nav { background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(12px); border-bottom: 1px solid rgba(0,0,0,0.05); }
        .service-card { transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
        .service-card:hover { transform: translateY(-10px); }
        .whatsapp-btn { animation: shadow-pulse 2s infinite; }
        @keyframes shadow-pulse {
            0% { box-shadow: 0 0 0 0 rgba(37, 211, 102, 0.4); }
            70% { box-shadow: 0 0 0 15px rgba(37, 211, 102, 0); }
            100% { box-shadow: 0 0 0 0 rgba(37, 211, 102, 0); }
        }
        .hero-pattern {
            background-image: radial-gradient(#2563eb 0.5px, transparent 0.5px);
            background-size: 24px 24px;
            mask-image: linear-gradient(to bottom, black, transparent);
        }
    </style>
</head>
<body class="font-sans text-slate-900 overflow-x-hidden">

    <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 glass-nav">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex items-center">
                    <a href="#" class="text-2xl font-extrabold tracking-tight text-primary flex items-center gap-2">
                        <div class="w-10 h-10 bg-primary text-white rounded-xl flex items-center justify-center">T</div>
                        TINKU <span class="text-slate-400 font-light">SERVICES</span>
                    </a>
                </div>
                
                <div class="hidden md:flex space-x-10 items-center">
                    <a href="#home" class="text-sm font-semibold hover:text-primary transition-colors">Home</a>
                    <a href="#services" class="text-sm font-semibold hover:text-primary transition-colors">Services</a>
                    <a href="#pricing" class="text-sm font-semibold hover:text-primary transition-colors">Pricing</a>
                    <a href="#portfolio" class="text-sm font-semibold hover:text-primary transition-colors text-accent">Portfolio</a>
                    <a href="https://wa.me/918874907689" target="_blank" class="bg-primary text-white px-7 py-2.5 rounded-full text-sm font-bold hover:bg-blue-700 shadow-lg shadow-blue-500/20 transition-all">Get a Quote</a>
                </div>

                <button class="md:hidden text-2xl" id="menuToggle">
                    <i class="fa-solid fa-bars-staggered"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Mobile Menu -->
    <div id="mobileMenu" class="fixed inset-0 bg-white z-[60] hidden flex-col items-center justify-center gap-8 text-2xl font-bold">
        <button class="absolute top-6 right-8" onclick="toggleMenu()"><i class="fa-solid fa-xmark"></i></button>
        <a href="#home" onclick="toggleMenu()">Home</a>
        <a href="#services" onclick="toggleMenu()">Services</a>
        <a href="#pricing" onclick="toggleMenu()">Pricing</a>
        <a href="#portfolio" onclick="toggleMenu()">Portfolio</a>
        <a href="https://wa.me/918874907689" onclick="toggleMenu()">Contact WhatsApp</a>
    </div>

    <!-- Hero Section -->
    <section id="home" class="relative pt-40 pb-24 bg-white overflow-hidden">
        <div class="absolute inset-0 hero-pattern opacity-10"></div>
        <div class="max-w-7xl mx-auto px-4 relative z-10">
            <div class="text-center">
                <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-blue-50 border border-blue-100 text-primary text-xs font-bold uppercase tracking-widest mb-6">
                    <span class="relative flex h-2 w-2">
                        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-primary opacity-75"></span>
                        <span class="relative inline-flex rounded-full h-2 w-2 bg-primary"></span>
                    </span>
                    Basti's Trusted Digital Partner
                </div>
                <h1 class="text-5xl md:text-7xl font-extrabold text-dark tracking-tight mb-8">
                    Grow Your Brand <br> <span class="text-primary italic">Professionally.</span>
                </h1>
                <p class="text-lg text-slate-500 max-w-2xl mx-auto mb-12 leading-relaxed">
                    Premium digital solutions from Ratanpur, Basti. Serving globally with top-tier websites, design, and reputation management.
                </p>
                <div class="flex flex-col sm:flex-row gap-5 justify-center">
                    <a href="https://wa.me/918874907689" target="_blank" class="bg-primary text-white px-10 py-5 rounded-2xl font-bold text-lg hover:scale-105 transition-all shadow-xl shadow-blue-500/30 flex items-center justify-center gap-2">
                        <i class="fa-brands fa-whatsapp"></i> Chat Now
                    </a>
                    <a href="https://drive.google.com/drive/folders/1bFNmAHI5sWRj2mf7sC04LJ75xuIUACQV" target="_blank" class="bg-slate-100 text-slate-700 px-10 py-5 rounded-2xl font-bold text-lg hover:bg-slate-200 transition-all flex items-center justify-center gap-3">
                        <i class="fa-brands fa-google-drive"></i> View Portfolio
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 gap-6">
                <div>
                    <h2 class="text-4xl font-bold mb-4">Our Expertise</h2>
                    <p class="text-slate-500">Quality results tailored to your budget.</p>
                </div>
                <a href="https://wa.me/918874907689" target="_blank" class="text-primary font-bold flex items-center gap-2 group">
                    Custom Requests <i class="fa-solid fa-arrow-right group-hover:translate-x-1 transition-transform"></i>
                </a>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="service-card p-10 bg-white rounded-[2rem] shadow-sm border border-slate-100">
                    <div class="w-16 h-16 bg-blue-50 text-primary rounded-2xl flex items-center justify-center text-3xl mb-8">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">Web Development</h3>
                    <p class="text-slate-600 mb-6">Complete responsive websites for shops and startups. Fast, clean, and modern.</p>
                    <div class="text-primary font-bold text-xl">₹6,999<span class="text-sm font-normal text-slate-400 italic"> starting</span></div>
                </div>

                <div class="service-card p-10 bg-white rounded-[2rem] shadow-sm border border-slate-100">
                    <div class="w-16 h-16 bg-red-50 text-red-500 rounded-2xl flex items-center justify-center text-3xl mb-8">
                        <i class="fa-solid fa-palette"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">Thumbnail Design</h3>
                    <p class="text-slate-600 mb-6">Viral-style YouTube thumbnails. Designed to grab attention and increase clicks.</p>
                    <div class="text-red-500 font-bold text-xl">₹199<span class="text-sm font-normal text-slate-400 italic"> per design</span></div>
                </div>

                <div class="service-card p-10 bg-white rounded-[2rem] shadow-sm border border-slate-100">
                    <div class="w-16 h-16 bg-green-50 text-green-600 rounded-2xl flex items-center justify-center text-3xl mb-8">
                        <i class="fa-solid fa-star"></i>
                    </div>
                    <h3 class="text-2xl font-bold mb-4">Map Reviews</h3>
                    <p class="text-slate-600 mb-6">Strategic local SEO boost with 15 verified, high-quality Google Map reviews.</p>
                    <div class="text-green-600 font-bold text-xl">₹299<span class="text-sm font-normal text-slate-400 italic"> for 15 reviews</span></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-extrabold mb-4">Fixed Pricing</h2>
                <p class="text-slate-500">Simple and transparent rates for your digital needs.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
                <!-- Plan 1 -->
                <div class="p-8 rounded-[2.5rem] bg-white border border-slate-200 flex flex-col items-center text-center">
                    <h4 class="text-xl font-bold mb-2">YT Thumbnails</h4>
                    <div class="text-4xl font-black mb-8">₹199 <span class="text-sm font-normal text-slate-400 italic">/ea</span></div>
                    <ul class="space-y-4 mb-10 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-check text-primary mr-2"></i> Custom Visuals</li>
                        <li><i class="fa-solid fa-check text-primary mr-2"></i> High CTR Layout</li>
                        <li><i class="fa-solid fa-check text-primary mr-2"></i> Fast Delivery</li>
                    </ul>
                    <a href="https://wa.me/918874907689?text=Hi, I want to order a Thumbnail Design." target="_blank" class="w-full py-4 bg-slate-100 text-slate-800 font-bold rounded-2xl hover:bg-slate-200 transition-all">Order via WhatsApp</a>
                </div>

                <!-- Featured Plan -->
                <div class="p-10 rounded-[2.5rem] bg-dark text-white shadow-2xl flex flex-col items-center text-center relative md:-translate-y-6">
                    <div class="absolute -top-4 left-1/2 -translate-x-1/2 bg-accent text-white px-5 py-1.5 rounded-full text-[10px] font-black uppercase tracking-widest">Best Value</div>
                    <h4 class="text-xl font-bold mb-2">Business Website</h4>
                    <div class="text-5xl font-black mb-8 text-primary">₹6,999</div>
                    <ul class="space-y-4 mb-10 text-white/70 text-sm">
                        <li><i class="fa-solid fa-circle-check text-accent mr-2"></i> 5 Pages Included</li>
                        <li><i class="fa-solid fa-circle-check text-accent mr-2"></i> WhatsApp Buttons</li>
                        <li><i class="fa-solid fa-circle-check text-accent mr-2"></i> Mobile Responsive</li>
                        <li><i class="fa-solid fa-circle-check text-accent mr-2"></i> Google Maps Setup</li>
                    </ul>
                    <a href="https://wa.me/918874907689?text=Hi, I want to order the Business Website Package for ₹6,999." target="_blank" class="w-full py-5 bg-primary text-white font-black rounded-2xl hover:bg-blue-700 shadow-xl shadow-blue-500/40 transition-all">Get Started Now</a>
                </div>

                <!-- Plan 3 -->
                <div class="p-8 rounded-[2.5rem] bg-white border border-slate-200 flex flex-col items-center text-center">
                    <h4 class="text-xl font-bold mb-2">Map Reviews</h4>
                    <div class="text-4xl font-black mb-8">₹299 <span class="text-sm font-normal text-slate-400 italic">/15 revs</span></div>
                    <ul class="space-y-4 mb-10 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-check text-primary mr-2"></i> High Quality Profiles</li>
                        <li><i class="fa-solid fa-check text-primary mr-2"></i> Rank Optimization</li>
                        <li><i class="fa-solid fa-check text-primary mr-2"></i> 100% Secure</li>
                    </ul>
                    <a href="https://wa.me/918874907689?text=Hi, I want to order 15 Map Reviews for ₹299." target="_blank" class="w-full py-4 bg-slate-100 text-slate-800 font-bold rounded-2xl hover:bg-slate-200 transition-all">Order Pack</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Drive CTA -->
    <section id="portfolio" class="py-24 bg-primary relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')]"></div>
        <div class="max-w-7xl mx-auto px-4 relative z-10 text-center text-white">
            <h2 class="text-4xl font-black mb-6">Our Portfolio</h2>
            <p class="text-white/80 text-lg mb-12 max-w-2xl mx-auto">Explore our collection of thumbnails and web designs directly in our cloud drive.</p>
            <a href="https://drive.google.com/drive/folders/1bFNmAHI5sWRj2mf7sC04LJ75xuIUACQV" target="_blank" class="inline-flex items-center gap-4 bg-white text-primary px-12 py-6 rounded-3xl font-black text-xl hover:scale-105 transition-all shadow-2xl">
                <i class="fa-brands fa-google-drive text-3xl"></i> BROWSE DRIVE
            </a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
                <div>
                    <h2 class="text-5xl font-black mb-8 tracking-tighter">Get in Touch</h2>
                    <p class="text-slate-500 mb-12">Message us directly for custom projects or specific inquiries.</p>
                    
                    <div class="space-y-10">
                        <div class="flex gap-6">
                            <div class="w-14 h-14 bg-slate-100 rounded-2xl flex items-center justify-center text-primary text-2xl flex-shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h5 class="font-bold text-lg">Address</h5>
                                <p class="text-slate-500">Ratanpur, Basti, Uttar Pradesh, 272001</p>
                            </div>
                        </div>
                        <div class="flex gap-6">
                            <div class="w-14 h-14 bg-slate-100 rounded-2xl flex items-center justify-center text-primary text-2xl flex-shrink-0">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h5 class="font-bold text-lg">WhatsApp Only</h5>
                                <p class="text-slate-500">8874907689</p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-16 flex gap-4">
                        <a href="https://www.instagram.com/workherestudents?igsh=NXh2czdreGo3bmx6" target="_blank" class="w-14 h-14 rounded-2xl bg-gradient-to-tr from-yellow-400 to-purple-600 text-white flex items-center justify-center text-2xl hover:scale-110 transition-transform"><i class="fa-brands fa-instagram"></i></a>
                        <a href="https://wa.me/918874907689" target="_blank" class="w-14 h-14 rounded-2xl bg-[#25D366] text-white flex items-center justify-center text-2xl hover:scale-110 transition-transform shadow-xl"><i class="fa-brands fa-whatsapp"></i></a>
                    </div>
                </div>

                <!-- Final Form Logic with your number -->
                <div class="bg-slate-50 p-10 rounded-[3rem] border border-slate-200">
                    <form onsubmit="event.preventDefault(); window.location.href='https://wa.me/918874907689?text=Hi, my name is ' + document.getElementById('usr_n').value + '. I am interested in ' + document.getElementById('svc').value;" class="space-y-6">
                        <div class="space-y-2">
                            <label class="text-xs font-black uppercase text-slate-400 ml-2">Name</label>
                            <input type="text" id="usr_n" placeholder="Your Name" class="w-full bg-white border border-slate-200 rounded-2xl px-6 py-4 focus:outline-none focus:ring-2 focus:ring-primary transition-all" required>
                        </div>
                        <div class="space-y-2">
                            <label class="text-xs font-black uppercase text-slate-400 ml-2">Interest</label>
                            <select id="svc" class="w-full bg-white border border-slate-200 rounded-2xl px-6 py-4 focus:outline-none focus:ring-2 focus:ring-primary transition-all" required>
                                <option>Business Website (₹6,999)</option>
                                <option>Thumbnails (₹199)</option>
                                <option>Map Reviews (₹299)</option>
                                <option>Custom Design</option>
                            </select>
                        </div>
                        <button type="submit" class="w-full bg-dark text-white font-black py-5 rounded-2xl hover:bg-slate-800 transition-all text-lg tracking-widest uppercase flex items-center justify-center gap-3">
                            <i class="fa-brands fa-whatsapp text-xl text-[#25D366]"></i> Continue to WhatsApp
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-white border-t border-slate-100 text-center">
        <div class="max-w-7xl mx-auto px-4 text-slate-400 text-sm">
            <p class="font-bold mb-2">TINKU SERVICES | 8874907689</p>
            <p>&copy; 2026 RATANPUR, BASTI | ALL RIGHTS RESERVED.</p>
        </div>
    </footer>

    <!-- Floating WhatsApp -->
    <a href="https://wa.me/918874907689" target="_blank" class="whatsapp-btn fixed bottom-8 right-8 z-[100] bg-[#25D366] text-white w-16 h-16 rounded-full flex items-center justify-center text-3xl shadow-2xl">
        <i class="fa-brands fa-whatsapp"></i>
    </a>

    <script>
        const menuToggle = document.getElementById('menuToggle');
        const mobileMenu = document.getElementById('mobileMenu');
        
        function toggleMenu() {
            mobileMenu.classList.toggle('hidden');
            mobileMenu.classList.toggle('flex');
            document.body.classList.toggle('overflow-hidden');
        }

        menuToggle.onclick = toggleMenu;

        window.onscroll = () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 20) {
                nav.classList.add('py-2', 'shadow-xl');
            } else {
                nav.classList.remove('py-2', 'shadow-xl');
            }
        };
    </script>
</body>
</html>
