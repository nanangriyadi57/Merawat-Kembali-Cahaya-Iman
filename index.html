<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jangan Biarkan Redup: Merawat Kembali Cahaya Iman</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lora:wght@400;500;600&family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <!-- Chosen Palette: Serene Dawn -->
    <!-- Application Structure Plan: Aplikasi ini dirancang dengan metafora visual "Cahaya Iman" sebagai pusatnya. Di bagian atas, terdapat sebuah elemen visual yang merepresentasikan cahaya iman, yang awalnya tampak redup. Di bawahnya, terdapat lima "langkah perawatan" yang disajikan sebagai kartu interaktif. Ketika pengguna mengklik salah satu kartu, "cahaya" di atas akan menjadi lebih terang dan stabil, memberikan umpan balik visual bahwa tindakan tersebut "merawat" iman. Teks penjelasan untuk langkah yang dipilih kemudian akan muncul dengan mulus di area konten di bawahnya. Struktur ini mengubah dakwah linear menjadi sebuah pengalaman interaktif 'sebab-akibat', di mana pengguna secara aktif berpartisipasi dalam "menyalakan" kembali cahaya iman, sehingga pesan lebih meresap dan mudah diingat. -->
    <!-- Visualization & Content Choices: 
        - Cahaya Iman (Visual Utama): Tujuan -> Merepresentasikan inti metafora dakwah. Presentasi -> Div HTML dengan animasi CSS (radial-gradient, box-shadow, keyframes) untuk menciptakan efek cahaya yang berdenyut lembut. Interaksi -> Menjadi lebih terang dan warnanya lebih hangat saat pengguna memilih salah satu langkah perawatan. Justifikasi -> Menciptakan jangkar visual yang kuat dan emosional untuk seluruh konten.
        - Lima Langkah Perawatan (Navigasi): Tujuan -> Menyajikan poin-poin utama dakwah sebagai tindakan yang bisa dipilih. Presentasi -> Kartu-kartu interaktif (div HTML dengan Tailwind CSS) yang masing-masing memiliki ikon Unicode dan judul. Interaksi -> Event listener 'click' pada setiap kartu memicu fungsi JavaScript untuk memperbarui visual cahaya dan menampilkan konten teks yang relevan. Justifikasi -> Navigasi yang jelas, intuitif, dan menarik secara visual.
        - Konten Penjelasan: Tujuan -> Menyampaikan detail setiap langkah dari teks sumber. Presentasi -> Area konten khusus (div HTML) yang isinya diperbarui secara dinamis. Interaksi -> Teks muncul dengan transisi 'fade-in' untuk pengalaman yang mulus. Justifikasi -> Memisahkan detail dari navigasi utama, menjaga antarmuka tetap bersih dan fokus.
        - Grafik/Chart (Chart.js): Tidak digunakan. Justifikasi -> Teks sumber bersifat kualitatif, naratif, dan konseptual. Tidak ada data kuantitatif yang bisa direpresentasikan dalam bentuk grafik tanpa mengurangi atau mendistorsi pesan dakwah yang asli. Menggunakan grafik akan terasa dipaksakan dan tidak relevan.
    -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F5F2;
        }
        h1, h2, h3 {
            font-family: 'Lora', serif;
        }
        .cahaya-iman {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255,223,186,0.5) 0%, rgba(248,245,242,0) 70%);
            box-shadow: 0 0 20px 5px rgba(255,223,186,0.3);
            transition: all 0.7s ease-in-out;
            animation: pulse-dim 5s infinite ease-in-out;
        }
        .cahaya-iman.terang {
            transform: scale(1.1);
            background: radial-gradient(circle, rgba(255,204,153,0.9) 0%, rgba(248,245,242,0) 70%);
            box-shadow: 0 0 40px 20px rgba(255,204,153,0.6);
            animation: pulse-bright 4s infinite ease-in-out;
        }
        @keyframes pulse-dim {
            0%, 100% { box-shadow: 0 0 20px 5px rgba(255,223,186,0.3); }
            50% { box-shadow: 0 0 30px 10px rgba(255,223,186,0.4); }
        }
        @keyframes pulse-bright {
            0%, 100% { box-shadow: 0 0 40px 20px rgba(255,204,153,0.6); transform: scale(1.1); }
            50% { box-shadow: 0 0 55px 25px rgba(255,204,153,0.7); transform: scale(1.15); }
        }
        .content-area {
            transition: opacity 0.7s ease-in-out;
            opacity: 0;
        }
        .content-area.visible {
            opacity: 1;
        }
        .card-langkah {
            transition: all 0.3s ease-in-out;
            border: 2px solid transparent;
        }
        .card-langkah:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0,0,0,0.05), 0 4px 6px -2px rgba(0,0,0,0.05);
            border-color: #D1C4B0;
        }
        .card-langkah.active {
            transform: translateY(-5px) scale(1.03);
            box-shadow: 0 10px 20px -5px rgba(160, 128, 96, 0.2);
            border-color: #A08060;
            background-color: #FFFBF5;
        }
    </style>
</head>
<body class="bg-[#F8F5F2] text-[#5C4B3A]">
    <div class="container mx-auto px-4 py-8 md:py-12 max-w-4xl">
        
        <header class="text-center mb-10">
            <h1 class="text-4xl md:text-5xl font-bold text-[#8C6D4F] mb-2">Jangan Biarkan Redup</h1>
            <p class="text-lg md:text-xl text-[#A08060]">Merawat Kembali Cahaya Iman di Dalam Hati</p>
        </header>

        <main>
            <section id="interactive-zone" class="mb-12">
                <div class="flex justify-center items-center mb-10 h-48">
                    <div id="cahaya-iman-visual" class="cahaya-iman"></div>
                </div>

                <div class="text-center mb-8">
                     <h2 class="text-2xl font-semibold text-[#8C6D4F]">Lima Langkah Merawat Cahaya Iman</h2>
                     <p class="text-md text-[#A08060] mt-1">Pilih salah satu langkah di bawah untuk menyalakan kembali cahayanya.</p>
                </div>

                <div id="controls-container" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-4 md:gap-6">
                </div>
            </section>

            <section id="content-display-wrapper" class="bg-white/50 rounded-2xl p-6 md:p-8 min-h-[300px] shadow-inner backdrop-blur-sm">
                <div id="content-area" class="content-area">
                </div>
            </section>
             <footer class="text-center mt-12">
                <p class="text-sm text-[#A08060]">&copy; 2025 | Sebuah Visualisasi Dakwah Interaktif</p>
            </footer>
        </main>
    </div>

    <script>
        const dakwahData = [
            {
                id: 'alquran',
                title: "Kembali ke Al-Qur'an",
                icon: '📖',
                content: `
                    <h3 class="text-2xl font-semibold text-[#8C6D4F] mb-4">Langkah Pertama: Kembali ke Sumber Cahaya (Al-Qur'an)</h3>
                    <p class="mb-4 text-base leading-relaxed">Cahaya iman itu bersumber dari cahaya ilahi, yaitu Al-Qur'an. Jika kita merasa hati kita mulai gelap, tanyakan pada diri sendiri: "Kapan terakhir kali aku membuka dan merenungi Al-Qur'an?" Seringkali, saat iman melemah, Al-Qur'an adalah yang pertama kita jauhkan.</p>
                    <p class="mb-4 text-base leading-relaxed">Maka, paksa diri kita. Mulailah lagi, walau hanya satu ayat sehari. Baca artinya, renungi maknanya. Biarkan firman-firman Allah itu kembali menyirami hati kita yang kering dan menerangi jiwa kita yang mulai redup.</p>
                    <blockquote class="border-l-4 border-[#D1C4B0] pl-4 italic text-[#8C6D4F] my-6">
                        "Sungguh, telah datang kepadamu cahaya dari Allah, dan Kitab yang menjelaskan... Dengan Kitab itulah Allah menunjuki orang-orang... dari gelap gulita kepada cahaya yang terang benderang."
                        <cite class="block text-sm mt-2 not-italic">— QS. Al-Ma'idah: 15-16</cite>
                    </blockquote>
                `
            },
            {
                id: 'dzikir',
                title: "Mengisi 'Minyak' Pelita",
                icon: '🙏',
                content: `
                    <h3 class="text-2xl font-semibold text-[#8C6D4F] mb-4">Langkah Kedua: Mengisi "Minyak" Pelita dengan Dzikir dan Doa</h3>
                    <p class="mb-4 text-base leading-relaxed">Sebuah pelita tidak akan menyala tanpa minyak. Dan "minyak" bagi pelita iman kita adalah dzikrullah, mengingat Allah. Dzikir adalah amalan yang sangat ringan di lisan, namun sangat dahsyat dampaknya bagi hati.</p>
                    <p class="mb-4 text-base leading-relaxed">Saat futur melanda, saat hati gelisah, basahi lisan kita dengan istighfar. Mohon ampun atas segala kelalaian. Ucapkan tasbih, tahmid, dan tahlil. Dan jangan pernah lepaskan senjata terampuh seorang mukmin: doa. Mengadulah kepada-Nya, akui kelemahan kita.</p>
                     <blockquote class="border-l-4 border-[#D1C4B0] pl-4 italic text-center text-[#8C6D4F] my-6 p-4 bg-[#F8F5F2] rounded-r-lg">
                        <p class="text-lg font-serif">Yaa Muqallibal quluub, thabbit qalbii 'alaa diinik</p>
                        <cite class="block text-sm mt-2 not-italic">— "Wahai Dzat yang membolak-balikkan hati, teguhkanlah hatiku di atas agama-Mu."</cite>
                    </blockquote>
                `
            },
            {
                id: 'maksiat',
                title: "Melindungi dari 'Angin'",
                icon: '🛡️',
                content: `
                    <h3 class="text-2xl font-semibold text-[#8C6D4F] mb-4">Langkah Ketiga: Melindungi Pelita dari "Angin" Kemaksiatan</h3>
                    <p class="mb-4 text-base leading-relaxed">Sebuah pelita, seberapa pun terangnya, jika terus-menerus diterpa angin kencang, pasti akan padam. "Angin" itu adalah kemaksiatan. Setiap dosa yang kita lakukan, baik yang kecil maupun yang besar, adalah noda hitam yang menutupi cahaya hati kita.</p>
                    <p class="mb-4 text-base leading-relaxed">Mata yang melihat yang haram, telinga yang mendengar ghibah, lisan yang berkata dusta; semua itu adalah hembusan angin yang siap memadamkan pelita iman kita. Maka, jagalah panca indera kita. Jauhi lingkungan yang buruk, dan carilah sahabat-sahabat saleh yang akan membantu kita membangun benteng untuk melindungi cahaya iman kita.</p>
                `
            },
            {
                id: 'ilmu',
                title: "Menyalakan 'Api' Semangat",
                icon: '👥',
                content: `
                    <h3 class="text-2xl font-semibold text-[#8C6D4F] mb-4">Langkah Keempat: Menyalakan "Api" Semangat di Majelis Ilmu</h3>
                    <p class="mb-4 text-base leading-relaxed">Datang ke majelis ilmu itu ibarat kita membawa pelita kita yang redup untuk disulut kembali apinya dari obor yang menyala-nyala. Di sana, kita akan diingatkan kembali tentang akhirat dan mendengar kisah-kisah orang saleh yang membangkitkan semangat.</p>
                    <p class="mb-4 text-base leading-relaxed">Iman kita akan disegarkan kembali. Malaikat akan menaungi, dan rahmat Allah akan turun. Ini adalah cara yang sangat efektif untuk "recharge" spiritual kita dan menemukan kembali percikan semangat yang hilang.</p>
                `
            },
            {
                id: 'kematian',
                title: "Mengingat Tujuan Akhir",
                icon: '⏳',
                content: `
                    <h3 class="text-2xl font-semibold text-[#8C6D4F] mb-4">Langkah Kelima: Merenungi Tujuan Akhir Perjalanan (Mengingat Kematian)</h3>
                    <p class="mb-4 text-base leading-relaxed">Cara terampuh untuk merawat cahaya iman adalah dengan sering mengingat kematian. Mengingat bahwa perjalanan kita di dunia ini hanyalah sementara. Suatu saat, kita akan masuk ke dalam sebuah ruang yang gelap gulita, yaitu alam kubur.</p>
                    <p class="mb-4 text-base leading-relaxed">Satu-satunya penerang kita di sana bukanlah lampu, melainkan cahaya iman dan amal saleh yang kita bawa dari dunia. Renungan ini akan meluruskan kembali prioritas kita dan membuat kita bersemangat untuk kembali menata hati dan merawat cahaya iman kita.</p>
                `
            }
        ];

        const controlsContainer = document.getElementById('controls-container');
        const contentArea = document.getElementById('content-area');
        const cahayaVisual = document.getElementById('cahaya-iman-visual');

        function updateContent(selectedIndex) {
            contentArea.classList.remove('visible');

            setTimeout(() => {
                contentArea.innerHTML = dakwahData[selectedIndex].content;
                contentArea.classList.add('visible');
            }, 350);

            document.querySelectorAll('.card-langkah').forEach((card, index) => {
                if (index === selectedIndex) {
                    card.classList.add('active');
                } else {
                    card.classList.remove('active');
                }
            });

            cahayaVisual.classList.add('terang');
        }

        dakwahData.forEach((item, index) => {
            const card = document.createElement('div');
            card.className = 'card-langkah bg-white/60 rounded-xl p-4 text-center cursor-pointer flex flex-col items-center justify-center aspect-square';
            card.innerHTML = `
                <div class="text-4xl mb-2">${item.icon}</div>
                <h4 class="font-semibold text-sm md:text-base text-[#8C6D4F]">${item.title}</h4>
            `;
            card.addEventListener('click', () => updateContent(index));
            controlsContainer.appendChild(card);
        });
        
        window.addEventListener('load', () => {
            const initialContent = `
                <h3 class="text-2xl font-semibold text-[#8C6D4F] mb-4 text-center">Selamat Datang, Wahai Hamba Allah</h3>
                <p class="text-center text-base leading-relaxed mb-4">Di dalam dada kita terdapat sebuah cahaya berharga: iman. Terkadang ia terang, terkadang ia meredup. Aplikasi ini adalah ruang untuk merenung dan menemukan kembali cara merawat cahaya itu.</p>
                <p class="text-center text-base leading-relaxed">Mulailah dengan memilih salah satu dari lima langkah di atas untuk menerangi kembali hati Anda.</p>
            `;
            contentArea.innerHTML = initialContent;
            contentArea.classList.add('visible');
        });

    </script>
</body>
</html>
