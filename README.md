# UTS_PPLMandiri
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio PPL PPG - Bayu Rahayu, S.Pd.</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        emerald: {
                            50: '#ecfdf5',
                            100: '#d1fae5',
                            500: '#10b981',
                            600: '#059669',
                            700: '#047857',
                            900: '#064e3b',
                        }
                    }
                }
            }
        }
    </script>
    <!-- Font Inter & Lucide Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 dark:bg-slate-900 dark:text-slate-100 transition-colors duration-300">

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-50 backdrop-blur-md bg-white/80 dark:bg-slate-900/80 border-b border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-emerald-600 to-teal-500 flex items-center justify-center text-white font-bold text-xl shadow-md shadow-emerald-500/20">
                        BR
                    </div>
                    <div>
                        <span class="font-bold text-slate-900 dark:text-white block leading-tight">Bayu Rahayu, S.Pd.</span>
                        <span class="text-xs text-emerald-600 dark:text-emerald-400 font-semibold">Portofolio PPL PPG</span>
                    </div>
                </div>

                <!-- Desktop Nav -->
                <nav class="hidden md:flex space-x-6 text-sm font-medium">
                    <a href="#profil" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition-colors">Profil</a>
                    <a href="#pendidikan" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition-colors">Riwayat</a>
                    <a href="#analisis" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition-colors">Analisis Artefak</a>
                    <a href="#refleksi" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition-colors">Refleksi Diri</a>
                    <a href="#artefak" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition-colors">Dokumen Artefak</a>
                </nav>

                <div class="flex items-center gap-3">
                    <button id="themeToggle" class="p-2 rounded-lg bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:bg-slate-200 dark:hover:bg-slate-700 transition-colors">
                        <i data-lucide="sun" class="w-5 h-5 hidden dark:block"></i>
                        <i data-lucide="moon" class="w-5 h-5 block dark:hidden"></i>
                    </button>
                    <a href="#artefak" class="hidden sm:inline-flex items-center gap-2 px-4 py-2 text-sm font-medium text-white bg-emerald-600 hover:bg-emerald-700 rounded-lg shadow-sm transition-colors">
                        <i data-lucide="file-text" class="w-4 h-4"></i> Tautan Artefak
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-16 md:py-24 relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-br from-emerald-500/10 via-teal-500/5 to-transparent pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-emerald-100 dark:bg-emerald-950/60 border border-emerald-300 dark:border-emerald-800 text-emerald-800 dark:text-emerald-300 text-xs font-semibold">
                        <i data-lucide="award" class="w-4 h-4"></i> Peserta Pendidikan Profesi Guru (PPG)
                    </div>
                    <h1 class="text-4xl sm:text-5xl font-extrabold tracking-tight text-slate-900 dark:text-white leading-tight">
                        Portofolio Praktik Pengalaman Lapangan (PPL)
                    </h1>
                    <p class="text-lg text-slate-600 dark:text-slate-300 leading-relaxed max-w-2xl mx-auto lg:mx-0">
                        Dokumentasi komprehensif, analisis mendalam, serta refleksi kritis pelaksanaan praktik mengajar mata pelajaran PJOK di SMPN 4 Ciamis.
                    </p>

                    <!-- Profile Meta Badges -->
                    <div class="pt-2 flex flex-wrap gap-4 justify-center lg:justify-start text-sm font-medium">
                        <div class="flex items-center gap-2 bg-white dark:bg-slate-800 px-4 py-2.5 rounded-xl shadow-sm border border-slate-200 dark:border-slate-700">
                            <i data-lucide="user" class="w-5 h-5 text-emerald-600"></i>
                            <span>Bayu Rahayu, S.Pd.</span>
                        </div>
                        <div class="flex items-center gap-2 bg-white dark:bg-slate-800 px-4 py-2.5 rounded-xl shadow-sm border border-slate-200 dark:border-slate-700">
                            <i data-lucide="id-card" class="w-5 h-5 text-emerald-600"></i>
                            <span>NIM: 2186250029</span>
                        </div>
                        <div class="flex items-center gap-2 bg-white dark:bg-slate-800 px-4 py-2.5 rounded-xl shadow-sm border border-slate-200 dark:border-slate-700">
                            <i data-lucide="map-pin" class="w-5 h-5 text-emerald-600"></i>
                            <span>SMPN 4 Ciamis</span>
                        </div>
                        <div class="flex items-center gap-2 bg-white dark:bg-slate-800 px-4 py-2.5 rounded-xl shadow-sm border border-slate-200 dark:border-slate-700">
                            <i data-lucide="graduation-cap" class="w-5 h-5 text-emerald-600"></i>
                            <span>Universitas Galuh Ciamis</span>
                        </div>
                    </div>
                </div>

                <!-- Hero Graphic / Summary Card -->
                <div class="lg:col-span-5">
                    <div class="bg-white dark:bg-slate-800 rounded-2xl p-6 sm:p-8 shadow-xl border border-slate-200/80 dark:border-slate-700 relative">
                        <div class="absolute -top-3 -right-3 w-12 h-12 bg-emerald-500 rounded-2xl rotate-12 flex items-center justify-center text-white shadow-lg">
                            <i data-lucide="activity" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white mb-4 flex items-center gap-2">
                            <i data-lucide="target" class="w-5 h-5 text-emerald-600"></i> Fokus Utama Pembelajaran
                        </h3>
                        <div class="space-y-4 text-sm text-slate-600 dark:text-slate-300">
                            <div class="p-3.5 rounded-xl bg-slate-50 dark:bg-slate-900/50 border border-slate-100 dark:border-slate-800">
                                <span class="font-semibold text-slate-900 dark:text-white block mb-1">Pendekatan Deep Learning</span>
                                Mindful, Meaningful, dan Joyful Learning dalam pembelajaran PJOK.
                            </div>
                            <div class="p-3.5 rounded-xl bg-slate-50 dark:bg-slate-900/50 border border-slate-100 dark:border-slate-800">
                                <span class="font-semibold text-slate-900 dark:text-white block mb-1">Diferensiasi (TaRL)</span>
                                Pengelompokan siswa berdasarkan asesmen diagnostik motorik (Pemula, Menengah, Mahir).
                            </div>
                            <div class="p-3.5 rounded-xl bg-slate-50 dark:bg-slate-900/50 border border-slate-100 dark:border-slate-800">
                                <span class="font-semibold text-slate-900 dark:text-white block mb-1">Kearifan Lokal Sunda (CRT)</span>
                                Integrasi nilai *Silih Asah, Silih Asih, Silih Asuh* dalam dinamika kelompok.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Profil Saya Section -->
    <section id="profil" class="py-16 bg-white dark:bg-slate-800/50 border-y border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mx-auto text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-900 dark:text-white">Profil Saya</h2>
                <div class="w-16 h-1 bg-emerald-500 mx-auto mt-3 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-12 gap-8 items-start">
                <!-- Bio Cards -->
                <div class="md:col-span-8 bg-slate-50 dark:bg-slate-800 rounded-2xl p-6 sm:p-8 border border-slate-200 dark:border-slate-700 space-y-4">
                    <p class="text-base leading-relaxed text-slate-700 dark:text-slate-300">
                        <span class="font-semibold text-slate-900 dark:text-white">Assalamualaikum Warahmatullahi Wabarakatuh</span>
                    </p>
                    <p class="text-base leading-relaxed text-slate-700 dark:text-slate-300">
                        Perkenalkan nama Saya <strong>Bayu Rahayu</strong>, berdomisili di Garut Selatan, tepatnya Bungbulang. Saya lahir dari keluarga sederhana yang memiliki kepercayaan teguh bahwa setiap anak harus memperoleh pendidikan yang baik. Di usia yang menginjak 29 tahun ini, saya telah merasakan begitu banyak manfaat dari jalur pendidikan yang telah saya tempuh.
                    </p>
                    <p class="text-base leading-relaxed text-slate-700 dark:text-slate-300">
                        Sebagai seorang yang menggemari berbagai jenis olahraga—terutama <strong>Sepak Bola</strong>—saya memiliki ketertarikan mendalam dalam mendidik dan membina fisik serta karakter generasi muda melalui Olahraga dan Kesehatan.
                    </p>
                    <div class="p-4 rounded-xl bg-emerald-50 dark:bg-emerald-950/40 border border-emerald-200 dark:border-emerald-800/50 mt-4">
                        <h4 class="font-bold text-emerald-900 dark:text-emerald-300 mb-1 flex items-center gap-2">
                            <i data-lucide="heart-handshake" class="w-5 h-5 text-emerald-600"></i> Visi & Tujuan Guru Profesional
                        </h4>
                        <p class="text-sm text-emerald-800 dark:text-emerald-300/90 leading-relaxed">
                            Tujuan utama saya mengikuti Pendidikan Profesi Guru (PPG) adalah untuk memperoleh kualifikasi dan gelar resmi sebagai Guru Profesional. Harapan terbesar saya adalah dapat berkontribusi secara nyata dalam meningkatkan kualitas pendidikan di Indonesia, dimulai langsung dari interaksi dan pembelajaran inovatif di dalam kelas yang saya ajar.
                        </p>
                    </div>
                </div>

                <!-- Personal Quick Info -->
                <div class="md:col-span-4 space-y-4">
                    <div class="bg-slate-50 dark:bg-slate-800 rounded-2xl p-6 border border-slate-200 dark:border-slate-700">
                        <h3 class="font-bold text-slate-900 dark:text-white text-lg mb-4 flex items-center gap-2">
                            <i data-lucide="info" class="w-5 h-5 text-emerald-600"></i> Informasi Diri
                        </h3>
                        <dl class="space-y-3 text-sm">
                            <div class="flex justify-between py-1.5 border-b border-slate-200 dark:border-slate-700">
                                <dt class="text-slate-500 dark:text-slate-400">Usia</dt>
                                <dd class="font-semibold text-slate-800 dark:text-slate-200">29 Tahun</dd>
                            </div>
                            <div class="flex justify-between py-1.5 border-b border-slate-200 dark:border-slate-700">
                                <dt class="text-slate-500 dark:text-slate-400">Domisili Asli</dt>
                                <dd class="font-semibold text-slate-800 dark:text-slate-200">Bungbulang, Garut</dd>
                            </div>
                            <div class="flex justify-between py-1.5 border-b border-slate-200 dark:border-slate-700">
                                <dt class="text-slate-500 dark:text-slate-400">Hobi Utama</dt>
                                <dd class="font-semibold text-slate-800 dark:text-slate-200">Sepak Bola & Olahraga</dd>
                            </div>
                            <div class="flex justify-between py-1.5 border-b border-slate-200 dark:border-slate-700">
                                <dt class="text-slate-500 dark:text-slate-400">Lokasi PPL</dt>
                                <dd class="font-semibold text-slate-800 dark:text-slate-200">SMPN 4 Ciamis</dd>
                            </div>
                            <div class="flex justify-between py-1.5">
                                <dt class="text-slate-500 dark:text-slate-400">Kampus PPG</dt>
                                <dd class="font-semibold text-slate-800 dark:text-slate-200">Univ. Galuh Ciamis</dd>
                            </div>
                        </dl>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Riwayat Pendidikan Timeline Section -->
    <section id="pendidikan" class="py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mx-auto text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-900 dark:text-white">Riwayat Pendidikan</h2>
                <p class="text-slate-600 dark:text-slate-400 mt-2">Jejak langkah formal pendidikan yang telah ditempuh</p>
                <div class="w-16 h-1 bg-emerald-500 mx-auto mt-3 rounded-full"></div>
            </div>

            <div class="max-w-4xl mx-auto relative before:absolute before:inset-0 before:left-1/2 before:-ml-0.5 before:w-0.5 before:bg-slate-200 dark:before:bg-slate-700 hidden md:block">
                <!-- Timeline Desktop Item 1 -->
                <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group mb-8">
                    <div class="flex items-center justify-center w-10 h-10 rounded-full border-4 border-white dark:border-slate-900 bg-emerald-600 text-white font-bold shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                        1
                    </div>
                    <div class="w-[calc(50%-2rem)] bg-white dark:bg-slate-800 p-5 rounded-2xl border border-slate-200 dark:border-slate-700 shadow-sm">
                        <span class="text-xs font-semibold text-emerald-600 dark:text-emerald-400">Pendidikan Dasar</span>
                        <h4 class="font-bold text-slate-900 dark:text-white text-lg">SD Hanjuang 1</h4>
                        <p class="text-sm text-slate-500 dark:text-slate-400">Bungbulang, Garut</p>
                    </div>
                </div>

                <!-- Timeline Desktop Item 2 -->
                <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group mb-8">
                    <div class="flex items-center justify-center w-10 h-10 rounded-full border-4 border-white dark:border-slate-900 bg-emerald-600 text-white font-bold shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                        2
                    </div>
                    <div class="w-[calc(50%-2rem)] bg-white dark:bg-slate-800 p-5 rounded-2xl border border-slate-200 dark:border-slate-700 shadow-sm">
                        <span class="text-xs font-semibold text-emerald-600 dark:text-emerald-400">Pendidikan Menengah Pertama</span>
                        <h4 class="font-bold text-slate-900 dark:text-white text-lg">SMPN 1 Bungbulang & SMP Puspita Bangsa</h4>
                        <p class="text-sm text-slate-500 dark:text-slate-400">Garut</p>
                    </div>
                </div>

                <!-- Timeline Desktop Item 3 -->
                <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group mb-8">
                    <div class="flex items-center justify-center w-10 h-10 rounded-full border-4 border-white dark:border-slate-900 bg-emerald-600 text-white font-bold shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                        3
                    </div>
                    <div class="w-[calc(50%-2rem)] bg-white dark:bg-slate-800 p-5 rounded-2xl border border-slate-200 dark:border-slate-700 shadow-sm">
                        <span class="text-xs font-semibold text-emerald-600 dark:text-emerald-400">Pendidikan Menengah Atas</span>
                        <h4 class="font-bold text-slate-900 dark:text-white text-lg">SMAN 7 Garut</h4>
                        <p class="text-sm text-slate-500 dark:text-slate-400">Garut</p>
                    </div>
                </div>

                <!-- Timeline Desktop Item 4 -->
                <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group mb-8">
                    <div class="flex items-center justify-center w-10 h-10 rounded-full border-4 border-white dark:border-slate-900 bg-emerald-600 text-white font-bold shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                        4
                    </div>
                    <div class="w-[calc(50%-2rem)] bg-white dark:bg-slate-800 p-5 rounded-2xl border border-slate-200 dark:border-slate-700 shadow-sm">
                        <span class="text-xs font-semibold text-emerald-600 dark:text-emerald-400">Sarjana (S1)</span>
                        <h4 class="font-bold text-slate-900 dark:text-white text-lg">Universitas Pendidikan Indonesia (UPI)</h4>
                        <p class="text-sm text-slate-600 dark:text-slate-300 font-medium mt-1">Jurusan Kepelatihan Olahraga</p>
                        <p class="text-xs text-slate-500 dark:text-slate-400">Fakultas Pendidikan Olahraga dan Kesehatan (FPOK)</p>
                    </div>
                </div>

                <!-- Timeline Desktop Item 5 -->
                <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
                    <div class="flex items-center justify-center w-10 h-10 rounded-full border-4 border-white dark:border-slate-900 bg-teal-500 text-white font-bold shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                        5
                    </div>
                    <div class="w-[calc(50%-2rem)] bg-emerald-50 dark:bg-emerald-950/40 p-5 rounded-2xl border border-emerald-300 dark:border-emerald-700 shadow-sm">
                        <span class="text-xs font-semibold text-emerald-700 dark:text-emerald-300">Pendidikan Profesi</span>
                        <h4 class="font-bold text-slate-900 dark:text-white text-lg">Universitas Galuh Ciamis</h4>
                        <p class="text-sm text-emerald-800 dark:text-emerald-300 font-medium">Program Pendidikan Profesi Guru (PPG)</p>
                        <p class="text-xs text-slate-500 dark:text-slate-400 mt-1">Status: Sedang Menempuh PPL di SMPN 4 Ciamis</p>
                    </div>
                </div>
            </div>

            <!-- Mobile Timeline View -->
            <div class="space-y-4 md:hidden">
                <div class="bg-white dark:bg-slate-800 p-5 rounded-xl border border-slate-200 dark:border-slate-700">
                    <span class="text-xs font-semibold text-emerald-600">SD</span>
                    <h4 class="font-bold text-slate-900 dark:text-white">SD Hanjuang 1</h4>
                </div>
                <div class="bg-white dark:bg-slate-800 p-5 rounded-xl border border-slate-200 dark:border-slate-700">
                    <span class="text-xs font-semibold text-emerald-600">SMP</span>
                    <h4 class="font-bold text-slate-900 dark:text-white">SMPN 1 Bungbulang & SMP Puspita Bangsa</h4>
                </div>
                <div class="bg-white dark:bg-slate-800 p-5 rounded-xl border border-slate-200 dark:border-slate-700">
                    <span class="text-xs font-semibold text-emerald-600">SMA</span>
                    <h4 class="font-bold text-slate-900 dark:text-white">SMAN 7 Garut</h4>
                </div>
                <div class="bg-white dark:bg-slate-800 p-5 rounded-xl border border-slate-200 dark:border-slate-700">
                    <span class="text-xs font-semibold text-emerald-600">S1 Sarjana</span>
                    <h4 class="font-bold text-slate-900 dark:text-white">Universitas Pendidikan Indonesia (UPI)</h4>
                    <p class="text-sm text-slate-600 dark:text-slate-300">Kepelatihan Olahraga (FPOK)</p>
                </div>
                <div class="bg-emerald-50 dark:bg-emerald-950/40 p-5 rounded-xl border border-emerald-300 dark:border-emerald-700">
                    <span class="text-xs font-semibold text-emerald-700 dark:text-emerald-300">Profesi</span>
                    <h4 class="font-bold text-slate-900 dark:text-white">Universitas Galuh Ciamis (PPG)</h4>
                </div>
            </div>
        </div>
    </section>

    <!-- Kedalaman Analisis Artefak Section -->
    <section id="analisis" class="py-16 bg-white dark:bg-slate-800/50 border-y border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mx-auto text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-900 dark:text-white">Kedalaman Analisis Artefak</h2>
                <p class="text-slate-600 dark:text-slate-400 mt-2">Evaluasi komprehensif 5 komponen utama pelaksanaan PPL</p>
                <div class="w-16 h-1 bg-emerald-500 mx-auto mt-3 rounded-full"></div>
            </div>

            <!-- Tab Buttons / Interactive Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

                <!-- Analisis 1 -->
                <div class="bg-slate-50 dark:bg-slate-800 rounded-2xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition-shadow">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-emerald-100 dark:bg-emerald-900/50 text-emerald-600 dark:text-emerald-400 flex items-center justify-center mb-4">
                            <i data-lucide="book-open" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 dark:text-white mb-3">1. Analisis Produk Rancangan Pembelajaran</h3>
                        <ul class="space-y-2 text-sm text-slate-600 dark:text-slate-300 mb-4">
                            <li><strong class="text-slate-800 dark:text-slate-200">Pendekatan:</strong> Kurikulum Merdeka (Deep Learning: <i>Mindful, Meaningful, Joyful Learning</i>).</li>
                            <li><strong class="text-slate-800 dark:text-slate-200">TaRL:</strong> Pengelompokan 3 zona motorik (Pemula, Menengah, Mahir).</li>
                            <li><strong class="text-slate-800 dark:text-slate-200">CRT:</strong> Kearifan Sunda *Silih Asah, Silih Asih, Silih Asuh* & ritme kendang/tarian tradisional Sunda.</li>
                        </ul>
                    </div>
                    <div class="pt-3 border-t border-slate-200 dark:border-slate-700 text-xs text-amber-700 dark:text-amber-400 font-medium">
                        ⚠️ <strong>Evaluasi:</strong> Butuh manajemen durasi tes awal motorik agar tidak menyita jam pelajaran inti.
                    </div>
                </div>

                <!-- Analisis 2 -->
                <div class="bg-slate-50 dark:bg-slate-800 rounded-2xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition-shadow">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-blue-100 dark:bg-blue-900/50 text-blue-600 dark:text-blue-400 flex items-center justify-center mb-4">
                            <i data-lucide="dribbble" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 dark:text-white mb-3">2. Analisis Materi Pembelajaran</h3>
                        <ul class="space-y-2 text-sm text-slate-600 dark:text-slate-300 mb-4">
                            <li><strong class="text-slate-800 dark:text-slate-200">Materi Utama:</strong> Bola Basket (Dribbling, Passing, Catching).</li>
                            <li><strong class="text-slate-800 dark:text-slate-200">Lintas Disiplin:</strong> Fisika (Aksi-Reaksi/Gaya Dorong), Matematika (Sudut Elevasi & Poin), Bahasa Indonesia (Komunikasi Efektif).</li>
                        </ul>
                    </div>
                    <div class="pt-3 border-t border-slate-200 dark:border-slate-700 text-xs text-rose-700 dark:text-rose-400 font-medium">
                        🚨 <strong>Kendala:</strong> Minimnya jumlah bola basket fisik yang tersedia di sekolah.
                    </div>
                </div>

                <!-- Analisis 3 -->
                <div class="bg-slate-50 dark:bg-slate-800 rounded-2xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition-shadow">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-purple-100 dark:bg-purple-900/50 text-purple-600 dark:text-purple-400 flex items-center justify-center mb-4">
                            <i data-lucide="laptop" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 dark:text-white mb-3">3. Analisis Media Pembelajaran</h3>
                        <ul class="space-y-2 text-sm text-slate-600 dark:text-slate-300 mb-4">
                            <li><strong class="text-slate-800 dark:text-slate-200">Digital:</strong> Video YouTube teknik dasar, PPT, Google Forms & Quizizz.</li>
                            <li><strong class="text-slate-800 dark:text-slate-200">Fisik & Modifikasi:</strong> Marker cone, bola busa/karet untuk tingkat pemula.</li>
                        </ul>
                    </div>
                    <div class="pt-3 border-t border-slate-200 dark:border-slate-700 text-xs text-amber-700 dark:text-amber-400 font-medium">
                        ⚠️ <strong>Evaluasi:</strong> Inovasi digital baik, namun rasio bola per siswa belum seimbang.
                    </div>
                </div>

                <!-- Analisis 4 -->
                <div class="bg-slate-50 dark:bg-slate-800 rounded-2xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition-shadow lg:col-span-2">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-orange-100 dark:bg-orange-900/50 text-orange-600 dark:text-orange-400 flex items-center justify-center mb-4">
                            <i data-lucide="video" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 dark:text-white mb-3">4. Analisis Pelaksanaan Praktik Mengajar & Feedback</h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm">
                            <div class="p-3.5 bg-white dark:bg-slate-900 rounded-xl border border-slate-200 dark:border-slate-700">
                                <span class="font-semibold text-slate-900 dark:text-white block mb-1">Dinamika Siswa</span>
                                Siswa sangat antusias dalam Game-Based Learning, namun ada keluhan waktu tunggu/antrean memegang bola.
                            </div>
                            <div class="p-3.5 bg-white dark:bg-slate-900 rounded-xl border border-slate-200 dark:border-slate-700">
                                <span class="font-semibold text-slate-900 dark:text-white block mb-1">Umpan Balik Guru Pamong</span>
                                <span class="text-xs text-emerald-600 font-medium">Bpk. Adang, S.Pd.</span>
                                <ul class="list-disc list-inside text-xs mt-1 space-y-1">
                                    <li>Instruksi perlu lebih singkat & jelas.</li>
                                    <li>Optimalkan manajemen alokasi waktu kelompok.</li>
                                    <li>Perbanyak variasi Joyful Game.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Analisis 5 -->
                <div class="bg-slate-50 dark:bg-slate-800 rounded-2xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between hover:shadow-lg transition-shadow">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-teal-100 dark:bg-teal-900/50 text-teal-600 dark:text-teal-400 flex items-center justify-center mb-4">
                            <i data-lucide="users" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 dark:text-white mb-3">5. Analisis Kegiatan Non-Mengajar</h3>
                        <ul class="space-y-2 text-sm text-slate-600 dark:text-slate-300">
                            <li><strong class="text-slate-800 dark:text-slate-200">Mitra Lingkungan:</strong> Koordinasi penggunaan aula serbaguna & tim ekskul olahraga.</li>
                            <li><strong class="text-slate-800 dark:text-slate-200">Budaya Sekolah:</strong> Pembudayaan nilai Sunda menciptakan lingkungan sosial ramah, mencegah perundungan, dan menumbuhkan empati.</li>
                        </ul>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Refleksi Diri Section -->
    <section id="refleksi" class="py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mx-auto text-center mb-12">
                <h2 class="text-3xl font-bold text-slate-900 dark:text-white">Refleksi Diri</h2>
                <p class="text-slate-600 dark:text-slate-400 mt-2">Evaluasi mandiri atas kelebihan, tantangan, dan rencana tindak lanjut</p>
                <div class="w-16 h-1 bg-emerald-500 mx-auto mt-3 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Kekuatan -->
                <div class="bg-emerald-50/50 dark:bg-emerald-950/20 rounded-2xl p-6 border border-emerald-200 dark:border-emerald-800/60">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="p-2.5 bg-emerald-600 text-white rounded-xl">
                            <i data-lucide="check-circle" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white">Hal Positif (Kekuatan)</h3>
                    </div>
                    <ul class="space-y-3 text-sm text-slate-700 dark:text-slate-300">
                        <li class="flex items-start gap-2">
                            <i data-lucide="sparkles" class="w-4 h-4 text-emerald-600 shrink-0 mt-1"></i>
                            <span><strong>Inovasi Pembelajaran:</strong> Penerapan Deep Learning & diferensiasi TaRL zona latihan motorik.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i data-lucide="heart" class="w-4 h-4 text-emerald-600 shrink-0 mt-1"></i>
                            <span><strong>Penguatan Karakter:</strong> Inklusi kearifan Sunda mencegah perundungan di sekolah.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i data-lucide="smartphone" class="w-4 h-4 text-emerald-600 shrink-0 mt-1"></i>
                            <span><strong>Pemanfaatan Teknologi:</strong> Video YouTube & kuis interaktif meningkatkan keterlibatan siswa.</span>
                        </li>
                    </ul>
                </div>

                <!-- Kelemahan / Tantangan -->
                <div class="bg-rose-50/50 dark:bg-rose-950/20 rounded-2xl p-6 border border-rose-200 dark:border-rose-800/60">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="p-2.5 bg-rose-600 text-white rounded-xl">
                            <i data-lucide="alert-triangle" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white">Tantangan (Kelemahan)</h3>
                    </div>
                    <ul class="space-y-3 text-sm text-slate-700 dark:text-slate-300">
                        <li class="flex items-start gap-2">
                            <i data-lucide="box" class="w-4 h-4 text-rose-600 shrink-0 mt-1"></i>
                            <span><strong>Fasilitas & Alat:</strong> Keterbatasan jumlah bola basket dan penggunaan ruang lapangan terbatas.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i data-lucide="clock" class="w-4 h-4 text-rose-600 shrink-0 mt-1"></i>
                            <span><strong>Manajemen Waktu:</strong> Asesmen diagnostik awal terlalu memakan durasi jam inti.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i data-lucide="message-square" class="w-4 h-4 text-rose-600 shrink-0 mt-1"></i>
                            <span><strong>Efisiensi Instruksi:</strong> Penjelasan verbal di lapangan terkadang terlalu panjang.</span>
                        </li>
                    </ul>
                </div>

                <!-- Rencana Tindak Lanjut -->
                <div class="bg-blue-50/50 dark:bg-blue-950/20 rounded-2xl p-6 border border-blue-200 dark:border-blue-800/60">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="p-2.5 bg-blue-600 text-white rounded-xl">
                            <i data-lucide="arrow-right-circle" class="w-6 h-6"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 dark:text-white">Rencana Perbaikan</h3>
                    </div>
                    <ul class="space-y-3 text-sm text-slate-700 dark:text-slate-300">
                        <li class="flex items-start gap-2">
                            <i data-lucide="wrench" class="w-4 h-4 text-blue-600 shrink-0 mt-1"></i>
                            <span><strong>Modifikasi Pembelajaran:</strong> Menambah bola modifikasi (karet/busa) & sirkulasi kelompok yang rapat.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i data-lucide="zap" class="w-4 h-4 text-blue-600 shrink-0 mt-1"></i>
                            <span><strong>Penyederhanaan Instruksi:</strong> Mengutamakan peragaan/demonstrasi visual yang padat & langsung.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i data-lucide="activity" class="w-4 h-4 text-blue-600 shrink-0 mt-1"></i>
                            <span><strong>Optimasi Asesmen:</strong> Mengintegrasikan asesmen diagnostik ke dalam pemanasan (warming-up).</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Bukti Artefak Link Section -->
    <section id="artefak" class="py-16 bg-gradient-to-br from-emerald-900 to-teal-900 text-white">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-6">
            <div class="inline-flex p-3 bg-white/10 rounded-2xl backdrop-blur-md">
                <i data-lucide="folder-open" class="w-10 h-10 text-emerald-400"></i>
            </div>
            <h2 class="text-3xl font-extrabold">Dokumen & Bukti Artefak PPL</h2>
            <p class="text-emerald-100 max-w-2xl mx-auto text-base">
                Akses berkas lengkap modul ajar, dokumen perencanaan, dan bukti pelaksanaan PPL yang tersimpan pada repositori Google Docs resmi.
            </p>
            <div class="pt-4">
                <a href="https://docs.google.com/document/d/1vtn9qeoWYdU0cTQoqiNPNmjWs1I3sowp/edit?usp=sharing&ouid=108765640719780219777&rtpof=true&sd=true" 
                   target="_blank" 
                   rel="noopener noreferrer"
                   class="inline-flex items-center gap-3 px-8 py-4 bg-emerald-500 hover:bg-emerald-400 text-slate-900 font-bold text-lg rounded-xl shadow-lg transition-transform hover:-translate-y-1">
                    <i data-lucide="external-link" class="w-6 h-6"></i> Buka Dokumen Artefak (Google Docs)
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-slate-900 text-slate-400 text-sm border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row justify-between items-center gap-4">
            <div>
                <p>© Portofolio PPL PPG - Bayu Rahayu, S.Pd. | Universitas Galuh Ciamis</p>
            </div>
            <div class="flex gap-4 text-xs">
                <span>SMPN 4 Ciamis</span>
                <span>•</span>
                <span>PJOK</span>
                <span>•</span>
                <span>NIM: 2186250029</span>
            </div>
        </div>
    </footer>

    <!-- Scripts -->
    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Dark Mode Toggle Logic
        const themeToggleBtn = document.getElementById('themeToggle');
        themeToggleBtn.addEventListener('click', () => {
            document.documentElement.classList.toggle('dark');
        });
    </script>
</body>
</html>
