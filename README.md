# -ng-Ng-c-T-n-
<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đặng Ngọc Tân - Personal Website</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#2563eb',
                        darkBg: '#0f172a',
                    }
                }
            }
        }
    </script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased selection:bg-blue-500 selection:text-white">

    <!-- Header / Navigation -->
    <header class="fixed top-0 left-0 w-full z-50 bg-slate-900/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-4 h-16 flex items-center justify-between">
            <a href="#home" class="text-xl font-black tracking-wider text-blue-500">NGOC TAN.</a>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                <a href="#home" class="hover:text-blue-400 transition-colors">Trang chủ</a>
                <a href="#about" class="hover:text-blue-400 transition-colors">Giới thiệu</a>
                <a href="#hobbies" class="hover:text-blue-400 transition-colors">Sở thích</a>
                <a href="#subjects" class="hover:text-blue-400 transition-colors">Môn học</a>
                <a href="#music" class="hover:text-blue-400 transition-colors">Âm nhạc</a>
                <a href="#gallery" class="hover:text-blue-400 transition-colors">Thư viện ảnh</a>
                <a href="#video" class="hover:text-blue-400 transition-colors">Video</a>
                <a href="#links" class="hover:text-blue-400 transition-colors">Liên kết</a>
            </nav>
            <!-- Mobile Menu Button -->
            <button id="menu-btn" class="md:hidden text-slate-300 hover:text-white focus:outline-none">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>
        </div>
        <!-- Mobile Nav Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-slate-900 border-b border-slate-800 px-4 pt-2 pb-4 space-y-2">
            <a href="#home" class="block py-2 hover:text-blue-400">Trang chủ</a>
            <a href="#about" class="block py-2 hover:text-blue-400">Giới thiệu</a>
            <a href="#hobbies" class="block py-2 hover:text-blue-400">Sở thích</a>
            <a href="#subjects" class="block py-2 hover:text-blue-400">Môn học</a>
            <a href="#music" class="block py-2 hover:text-blue-400">Âm nhạc</a>
            <a href="#gallery" class="block py-2 hover:text-blue-400">Thư viện ảnh</a>
            <a href="#video" class="block py-2 hover:text-blue-400">Video</a>
            <a href="#links" class="block py-2 hover:text-blue-400">Liên kết</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-center pt-20 bg-gradient-to-b from-slate-900 via-slate-800 to-slate-900 text-center px-4">
        <div class="max-w-3xl space-y-6">
            <span class="inline-block py-1 px-3 rounded-full bg-blue-500/10 text-blue-400 text-xs font-semibold tracking-widest uppercase border border-blue-500/20">
                WELCOME TO MY WEBSITE
            </span>
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white">
                ĐẶNG NGỌC TÂN
            </h1>
            <p class="text-lg sm:text-xl text-slate-400 max-w-xl mx-auto">
                Chào mừng bạn đến với không gian cá nhân của mình. <br>
                <span class="text-blue-400 font-semibold">Học hỏi · Trải nghiệm · Khám phá</span>
            </p>
            <div class="pt-4 flex justify-center gap-4">
                <a href="#about" class="px-6 py-3 rounded-xl bg-blue-600 text-white font-medium hover:bg-blue-500 transition shadow-lg shadow-blue-600/30">
                    Khám phá ngay
                </a>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="py-20 px-4 max-w-5xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-2">Giới thiệu bản thân</h2>
        <div class="w-16 h-1 bg-blue-500 mx-auto mb-12 rounded"></div>

        <div class="bg-slate-800/50 border border-slate-700/60 rounded-2xl p-8 shadow-xl flex flex-col md:flex-row gap-8 items-center">
            <div class="w-full md:w-1/3 flex justify-center">
                <div class="w-48 h-48 rounded-full bg-slate-700 overflow-hidden border-4 border-blue-500/30 shadow-inner">
                    <img src="images/anh-dai-dien.jpg" alt="Đặng Ngọc Tân" class="w-full h-full object-cover">
                </div>
            </div>
            <div class="w-full md:w-2/3 space-y-4 text-slate-300">
                <h3 class="text-2xl font-bold text-white">Đặng Ngọc Tân</h3>
                <p><strong class="text-white">Sở thích:</strong> Bóng rổ, Chạy bộ, Nghe nhạc</p>
                <p><strong class="text-white">Môn học yêu thích:</strong> Toán, Vật lý, Tiếng Anh</p>
                <blockquote class="p-4 bg-blue-950/40 border-l-4 border-blue-500 text-blue-200 italic rounded-r-lg">
                    "Shooter gonna shoot" — Tinh thần tự tin, tập trung tối đa và sẵn sàng nắm bắt mọi cơ hội để bứt phá.
                </blockquote>
                <p class="text-slate-400">
                    Mình là người yêu thích khám phá những điều mới, luôn muốn học hỏi, trải nghiệm và phát triển bản thân qua từng ngày trên hành trình chinh phục các mục tiêu phía trước.
                </p>
            </div>
        </div>
    </section>

    <!-- Hobbies Section -->
    <section id="hobbies" class="py-20 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-2">Sở thích của mình</h2>
        <p class="text-slate-400 text-center mb-4">Những hoạt động tạo nên năng lượng và màu sắc riêng</p>
        <div class="w-16 h-1 bg-blue-500 mx-auto mb-12 rounded"></div>

        <div class="grid md:grid-cols-2 gap-8">
            <!-- Bóng rổ -->
            <div class="bg-slate-800/40 border border-slate-700 rounded-2xl overflow-hidden hover:border-blue-500/50 transition duration-300 group">
                <div class="h-56 overflow-hidden">
                    <img src="images/basketball-1.jpg" alt="Bóng rổ" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                </div>
                <div class="p-6 space-y-2">
                    <h3 class="text-xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-basketball text-blue-500"></i> Bóng rổ
                    </h3>
                    <p class="text-slate-400">
                        Môn thể thao rèn luyện sức bền, sự quyết đoán, tư duy chiến thuật nhạy bén và tinh thần đồng đội gắn kết trên sân đấu.
                    </p>
                </div>
            </div>

            <!-- Chạy bộ (Gắn ảnh Strava 10km) -->
            <div class="bg-slate-800/40 border border-slate-700 rounded-2xl overflow-hidden hover:border-blue-500/50 transition duration-300 group">
                <div class="h-56 overflow-hidden">
                    <img src="images/strava-run.jpg" alt="Chạy bộ Strava" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                </div>
                <div class="p-6 space-y-2">
                    <h3 class="text-xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-person-running text-blue-500"></i> Chạy bộ (10.01 km)
                    </h3>
                    <p class="text-slate-400">
                        Duy trì sự kiên trì, ý chí chinh phục cung đường dài và tận hưởng khoảnh khắc năng lượng tích cực lúc hoàng hôn.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Subjects Section -->
    <section id="subjects" class="py-20 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-2">Môn học yêu thích</h2>
        <div class="w-16 h-1 bg-blue-500 mx-auto mb-12 rounded"></div>

        <div class="grid md:grid-cols-3 gap-6">
            <div class="bg-slate-800/50 border border-slate-700 p-6 rounded-2xl hover:bg-slate-800 transition">
                <div class="w-12 h-12 bg-blue-500/10 rounded-xl flex items-center justify-center text-blue-400 text-xl font-bold mb-4">
                    <i class="fa-solid fa-calculator"></i>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Toán học</h3>
                <p class="text-slate-400 text-sm">Phát triển tư duy logic, rèn luyện sự nhạy bén và khả năng giải quyết vấn đề phức tạp.</p>
            </div>

            <div class="bg-slate-800/50 border border-slate-700 p-6 rounded-2xl hover:bg-slate-800 transition">
                <div class="w-12 h-12 bg-blue-500/10 rounded-xl flex items-center justify-center text-blue-400 text-xl font-bold mb-4">
                    <i class="fa-solid fa-atom"></i>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Vật lý</h3>
                <p class="text-slate-400 text-sm">Khám phá các quy luật vận hành của tự nhiên và ứng dụng thực tiễn vào đời sống.</p>
            </div>

            <div class="bg-slate-800/50 border border-slate-700 p-6 rounded-2xl hover:bg-slate-800 transition">
                <div class="w-12 h-12 bg-blue-500/10 rounded-xl flex items-center justify-center text-blue-400 text-xl font-bold mb-4">
                    <i class="fa-solid fa-globe"></i>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Tiếng Anh</h3>
                <p class="text-slate-400 text-sm">Công cụ sắc bén để mở rộng tri thức nhân loại và kết nối toàn cầu.</p>
            </div>
        </div>
    </section>

    <!-- Music Section (Thêm mới từ file music.jpg) -->
    <section id="music" class="py-20 px-4 max-w-5xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-2">Giai điệu yêu thích</h2>
        <p class="text-slate-400 text-center mb-4">Âm nhạc là nơi thư giãn và tiếp thêm cảm hứng</p>
        <div class="w-16 h-1 bg-blue-500 mx-auto mb-12 rounded"></div>

        <div class="bg-slate-800/50 border border-slate-700 rounded-2xl p-6 shadow-xl flex flex-col md:flex-row items-center gap-6">
            <div class="w-full md:w-1/3 aspect-square rounded-xl overflow-hidden shadow-md">
                <img src="https://raw.githubusercontent.com/sonny130556547-lab/Sonny-dep-zai/main/music.jpg" alt="Giai điệu âm nhạc" class="w-full h-full object-cover hover:scale-105 transition duration-500">
            </div>
            <div class="w-full md:w-2/3 space-y-4">
                <h3 class="text-2xl font-bold text-white flex items-center gap-2">
                    <i class="fa-solid fa-music text-blue-500"></i> Âm nhạc & Không gian thư giãn
                </h3>
                <p class="text-slate-300">
                    Những giai điệu nhẹ nhàng giúp giải tỏa căng thẳng sau giờ học và thi đấu thể thao, mang lại sự tập trung và năng lượng tích cực cho ngày mới.
                </p>
                <div class="pt-2">
                    <audio controls class="w-full rounded-lg accent-blue-500">
                        <source src="audio/music.mp3" type="audio/mpeg">
                        Trình duyệt của bạn không hỗ trợ phát âm thanh.
                    </audio>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section (Bao gồm ảnh Chạy bộ Strava & 4 ảnh Bóng rổ) -->
    <section id="gallery" class="py-20 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-2">Thư viện ảnh</h2>
        <p class="text-slate-400 text-center mb-4">Khoảnh khắc thể thao và thành tích</p>
        <div class="w-16 h-1 bg-blue-500 mx-auto mb-12 rounded"></div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="overflow-hidden rounded-xl border border-slate-700 shadow-lg group h-72">
                <img src="https://raw.githubusercontent.com/sonny130556547-lab/Sonny-dep-zai/main/music.jpg" alt="Âm nhạc" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
            </div>
            <div class="overflow-hidden rounded-xl border border-slate-700 shadow-lg group h-72">
                <img src="images/strava-run.jpg" alt="Thành tích chạy bộ Strava" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
            </div>
            <div class="overflow-hidden rounded-xl border border-slate-700 shadow-lg group h-72">
                <img src="images/basketball-1.jpg" alt="Bóng rổ 1" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
            </div>
            <div class="overflow-hidden rounded-xl border border-slate-700 shadow-lg group h-72">
                <img src="images/basketball-2.jpg" alt="Bóng rổ 2" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
            </div>
            <div class="overflow-hidden rounded-xl border border-slate-700 shadow-lg group h-72">
                <img src="images/basketball-3.jpg" alt="Bóng rổ 3" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
            </div>
            <div class="overflow-hidden rounded-xl border border-slate-700 shadow-lg group h-72">
                <img src="images/basketball-4.jpg" alt="Bóng rổ 4" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
            </div>
        </div>
    </section>

    <!-- Video Section -->
    <section id="video" class="py-20 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-2">Video của mình</h2>
        <p class="text-slate-400 text-center mb-4">Những thước phim ghi lại đam mê</p>
        <div class="w-16 h-1 bg-blue-500 mx-auto mb-12 rounded"></div>

        <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-slate-800 border border-slate-700 rounded-2xl overflow-hidden shadow-xl">
                <video controls playsinline class="w-full h-auto aspect-video object-cover">
                    <source src="videos/video-1.mp4" type="video/mp4">
                    Trình duyệt không hỗ trợ video.
                </video>
                <div class="p-4 text-center font-medium text-slate-300">Highlight Video 1</div>
            </div>
            <div class="bg-slate-800 border border-slate-700 rounded-2xl overflow-hidden shadow-xl">
                <video controls playsinline class="w-full h-auto aspect-video object-cover">
                    <source src="videos/video-2.mp4" type="video/mp4">
                    Trình duyệt không hỗ trợ video.
                </video>
                <div class="p-4 text-center font-medium text-slate-300">Highlight Video 2</div>
            </div>
        </div>
    </section>

    <!-- Favorite Links Section -->
    <section id="links" class="py-20 px-4 max-w-4xl mx-auto text-center">
        <h2 class="text-3xl font-bold mb-2">Liên kết yêu thích</h2>
        <p class="text-slate-400 mb-4">Các trang web và nguồn cảm hứng</p>
        <div class="w-16 h-1 bg-blue-500 mx-auto mb-12 rounded"></div>

        <div class="flex flex-wrap justify-center gap-4">
            <a href="https://bwfbadminton.com/" target="_blank" rel="noopener" class="px-6 py-3 bg-slate-800 hover:bg-blue-600 border border-slate-700 rounded-xl transition font-medium flex items-center gap-2">
                <i class="fa-solid fa-link"></i> BWF Official
            </a>
            <a href="https://www.facebook.com/bwfbadminton" target="_blank" rel="noopener" class="px-6 py-3 bg-slate-800 hover:bg-blue-600 border border-slate-700 rounded-xl transition font-medium flex items-center gap-2">
                <i class="fa-brands fa-facebook"></i> Facebook BWF
            </a>
            <a href="https://vn.canon/" target="_blank" rel="noopener" class="px-6 py-3 bg-slate-800 hover:bg-blue-600 border border-slate-700 rounded-xl transition font-medium flex items-center gap-2">
                <i class="fa-solid fa-camera"></i> Canon Việt Nam
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 border-t border-slate-800 py-8 text-center text-slate-500 text-sm">
        <p>© 2026 <span class="text-slate-300 font-semibold">Đặng Ngọc Tân</span></p>
        <p class="mt-1">PERSONAL WEBSITE</p>
    </footer>

    <!-- Simple Mobile Menu Script -->
    <script>
        const btn = document.getElementById('menu-btn');
        const menu = document.getElementById('mobile-menu');
        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
