<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wiby Catering - Hidangan Lezat, Momen Tak Terlupakan</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome untuk Icon -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Playfair Display & Plus Jakarta Sans -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        serif: ['Playfair Display', 'serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        brandCream: '#fdfbf7',
                        brandRose: '#9f5255', // Warna Rose Mewah
                        brandGold: '#c5a880', // Warna Emas Elegan
                        brandDark: '#2c1819',
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-brandCream text-brandDark font-sans antialiased">

    <!-- NAVBAR -->
    <nav class="fixed w-full z-50 bg-brandCream/80 backdrop-blur-md border-b border-brandGold/20">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex flex-col">
                    <span class="font-serif text-2xl font-bold tracking-wide text-brandRose">Wiby</span>
                    <span class="text-[10px] tracking-[0.2em] uppercase text-brandGold -mt-1">Catering & Cake</span>
                </div>
                <div class="hidden md:flex items-center space-x-8 text-sm font-medium tracking-wide">
                    <a href="#beranda" class="hover:text-brandRose transition-colors">Beranda</a>
                    <a href="#layanan" class="hover:text-brandRose transition-colors">Catering</a>
                    <a href="#kue" class="hover:text-brandRose transition-colors">Aneka Kue</a>
                    <a href="#kontak" class="bg-brandRose text-white px-5 py-2.5 rounded-full font-semibold hover:bg-brandDark transition-all shadow-md shadow-brandRose/10">Pesan Sekarang</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION (Dengan Animasi & Gambar Cantik) -->
    <section id="beranda" class="relative min-h-screen flex items-center pt-20 overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 lg:px-8 w-full grid md:grid-cols-12 gap-12 items-center">
            
            <!-- Teks Hero -->
            <div class="md:col-span-6 space-y-6 text-center md:text-left">
                <span class="inline-block text-xs font-bold tracking-[0.2em] uppercase text-brandGold bg-brandGold/10 px-4 py-2 rounded-full">
                    Cita Rasa Prima & Pelayanan Mewah
                </span>
                <h1 class="font-serif text-4xl sm:text-5xl lg:text-6xl font-normal leading-tight text-brandDark">
                    Sajian Istimewa dari <span class="italic text-brandRose font-medium">Wiby Catering</span>
                </h1>
                <p class="text-gray-600 text-base sm:text-lg max-w-md mx-auto md:mx-0 leading-relaxed">
                    Menghadirkan kelezatan catering profesional untuk berbagai acara penting Anda serta kemewahan aneka kue premium yang dibuat dengan bahan terbaik penuh cinta.
                </p>
                <div class="pt-4 flex flex-col sm:flex-row justify-center md:justify-start gap-4">
                    <a href="https://wa.me/6281234567890" target="_blank" class="inline-flex items-center justify-center gap-2 bg-brandRose text-white px-8 py-3.5 rounded-full font-semibold hover:bg-brandDark transition-all transform hover:-translate-y-0.5 shadow-lg shadow-brandRose/20">
                        <i class="fab fa-whatsapp"></i> Hubungi Konsultan Rasa
                    </a>
                </div>
            </div>

            <!-- Gambar dengan Efek Floating Animasi -->
            <div class="md:col-span-6 relative flex justify-center">
                <!-- Ornamen Lingkaran Emas di Background -->
                <div class="absolute w-72 h-72 rounded-full border border-brandGold/30 -top-8 animate-[spin_20s_linear_infinite]"></div>
                
                <!-- Gambar Utama (Animasi Naik Turun Lembut) -->
                <div class="relative w-80 sm:w-96 h-[450px] rounded-t-full overflow-hidden border-4 border-brandGold/40 shadow-2xl animate-[bounce_4s_infinite_ease-in-out]">
                    <img src="https://images.unsplash.com/photo-1555244162-803834f70033?q=80&w=600&auto=format&fit=crop" 
                         alt="Wiby Catering Premium Buffet" 
                         class="w-full h-full object-cover transition-transform duration-700 hover:scale-110">
                </div>
            </div>

        </div>
    </section>

    <!-- CATERING SECTION -->
    <section id="layanan" class="py-24 bg-white border-y border-brandGold/10">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16 space-y-3">
                <h2 class="text-xs font-bold text-brandGold uppercase tracking-[0.2em]">Layanan Utama</h2>
                <p class="font-serif text-3xl sm:text-4xl font-normal text-brandDark">Paket Catering Wiby</p>
                <div class="w-12 h-[1px] bg-brandGold mx-auto"></div>
            </div>

            <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="group bg-brandCream rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1519225495810-7512c696505a?q=80&w=500&auto=format&fit=crop" alt="Pernikahan Wiby Catering" class="w-full h-full object-cover group-hover:scale-105 transition-all duration-500">
                    </div>
                    <div class="p-6 space-y-3">
                        <h3 class="font-serif text-xl font-semibold text-brandDark">Wedding & Prasmanan</h3>
                        <p class="text-gray-600 text-sm leading-relaxed">Sajian prasmanan mewah dengan tata rias meja yang estetik untuk perayaan pernikahan impian Anda.</p>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="group bg-brandCream rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?q=80&w=500&auto=format&fit=crop" alt="Acara Kantor Wiby" class="w-full h-full object-cover group-hover:scale-105 transition-all duration-500">
                    </div>
                    <div class="p-6 space-y-3">
                        <h3 class="font-serif text-xl font-semibold text-brandDark">Corporate & Gathering</h3>
                        <p class="text-gray-600 text-sm leading-relaxed">Nasi box eksklusif, hidangan gubukan, dan menu *coffee break* berkualitas tinggi untuk kelancaran agenda formal Anda.</p>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="group bg-brandCream rounded-2xl overflow-hidden shadow-sm hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=500&auto=format&fit=crop" alt="Tumpeng Wiby Catering" class="w-full h-full object-cover group-hover:scale-105 transition-all duration-500">
                    </div>
                    <div class="p-6 space-y-3">
                        <h3 class="font-serif text-xl font-semibold text-brandDark">Tumpeng & Hampers Adat</h3>
                        <p class="text-gray-600 text-sm leading-relaxed">Kreasi tumpeng hias modern bercita rasa nusantara autentik serta hantaran syukuran keluarga yang anggun.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ANEKA KUE SECTION -->
    <section id="kue" class="py-24">
        <div class="max-w-7xl mx-auto px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16 space-y-3">
                <h2 class="text-xs font-bold text-brandGold uppercase tracking-[0.2em]">Pesta Manis</h2>
                <p class="font-serif text-3xl sm:text-4xl font-normal text-brandDark">Aneka Kue & Dessert Wiby</p>
                <div class="w-12 h-[1px] bg-brandGold mx-auto"></div>
            </div>

            <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Cake 1 -->
                <div class="text-center space-y-3 group">
                    <div class="w-full h-72 rounded-full overflow-hidden border border-brandGold/20 shadow-md group-hover:border-brandRose transition-all duration-300">
                        <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?q=80&w=400&auto=format&fit=crop" alt="Kue Wiby Catering" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <h4 class="font-serif text-lg font-medium text-brandDark">Signature Whole Cake</h4>
                    <p class="text-xs text-brandGold tracking-widest uppercase">Mulai Rp 250rb</p>
                </div>

                <!-- Cake 2 -->
                <div class="text-center space-y-3 group">
                    <div class="w-full h-72 rounded-full overflow-hidden border border-brandGold/20 shadow-md group-hover:border-brandRose transition-all duration-300">
                        <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?q=80&w=400&auto=format&fit=crop" alt="Pastry Wiby" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <h4 class="font-serif text-lg font-medium text-brandDark">Premium French Pastry</h4>
                    <p class="text-xs text-brandGold tracking-widest uppercase">Mulai Rp 15rb / pcs</p>
                </div>

                <!-- Cake 3 -->
                <div class="text-center space-y-3 group">
                    <div class="w-full h-72 rounded-full overflow-hidden border border-brandGold/20 shadow-md group-hover:border-brandRose transition-all duration-300">
                        <img src="https://images.unsplash.com/photo-1612240498936-65f5101365d2?q=80&w=400&auto=format&fit=crop" alt="Kue Tradisional Wiby" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <h4 class="font-serif text-lg font-medium text-brandDark">Jajanan Pasar Tampah</h4>
                    <p class="text-xs text-brandGold tracking-widest uppercase">Mulai Rp 180rb / Tampah</p>
                </div>

                <!-- Cake 4 -->
                <div class="text-center space-y-3 group">
                    <div class="w-full h-72 rounded-full overflow-hidden border border-brandGold/20 shadow-md group-hover:border-brandRose transition-all duration-300">
                        <img src="https://images.unsplash.com/photo-1563729784474-d77dbb933a9e?q=80&w=400&auto=format&fit=crop" alt="Cupcake Wiby" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                    </div>
                    <h4 class="font-serif text-lg font-medium text-brandDark">Custom Party Cupcake</h4>
                    <p class="text-xs text-brandGold tracking-widest uppercase">Mulai Rp 25rb / pcs</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CALL TO ACTION -->
    <section id="kontak" class="py-24 bg-brandDark text-brandCream relative overflow-hidden">
        <!-- Dekorasi Background Transparan -->
        <div class="absolute inset-0 bg-[radial-gradient(#c5a880_1px,transparent_1px)] [background-size:16px_16px] opacity-10"></div>
        
        <div class="max-w-4xl mx-auto px-6 text-center space-y-8 relative z-10">
            <h2 class="font-serif text-3xl sm:text-5xl font-normal tracking-wide">Rencanakan Menu Acara Anda Bersama Kami</h2>
            <p class="text-brandCream/70 text-base sm:text-lg max-w-xl mx-auto leading-relaxed">
                Slot pemesanan kustom dan layanan pesta besar terbatas setiap minggunya. Hubungi Wiby Catering sekarang untuk konsultasi menu dan uji rasa (*tester*).
            </p>
            <div class="pt-4">
                <a href="https://wa.me/6281234567890" target="_blank" class="inline-flex items-center gap-3 bg-brandGold text-brandDark px-10 py-4 rounded-full font-bold text-lg hover:bg-white transition-all transform hover:-translate-y-1 shadow-2xl">
                    <i class="fab fa-whatsapp text-xl"></i> Chat WhatsApp Sekarang
                </a>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-brandDark/95 border-t border-brandGold/10 py-12 text-center text-xs text-brandCream/40 tracking-wider">
        <div class="font-serif text-xl text-brandGold mb-4">Wiby Catering</div>
        <p>&copy; 2026 Wiby Catering & Cake. Dibuat dengan Komitmen Rasa Terbaik.</p>
    </footer>

</body>
</html>
