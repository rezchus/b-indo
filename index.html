<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuis Interaktif Teks Argumentasi (80 Soal)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 min-h-screen flex flex-col items-center justify-center p-4">

    <!-- Container Utama -->
    <div id="app" class="w-full max-w-3xl bg-slate-800 rounded-2xl shadow-2xl p-6 sm:p-8 border border-slate-700">
        
        <!-- Halaman Sambutan / Start Screen -->
        <div id="start-screen" class="text-center space-y-6">
            <div class="inline-block p-4 bg-indigo-600/20 text-indigo-400 rounded-full mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
                </svg>
            </div>
            <h1 class="text-3xl sm:text-4xl font-bold tracking-tight text-white">Kuis Komprehensif Teks Argumentasi</h1>
            <p class="text-slate-300 max-w-xl mx-auto text-sm sm:text-base">
                Uji pemahaman Anda mengenai <span class="text-indigo-400 font-semibold">Fakta & Opini</span>, <span class="text-indigo-400 font-semibold">Struktur Teks</span>, <span class="text-indigo-400 font-semibold">Kaidah Kebahasaan</span>, serta <span class="text-indigo-400 font-semibold">Hubungan Antarparagraf</span> dalam 80 soal pilihan ganda berkualitas tinggi.
            </p>
            <div class="pt-4">
                <button onclick="startQuiz()" class="px-8 py-3.5 bg-indigo-600 hover:bg-indigo-500 text-white font-semibold rounded-xl shadow-lg transition-all duration-200 transform hover:-translate-y-0.5">
                    Mulai Kuis Sekarang
                </button>
            </div>
        </div>

        <!-- Halaman Kuis / Quiz Screen -->
        <div id="quiz-screen" class="hidden space-y-6">
            <!-- Header Progress -->
            <div class="flex justify-between items-center border-b border-slate-700 pb-4">
                <div>
                    <span id="question-number" class="text-xs font-bold uppercase tracking-wider text-indigo-400 bg-indigo-950 px-2.5 py-1 rounded-md border border-indigo-800">Soal 1 dari 80</span>
                </div>
                <div class="text-sm font-medium text-slate-400">
                    Skor: <span id="current-score" class="text-white font-bold">0</span>
                </div>
            </div>

            <!-- Pertanyaan -->
            <div class="space-y-3">
                <h2 id="question-text" class="text-lg sm:text-xl font-medium text-slate-100 leading-relaxed"></h2>
                <div id="hint-container" class="hidden text-xs italic text-amber-300 bg-amber-950/50 p-2.5 rounded-lg border border-amber-900/50">
                    <strong>Petunjuk:</strong> <span id="hint-text"></span>
                </div>
            </div>

            <!-- Opsi Jawaban -->
            <div id="options-container" class="grid grid-cols-1 gap-3">
                <!-- Opsi akan dimasukkan via JavaScript -->
            </div>

            <!-- Area Rationale & Tombol Lanjut -->
            <div id="feedback-area" class="hidden space-y-4 pt-2 border-t border-slate-700">
                <div id="rationale-box" class="p-3.5 rounded-xl text-sm leading-relaxed"></div>
                <div class="flex justify-end">
                    <button onclick="nextQuestion()" id="next-btn" class="px-6 py-2.5 bg-indigo-600 hover:bg-indigo-500 text-white font-medium rounded-xl shadow-md transition-all">
                        Soal Selanjutnya →
                    </button>
                </div>
            </div>
        </div>

        <!-- Halaman Hasil / Result Screen -->
        <div id="result-screen" class="hidden text-center space-y-6">
            <div class="inline-block p-4 bg-emerald-600/25 text-emerald-400 rounded-full mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
            </div>
            <h2 class="text-2xl sm:text-3xl font-bold text-white">Kuis Selesai!</h2>
            <p class="text-slate-300">Berikut adalah rekapitulasi hasil pengerjaan kuis teks argumentasi Anda:</p>
            
            <div class="bg-slate-900/60 border border-slate-700 rounded-2xl p-6 max-w-sm mx-auto space-y-2">
                <div class="text-sm text-slate-400">Skor Akhir Anda</div>
                <div id="final-score-display" class="text-4xl font-extrabold text-indigo-400">0 / 80</div>
                <div id="final-percentage" class="text-sm font-medium text-emerald-400">0%</div>
            </div>

            <div class="pt-4">
                <button onclick="restartQuiz()" class="px-8 py-3 bg-indigo-600 hover:bg-indigo-500 text-white font-semibold rounded-xl shadow-lg transition-all">
                    Ulangi Kuis
                </button>
            </div>
        </div>

    </div>

    <script>
        // Bank Soal Lengkap 80 Butir
        const questionsData = [
            {
                question: "Apa tujuan utama dari penulisan sebuah teks argumentasi?",
                options: [
                    "Menceritakan urutan kejadian secara kronologis.",
                    "Menyakinkan pembaca agar percaya dan terpengaruh melalui bukti dan alasan logis.",
                    "Menggambarkan suatu objek secara rinci berdasarkan panca indra.",
                    "Memberikan petunjuk langkah demi langkah melakukan sesuatu."
                ],
                correctIndex: 1,
                rationale: "Teks argumentasi bertujuan utama untuk meyakinkan pembaca dengan menyajikan bukti, data, dan alasan logis agar pembaca sepakat atau terpengaruh.",
                hint: "Fokus pada fungsi membujuk atau meyakinkan dengan bukti."
            },
            {
                question: "Manakah pernyataan di bawah ini yang merupakan ciri utama dari sebuah fakta?",
                options: [
                    "Bersifat subyektif dan bergantung pada pandangan pribadi seseorang.",
                    "Belum dapat diverifikasi kebenarannya karena baru berupa asumsi.",
                    "Dapat dibuktikan kebenarannya secara objektif serta memiliki data yang akurat.",
                    "Menggunakan kata-kata seperti 'sebaiknya', 'menurut saya', atau 'seharusnya'."
                ],
                correctIndex: 2,
                rationale: "Fakta bersifat objektif, nyata, dapat diverifikasi, dan didukung oleh data atau angka yang valid tanpa dipengaruhi opini pribadi.",
                hint: "Cari karakteristik yang bisa diverifikasi kebenarannya secara nyata."
            },
            {
                question: "Kalimat manakah yang dikategorikan sebagai kalimat opini dalam teks argumentasi?",
                options: [
                    "Berdasarkan data BPS, jumlah penduduk miskin turun 0,5% pada tahun 2025.",
                    "Gempa bumi berkekuatan 6,2 Skala Richter mengguncang wilayah pesisir barat.",
                    "Kementerian Kesehatan mencatat ada 1.200 kasus demam berdarah bulan lalu.",
                    "Pemerintah tampaknya kurang serius menangani masalah krisis iklim global saat ini."
                ],
                correctIndex: 3,
                rationale: "Penggunaan kata 'tampaknya' dan penilaian subjektif 'kurang serius' menunjukkan bahwa pernyataan tersebut adalah sebuah pendapat (opini).",
                hint: "Perhatikan kata penanda yang menunjukkan subjektivitas atau dugaan."
            },
            {
                question: "Dalam struktur teks argumentasi, bagian pendahuluan umumnya berisi...",
                options: [
                    "Rangkuman menyeluruh dari semua argumen yang telah disampaikan.",
                    "Pernyataan pendapat (thesis statement) yang menjadi landasan permasalahan.",
                    "Uraian data pendukung yang sangat mendalam dan terperinci.",
                    "Penutup berupa imbauan tegas kepada para pembaca."
                ],
                correctIndex: 1,
                rationale: "Bagian pendahuluan teks argumentasi berfungsi memperkenalkan isu sekaligus memuat tesis atau pernyataan pendapat penulis.",
                hint: "Pikirkan apa yang pertama kali diletakkan untuk menarik perhatian sekaligus mengenalkan topik."
            },
            {
                question: "Bagian tubuh argumen (argumen pendukung) dalam teks argumentasi berfungsi untuk...",
                options: [
                    "Menyajikan serangkaian fakta, alasan logis, dan bukti untuk memperkuat tesis.",
                    "Menyampaikan cerita fiktif yang menarik sebagai pengantar pembaca.",
                    "Memberikan kesimpulan akhir tanpa perlu menyertakan bukti lagi.",
                    "Membuat alur cerita menjadi mengalir layaknya novel."
                ],
                correctIndex: 0,
                rationale: "Tubuh argumen adalah inti dari teks argumentasi di mana penulis membeberkan bukti-bukti faktual dan penalaran logis untuk menguji tesis.",
                hint: "Bagian ini berisi deretan alasan dan data."
            },
            {
                question: "Bagian akhir atau penutup dalam teks argumentasi sering disebut juga sebagai...",
                options: [
                    "Klimaks cerita",
                    "Pernyataan ulang pendapat (simpulan)",
                    "Abstraksi masalah",
                    "Orientasi awal"
                ],
                correctIndex: 1,
                rationale: "Bagian penutup teks argumentasi umumnya berisi penegasan ulang atau simpulan dari seluruh argumen yang telah dijabarkan sebelumnya.",
                hint: "Bagian ini menyimpulkan keseluruhan esai argumen."
            },
            {
                question: "Manakah pola pengembangan paragraf argumentasi yang membandingkan dua hal untuk menarik kesimpulan?",
                options: [
                    "Pola analogi",
                    "Pola sebab-akibat (kausalitas)",
                    "Pola akibat-sebab",
                    "Pola definisi luas"
                ],
                correctIndex: 0,
                rationale: "Pola analogi membandingkan dua objek atau situasi yang memiliki kesamaan untuk menarik kesimpulan yang logis.",
                hint: "Perhatikan istilah perbandingan dalam penarikan kesimpulan."
            },
            {
                question: "Perhatikan kalimat berikut: 'Karena tingginya curah hujan dan buruknya sistem drainase, wilayah ibu kota mengalami banjir parah.' Pola pengembangan apakah ini?",
                options: [
                    "Akibat-sebab",
                    "Sebab-akibat",
                    "Definisi",
                    "Generalisasi"
                ],
                correctIndex: 1,
                rationale: "Pola sebab-akibat mendahulukan sebab (curah hujan tinggi dan drainase buruk) yang memunculkan akibat tertentu (banjir parah).",
                hint: "Penyebab disebutkan terlebih dahulu sebelum menghasilkan dampak."
            },
            {
                question: "Pola pengembangan argumentasi yang berpangkal dari peristiwa-peristiwa khusus menuju ke kesimpulan umum disebut...",
                options: [
                    "Deduktif",
                    "Induktif",
                    "Deskriptif",
                    "Persuasif"
                ],
                correctIndex: 1,
                rationale: "Pola induktif menyusun argumen dari hal-hal khusus atau spesifik menuju generalisasi atau kesimpulan umum di akhir.",
                hint: "Dimulai dari data spesifik lalu disimpulkan secara umum."
            },
            {
                question: "Apa yang dimaksud dengan pola pengembangan deduktif dalam teks argumentasi?",
                options: [
                    "Dimulai dari pernyataan umum di awal lalu diikuti perincian bukti-bukti khusus.",
                    "Dimulai dari contoh kecil hingga menyimpulkan hukum umum.",
                    "Hanya berisi opini tanpa memerlukan landasan teori.",
                    "Menyajikan urutan waktu kejadian secara kronologis."
                ],
                correctIndex: 0,
                rationale: "Deduktif menempatkan gagasan utama atau tesis di awal paragraf (umum), kemudian dijabarkan dengan rincian khusus di kalimat-kalimat berikutnya.",
                hint: "Gagasan utama berada di awal paragraf."
            },
            {
                question: "Manakah di bawah ini yang merupakan ciri kaidah kebahasaan teks argumentasi?",
                options: [
                    "Banyak menggunakan kata kerja mental dan konjungsi temporal.",
                    "Menggunakan kata penghubung antarkalimat yang menyatakan pertentangan atau akibat.",
                    "Wajib menggunakan dialog langsung antar-tokoh.",
                    "Menggunakan latar tempat dan waktu yang sangat mendetail."
                ],
                correctIndex: 1,
                rationale: "Teks argumentasi sering menggunakan konjungsi antarkalimat penanda logika seperti 'oleh karena itu', 'meskipun demikian', atau 'akibatnya'.",
                hint: "Fokus pada konjungsi penalaran logis."
            },
            {
                question: "Apa fungsi kata penghubung 'oleh karena itu' dalam struktur kalimat argumentatif?",
                options: [
                    "Menyatakan pertentangan ide.",
                    "Menyatakan hubungan sebab-akibat (konsekuensi).",
                    "Menyatakan penambahan informasi biasa.",
                    "Menyatakan pilihan alternatif."
                ],
                correctIndex: 1,
                rationale: "'Oleh karena itu' adalah konjungsi antarkalimat yang menyatakan hubungan konsekuensi atau akibat dari argumen sebelumnya.",
                hint: "Menandakan adanya kesimpulan atau akibat dari sebab sebelumnya."
            },
            {
                question: "Manakah kalimat yang menggunakan kata kerja mental (mental verbs)?",
                options: [
                    "Para peneliti mengukur suhu permukaan air laut setiap hari.",
                    "Masyarakat menyadari bahwa pentingnya menjaga kebersihan lingkungan.",
                    "Pemerintah membangun jalan tol trans-sumatera sepanjang ribuan kilometer.",
                    "Nelayan menangkap ikan menggunakan jaring modern di laut lepas."
                ],
                correctIndex: 1,
                rationale: "Kata 'menyadari' adalah kata kerja mental yang mengekspresikan persepsi, emosi, atau pemikiran subjek.",
                hint: "Cari kata kerja yang berkaitan dengan pemikiran, perasaan, atau persepsi."
            },
            {
                question: "Hubungan antarparagraf yang bersifat memperkuat atau menegaskan argumen sebelumnya biasanya ditandai oleh...",
                options: [
                    "Penggunaan konjungsi kontras seperti 'sebaliknya'.",
                    "Penggunaan penanda penguatan seperti 'selain itu' atau 'lebih lanjut'.",
                    "Pengalihan topik bahasan secara drastis ke masalah baru.",
                    "Peniadaan seluruh data pendukung di paragraf kedua."
                ],
                correctIndex: 1,
                rationale: "Transisi antarparagraf yang kohesif sering memakai frasa penghubung seperti 'selain itu' atau 'lebih lanjut' untuk memperluas argumen.",
                hint: "Menunjukkan penambahan atau penguatan argumen."
            },
            {
                question: "Jika paragraf kedua menyajikan sanggahan atau pandangan kontras terhadap paragraf pertama, hubungan antarparagraf tersebut adalah...",
                options: [
                    "Hubungan perbandingan sejajar",
                    "Hubungan pertentangan / perlawanan",
                    "Hubungan sebab-akibat murni",
                    "Hubungan kronologis waktu"
                ],
                correctIndex: 1,
                rationale: "Hubungan pertentangan antarparagraf digunakan untuk mendiskusikan sisi lain, kontra-argumen, atau perbandingan yang kontras.",
                hint: "Menyajikan sudut pandang yang berlawanan."
            },
            {
                question: "Manakah kalimat fakta yang valid untuk mendukung argumen tentang bahaya sampah plastik?",
                options: [
                    "Sampah plastik adalah ciptaan manusia paling jahat di bumi.",
                    "Menurut laporan WWF 2023, Indonesia menghasilkan sekitar 7 juta ton sampah plastik per tahun.",
                    "Menurut saya, semua pabrik plastik harus segera ditutup tanpa kecuali.",
                    "Sampah plastik di masa depan pasti akan menghancurkan seluruh umat manusia."
                ],
                correctIndex: 1,
                rationale: "Pernyataan yang menyebutkan lembaga riset (WWF) dan angka statistik kuantitatif (7 juta ton per tahun) merupakan data fakta.",
                hint: "Cari kalimat yang mencantumkan sumber kredibel dan data numerik."
            },
            {
                question: "Apa peran dari penggunaan istilah teknis atau ilmiah dalam teks argumentasi?",
                options: [
                    "Membuat pembaca kebingungan dan kesulitan memahami teks.",
                    "Menambah validitas, tingkat kepercayaan, dan kedalaman ilmiah argumen.",
                    "Mengubah teks argumentasi menjadi karya fiksi ilmiah murni.",
                    "Menghilangkan kebutuhan akan paragraf kesimpulan."
                ],
                correctIndex: 1,
                rationale: "Penggunaan istilah teknis memperkuat otoritas penulis dan menunjukkan bahwa argumen didasarkan pada bidang ilmu tertentu secara akurat.",
                hint: "Istilah khusus memperkuat keandalan isi teks."
            },
            {
                question: "Perhatikan kalimat: 'Jika penggunaan energi fosil terus berlanjut tanpa kendali, maka suhu bumi akan meningkat secara drastis.' Kalimat ini menunjukkan hubungan...",
                options: [
                    "Sebab-akibat",
                    "Kronologis",
                    "Perbandingan",
                    "Descriptive"
                ],
                correctIndex: 0,
                rationale: "Adanya kata 'Jika' dan 'maka' jelas menunjukkan hubungan kausalitas atau sebab-akibat.",
                hint: "Perhatikan pola kondisional 'jika-maka'."
            },
            {
                question: "Manakah bentuk argumen yang menggunakan metode generalisasi?",
                options: [
                    "Menarik kesimpulan umum berdasarkan beberapa sampel data atau kasus khusus yang valid.",
                    "Menyamakan dua hal yang tidak berkaitan sama sekali.",
                    "Menceritakan kisah hidup seseorang dari kecil hingga tua.",
                    "Menyusun urutan waktu peristiwa sejarah kemerdekaan."
                ],
                correctIndex: 0,
                rationale: "Generalisasi adalah proses penalaran yang menarik kesimpulan umum berdasarkan sejumlah data atau gejala khusus yang memadai.",
                hint: "Menyimpulkan hal umum dari beberapa sampel kasus."
            },
            {
                question: "Mengapa opini dalam teks argumentasi harus didukung oleh fakta?",
                options: [
                    "Agar opini tersebut berubah menjadi sebuah dongeng.",
                    "Agar opini memiliki landasan yang kuat dan dapat meyakinkan pembaca secara objektif.",
                    "Supaya jumlah kata dalam teks menjadi jauh lebih banyak.",
                    "Agar pembaca dapat langsung menolak isi teks."
                ],
                correctIndex: 1,
                rationale: "Opini tanpa fakta hanya akan menjadi klaim kosong. Fakta berfungsi sebagai bukti empiris yang menopang kebenaran opini tersebut.",
                hint: "Fakta memberi fondasi kuat pada pendapat."
            },
            {
                question: "Manakah kalimat yang menggunakan konjungsi antarkalimat pertentangan?",
                options: [
                    "Oleh karena itu, pemerintah harus segera menaikkan anggaran pendidikan.",
                    "Akan tetapi, masih banyak warga yang mengabaikan aturan tersebut.",
                    "Selain itu, sektor pariwisata juga mengalami peningkatan signifikan.",
                    "Dengan demikian, target swasembada pangan dapat tercapai."
                ],
                correctIndex: 1,
                rationale: "Frasa 'Akan tetapi' adalah konjungsi antarkalimat yang menyatakan pertentangan atau perlawanan ide dari kalimat sebelumnya.",
                hint: "Mencari konjungsi penanda kontras di awal klausa/kalimat."
            },
            {
                question: "Apa ciri utama kebahasaan dari segi leksikal dalam teks argumentasi ilmiah?",
                options: [
                    "Penggunaan kata sapaan akrab seperti 'kamu', 'aku', dan 'dia'.",
                    "Penggunaan kata denotatif, lugas, dan menghindari ambiguitas.",
                    "Penggunaan majora metafora berlebihan layaknya puisi romantis.",
                    "Penggunaan bahasa gaul yang sedang tren di media sosial."
                ],
                correctIndex: 1,
                rationale: "Teks argumentasi ilmiah menuntut penggunaan kata bermakna denotatif (lugas) agar tidak menimbulkan salah tafsir bagi pembaca.",
                hint: "Makna kata harus objektif dan tidak bermakna ganda."
            },
            {
                question: "Bagaimana hubungan antara paragraf pembuka (tesis) dan paragraf penutup (simpulan)?",
                options: [
                    "Keduanya membahas topik yang sama, di mana paragraf penutup merangkum kembali tesis dan argumen.",
                    "Paragraf penutup harus membahas topik yang sama sekali berbeda dari pembuka.",
                    "Paragraf pembuka berisi opini, sedangkan penutup berisi fiksi.",
                    "Tidak ada kaitan sama sekali antara pembuka dan penutup."
                ],
                correctIndex: 0,
                rationale: "Paragraf penutup merespons dan menegaskan kembali gagasan utama yang telah diperkenalkan pada paragraf pembuka (tesis).",
                hint: "Simpulan adalah bentuk akhir dari tesis yang telah diuji."
            },
            {
                question: "Mana yang paling tepat menggambarkan ciri kalimat deklaratif dalam teks argumentasi?",
                options: [
                    "Berfungsi untuk mengajukan pertanyaan kepada pembaca.",
                    "Berfungsi untuk memberikan pernyataan atau informasi secara tegas.",
                    "Berfungsi untuk memberikan perintah langsung.",
                    "Berfungsi untuk mengungkapkan kekaguman emosional."
                ],
                correctIndex: 1,
                rationale: "Kalimat deklaratif adalah kalimat pernyataan yang berfungsi menyampaikan informasi atau berita secara faktual kepada pembaca.",
                hint: "Kalimat pernyataan biasa yang berakhiran titik."
            },
            {
                question: "Dalam menyusun argumen, mengapa penggunaan referensi atau kutipan ahli sangat penting?",
                options: [
                    "Untuk memenuhi jumlah halaman minimum tugas.",
                    "Sebagai otoritas pendukung yang memperkuat kredibilitas pendapat penulis.",
                    "Agar pembaca mengira penulis adalah seorang profesor.",
                    "Untuk menghindari keharusan menulis argumen sendiri."
                ],
                correctIndex: 1,
                rationale: "Kutipan ahli memberikan dukungan otoritatif (authority evidence) yang membuat argumen jauh lebih sulit dipatahkan.",
                hint: "Pendapat pakar mendongkrak kepercayaan isi argumen."
            },
            {
                question: "Manakah pernyataan di bawah ini yang paling akurat membedakan teks argumentasi dan teks persuasi?",
                options: [
                    "Teks argumentasi berfokus pada pembuktian logis, sedangkan persuasi lebih menekankan ajakan atau bujukan emosional.",
                    "Teks persuasi tidak pernah menggunakan fakta sama sekali.",
                    "Teks argumentasi selalu berbentuk cerita pendek berdialog.",
                    "Tidak ada perbedaan mendasar di antara keduanya."
                ],
                correctIndex: 0,
                rationale: "Argumentasi menitikberatkan pada bukti logis dan rasional agar pembaca percaya, sedangkan persuasi lebih mengutamakan daya tarik psikologis/emosional untuk mengajak bertindak.",
                hint: "Perhatikan titik berat pada logika vs ajakan psikologis."
            },
            {
                question: "Apa fungsi konjungsi 'selain itu' dalam kohesi antarparagraf teks argumentasi?",
                options: [
                    "Menyatakan pertentangan tajam.",
                    "Menambahkan argumen atau data pendukung baru yang selaras.",
                    "Menyatakan kesimpulan akhir dari seluruh bab.",
                    "Menyatakan urutan waktu kejadian."
                ],
                correctIndex: 1,
                rationale: "'Selain itu' berfungsi sebagai penanda aditif (penambahan) untuk memperkaya argumen dengan poin atau data tambahan.",
                hint: "Menambahkan poin informasi berikutnya."
            },
            {
                question: "Manakah kalimat opini yang menggunakan modalitas kepastian/kemungkinan?",
                options: [
                    "Jumlah penduduk Indonesia saat ini mencapai lebih dari 275 jiwa.",
                    "Kemungkinan besar kebijakan hilirisasi nikel akan mendatangkan keuntungan besar bagi negara.",
                    "Undang-Undang Dasar 1945 disahkan pada tanggal 18 Agustus 1945.",
                    "Titik didih air murni pada tekanan 1 atmosfer adalah 100 derajat Celsius."
                ],
                correctIndex: 1,
                rationale: "Frasa 'Kemungkinan besar' merupakan modalitas yang menyatakan peluang atau opini subjektif terhadap suatu prediktabilitas.",
                hint: "Cari kata penanda peluang/kemungkinan."
            },
            {
                question: "Mengapa sebuah teks argumentasi harus menghindari penggunaan asumsi yang tidak berdasar?",
                options: [
                    "Karena teks argumentasi wajib didasarkan pada penalaran logis dan pembuktian empiris.",
                    "Karena pembaca menyukai cerita fiksi fantasi.",
                    "Agar penulis tidak perlu berpikir keras.",
                    "Supaya teks bisa diterbitkan sebagai novel best-seller."
                ],
                correctIndex: 0,
                rationale: "Teks argumentasi bertumpu pada logika dan bukti objektif; asumsi tanpa dasar akan melemahkan validitas argumen secara keseluruhan.",
                hint: "Argumentasi menuntut bukti nyata, bukan khayalan."
            },
            {
                question: "Bagaimanakah hubungan sebab-akibat dapat memperkuat koherensi antarparagraf?",
                options: [
                    "Paragraf pertama memaparkan masalah (sebab), dan paragraf berikutnya menguraikan dampak (akibat) yang ditimbulkannya.",
                    "Paragraf pertama dan kedua membahas dua hal yang tidak saling kenal.",
                    "Paragraf kedua meralat total seluruh isi paragraf pertama.",
                    "Paragraf penutup diletakkan di awal teks."
                ],
                correctIndex: 0,
                rationale: "Hubungan sebab-akibat menciptakan alur logis di mana peristiwa atau masalah di paragraf awal memicu konsekuensi yang dibahas di paragraf berikutnya.",
                hint: "Sebab di awal, akibat di kelanjutan paragraf."
            },
            {
                question: "Manakah yang termasuk ke dalam kalimat fakta?",
                options: [
                    "Pendidikan karakter di sekolah tampaknya belum berjalan secara optimal.",
                    "Siswa kelas XII SMAN 1 mengikuti Ujian Satuan Pendidikan berbasis komputer.",
                    "Menurut saya, metode pembelajaran daring kurang efektif bagi anak usia dini.",
                    "Seharusnya setiap guru memberikan perhatian lebih kepada siswa yang pasif."
                ],
                correctIndex: 1,
                rationale: "Kegiatan nyata yang dapat diverifikasi (siswa kelas XII SMAN 1 mengikuti ujian) merupakan fakta konkret.",
                hint: "Pilih kejadian nyata yang dapat diverifikasi."
            },
            {
                question: "Apa fungsi dari kalimat penjelas (pendukung) di dalam tubuh paragraf argumentasi?",
                options: [
                    "Menjabarkan ide pokok dengan menyertakan data, contoh, atau alasan logis.",
                    "Mengganti gagasan utama di setiap kalimat baru.",
                    "Membuat pembaca merasa bosan dengan kalimat bertele-tele.",
                    "Mengubah alur teks menjadi narasi sejarah."
                ],
                correctIndex: 0,
                rationale: "Kalimat penjelas berfungsi menguraikan gagasan utama secara rinci menggunakan bukti-bukti pendukung.",
                hint: "Fungsinya menguraikan ide pokok."
            },
            {
                question: "Manakah struktur penulisan teks argumentasi yang paling ideal secara umum?",
                options: [
                    "Pendahuluan -> Tubuh Argumen -> Simpulan / Penutup",
                    "Penutup -> Pendahuluan -> Tubuh Argumen",
                    "Tubuh Argumen -> Pendahuluan -> Pendahuluan",
                    "Abstraksi -> Koda -> Krisis"
                ],
                correctIndex: 0,
                rationale: "Struktur standar teks argumentasi terdiri atas pendahuluan (tesis), tubuh argumen (pembuktian), dan penutup (simpulan).",
                hint: "Urutan logis dari pengenalan, isi, hingga penutup."
            },
            {
                question: "Apa yang dimaksud dengan kohesi dalam teks argumentasi?",
                options: [
                    "Kepaduan bentuk kebahasaan antarkalimat dan antarparagraf.",
                    "Kesatuan makna dan gagasan utama teks.",
                    "Jumlah kata total dalam sebuah paragraf.",
                    "Penggunaan gaya bahasa majas personifikasi."
                ],
                correctIndex: 0,
                rationale: "Kohesi merujuk pada aspek formal kebahasaan (seperti konjungsi, repetisi, substitusi) yang memadukan bagian-bagian teks secara struktural.",
                hint: "Kepaduan bentuk dan struktur bahasa."
            },
            {
                question: "Apa yang dimaksud dengan koherensi dalam teks argumentasi?",
                options: [
                    "Kepaduan makna atau gagasan yang mengalir secara logis dari satu kalimat/paragraf ke kalimat/paragraf berikutnya.",
                    "Penggunaan titik dan koma yang sangat banyak.",
                    "Panjang pendeknya paragraf dalam teks.",
                    "Pemilihan jenis huruf (font) yang menarik."
                ],
                correctIndex: 1,
                rationale: "Koherensi adalah keterpaduan isi atau makna secara logis sehingga gagasan mudah dipahami oleh pembaca.",
                hint: "Keterpaduan alur makna dan pikiran."
            },
            {
                question: "Manakah kalimat yang menggunakan konjungsi penalaran (kausalitas)?",
                options: [
                    "Meskipun hari hujan, mereka tetap bersemangat datang ke sekolah.",
                    "Banjir bandang terjadi lantaran maraknya penebangan liar di kawasan hulu sungai.",
                    "Ayah membaca koran pagi, sedangkan ibu menyiapkan sarapan di dapur.",
                    "Dia belajar dengan giat agar mendapatkan beasiswa kuliah."
                ],
                correctIndex: 1,
                rationale: "Kata 'lantaran' menyatakan hubungan sebab-akibat (kausalitas) antara penebangan liar dan banjir bandang.",
                hint: "Mencari kata penanda alasan atau sebab."
            },
            {
                question: "Manakah pernyataan yang paling tepat mengenai hubungan antarkalimat dalam paragraf argumentasi?",
                options: [
                    "Setiap kalimat harus berdiri sendiri tanpa ada kaitannya dengan kalimat lain.",
                    "Kalimat-kalimat penjelas harus mendukung dan memperkuat gagasan kalimat utama.",
                    "Kalimat utama diletakkan secara acak di tengah tanpa pola.",
                    "Kalimat penjelas boleh bertentangan langsung dengan gagasan utama."
                ],
                correctIndex: 1,
                rationale: "Paragraf yang baik menuntut kalimat-kalimat penjelas untuk konsisten mendukung kalimat utama.",
                hint: "Kalimat penjelas bertugas menyokong kalimat utama."
            },
            {
                question: "Bagaimana cara mengenali paragraf argumentasi yang menggunakan pola perbandingan?",
                options: [
                    "Paragraf tersebut membahas kesamaan atau perbedaan dua objek untuk memperkuat pandangan penulis.",
                    "Paragraf tersebut menceritakan biografi tokoh secara kronologis.",
                    "Paragraf tersebut hanya berisi tabel angka tanpa penjelasan naratif.",
                    "Paragraf tersebut menggunakan dialog antartokoh fiktif."
                ],
                correctIndex: 0,
                rationale: "Pola perbandingan menyoroti aspek persamaan atau perbedaan dua hal guna mempertegas argumen yang ingin disampaikan.",
                hint: "Membandingkan dua objek atau situasi."
            },
            {
                question: "Manakah kalimat opini yang didasarkan pada nilai moral atau etika?",
                options: [
                    "Suhu rata-rata global meningkat 1,1 derajat Celsius sejak era pra-industri.",
                    "Sudah sepatutnya generasi muda melestarikan kebudayaan lokal di tengah arus globalisasi.",
                    "Berdasarkan sensus penduduk, 60% penduduk Indonesia berada di usia produktif.",
                    "Kecepatan cahaya di ruang hampa udara adalah sekitar 300.000 kilometer per detik."
                ],
                correctIndex: 1,
                rationale: "Penggunaan kata 'sudah sepatutnya' mencerminkan nilai moral atau pendapat normatif (opini) penulis.",
                hint: "Mengandung kata anjuran atau nilai kepatutan."
            },
            {
                question: "Mengapa argumen yang hanya didasarkan pada emosi semata dianggap kurang kuat dalam teks argumentasi ilmiah?",
                options: [
                    "Karena teks argumentasi mengutamakan pembuktian rasional dan data objektif.",
                    "Karena emosi dilarang dalam seluruh karya tulis sastra.",
                    "Karena pembaca tidak memiliki perasaan.",
                    "Karena emosi membuat jumlah kata berkurang."
                ],
                correctIndex: 0,
                rationale: "Meskipun kadang menyentuh aspek persuasif, argumen ilmiah wajib bertumpu pada logika rasional dan bukti empiris, bukan sekadar rayuan emosional.",
                hint: "Argumentasi ilmiah berpusat pada akal sehat dan data."
            },
            {
                question: "Manakah kalimat fakta yang menunjukkan data waktu dan tempat yang spesifik?",
                options: [
                    "Krisis ekonomi global diperkirakan akan terjadi dalam waktu dekat.",
                    "Proklamasi kemerdekaan Republik Indonesia dibacakan di Jalan Pegangsaan Timur No. 56, Jakarta.",
                    "Pemerintah tampaknya perlu memperketat pengawasan lalu lintas udara.",
                    "Menurut saya, kota ini sangat nyaman untuk dijadikan tempat tinggal hari tua."
                ],
                correctIndex: 1,
                rationale: "Pernyataan peristiwa sejarah dengan detail waktu dan tempat yang jelas merupakan bentuk fakta mutlak.",
                hint: "Memuat informasi sejarah/peristiwa nyata yang terverifikasi."
            },
            {
                question: "Apa fungsi konjungsi 'akibatnya' dalam struktur kalimat argumentatif?",
                options: [
                    "Menyatakan sebab atau latar belakang suatu peristiwa.",
                    "Menunjukkan hasil atau konsekuensi logis dari tindakan/kondisi sebelumnya.",
                    "Menyatakan pertentangan pendapat yang tajam.",
                    "Menyatakan pilihan alternatif antara dua hal."
                ],
                correctIndex: 1,
                rationale: "'Akibatnya' secara langsung menghubungkan suatu kondisi penyebab dengan hasil atau konsekuensi yang ditimbulkannya.",
                hint: "Menandakan hasil akhir dari sebuah peristiwa."
            },
            {
                question: "Bagaimana cara paragraf penutup mengikat keseluruhan isi teks argumentasi?",
                options: [
                    "Dengan mengulang tesis secara verbatim dan menambahkan ringkasan argumen utama.",
                    "Dengan membuka topik baru yang sama sekali tidak dibahas sebelumnya.",
                    "Dengan menyertakan daftar pustaka lengkap di dalam paragraf.",
                    "Dengan menghentikan cerita secara tiba-tiba tanpa konklusi."
                ],
                correctIndex: 0,
                rationale: "Paragraf penutup merangkum kembali esensi tesis dan argumen utama untuk memberikan kesan akhir yang kuat kepada pembaca.",
                hint: "Merangkum kembali inti gagasan utama."
            },
            {
                question: "Manakah kalimat yang menggunakan modalitas keharusan?",
                options: [
                    "Masyarakat boleh memilih menggunakan transportasi umum atau kendaraan pribadi.",
                    "Pemerintah harus mengambil langkah tegas untuk menekan tingkat polusi udara.",
                    "Barangkali kebijakan ini dapat diterapkan pada tahun depan.",
                    "Kemungkinan besar harga bahan pokok akan stabil menjelang hari raya."
                ],
                correctIndex: 1,
                rationale: "Kata 'harus' merupakan modalitas yang menyatakan kewajiban atau keharusan dalam bertindak.",
                hint: "Cari kata yang menunjukkan kewajiban."
            },
            {
                question: "Apa yang dimaksud dengan gagasan utama dalam sebuah paragraf argumentasi?",
                options: [
                    "Pikiran pokok atau ide dasar yang menjadi jiwa dari keseluruhan isi paragraf.",
                    "Kalimat terakhir yang berisi daftar pustaka.",
                    "Judul utama yang terletak paling atas halaman.",
                    "Contoh kasus acak yang diselipkan di tengah teks."
                ],
                correctIndex: 0,
                rationale: "Gagasan utama adalah inti pembahasan yang diuraikan lebih lanjut melalui kalimat-kalimat penjelas dalam paragraf.",
                hint: "Ide dasar yang mendasari seluruh kalimat dalam paragraf."
            },
            {
                question: "Manakah pola pengembangan paragraf yang menyajikan kesimpulan umum di awal kalimat, lalu diikuti rincian di bawahnya?",
                options: [
                    "Induktif",
                    "Deduktif",
                    "Campuran",
                    "Kronologis"
                ],
                correctIndex: 1,
                rationale: "Pola deduktif menempatkan gagasan utama di awal (umum) lalu merinci ke khusus.",
                hint: "Gagasan di awal paragraf."
            },
            {
                question: "Mengapa kalimat opini dalam teks argumentasi perlu disaring secara cermat?",
                options: [
                    "Agar tidak menyesatkan pembaca dan tetap berpijak pada landasan logika yang sehat.",
                    "Agar semua teks berubah menjadi kamus bahasa.",
                    "Supaya penulis tidak memiliki pandangan pribadi sama sekali.",
                    "Agar paragraf menjadi lebih panjang dan rumit."
                ],
                correctIndex: 0,
                rationale: "Opini yang tidak didukung data logis dapat menjatuhkan kredibilitas teks argumentasi menjadi sekadar isapan jempol atau hoaks.",
                hint: "Menjaga kualitas logika agar tidak menyesatkan."
            },
            {
                question: "Manakah kalimat yang menunjukkan hubungan perbandingan antarkalimat?",
                options: [
                    "Tingkat literasi digital di perkotaan sangat tinggi; sebaliknya, di wilayah pedesaan angkanya masih sangat rendah.",
                    "Oleh karena itu, program digitalisasi sekolah harus segera diperluas.",
                    "Selain itu, fasilitas komputer di setiap kelas juga harus ditambah.",
                    "Dengan demikian, kesenjangan pendidikan dapat segera diatasi."
                ],
                correctIndex: 0,
                rationale: "Penggunaan kata 'sebaliknya' menunjukkan perbandingan kontras antara dua kondisi wilayah yang berbeda.",
                hint: "Membandingkan dua kondisi yang berbeda."
            },
            {
                question: "Apa peran penting dari data statistik dalam tubuh teks argumentasi?",
                options: [
                    "Sebagai bukti empiris yang objektif untuk meyakinkan pembaca.",
                    "Sebagai hiasan visual agar halaman tidak tampak kosong.",
                    "Sebagai hiburan ringan bagi pembaca di kala penat.",
                    "Sebagai pengganti judul teks."
                ],
                correctIndex: 0,
                rationale: "Statistik menyediakan angka dan persentase terukur yang membuat argumen sulit dibantah secara subjektif.",
                hint: "Angka dan data memperkuat pembuktian objektif."
            },
            {
                question: "Manakah pernyataan yang paling tepat mengenai hubungan antarparagraf yang koheren?",
                options: [
                    "Transisi antarparagraf harus mengalir secara mulus dengan jembatan makna yang logis.",
                    "Setiap paragraf harus membahas tema yang sama sekali tidak berhubungan.",
                    "Paragraf kedua boleh melompat ke topik lain tanpa penjelasan.",
                    "Transisi antarparagraf hanya ditentukan oleh jumlah kata."
                ],
                correctIndex: 0,
                rationale: "Koherensi antarparagraf menuntut adanya kesinambungan ide dan transisi mulus agar pembaca dapat mengikuti alur berpikir penulis.",
                hint: "Alur transisi ide harus mulus dan terhubung."
            },
            {
                question: "Manakah contoh kalimat fakta yang memuat variabel ilmiah?",
                options: [
                    "Air mendidih pada suhu 100 derajat Celsius pada tekanan udara standar 1 atm.",
                    "Menurut saya, air es sangat menyegarkan diminum pada siang hari yang terik.",
                    "Seharusnya setiap rumah tangga menyaring air minum sebelum dikonsumsi.",
                    "Kualitas air di kota ini tampaknya sudah tercemar limbah industri."
                ],
                correctIndex: 0,
                rationale: "Fakta ilmiah bersifat universal dan dapat dibuktikan di laboratorium (titik didih air).",
                hint: "Hukum atau ketetapan ilmiah yang teruji."
            },
            {
                question: "Apa tujuan dari penyusunan kerangka karangan sebelum menulis teks argumentasi?",
                options: [
                    "Agar struktur teks menjadi sistematis, logis, dan tidak keluar dari topik pembahasan.",
                    "Agar penulis bisa langsung menulis tanpa berpikir.",
                    "Supaya teks otomatis menjadi panjang tanpa isi.",
                    "Agar pembaca merasa kebingungan dengan alurnya."
                ],
                correctIndex: 0,
                rationale: "Kerangka karangan membantu penulis menjaga alur logika, struktur, dan kelengkapan argumen agar tetap fokus.",
                hint: "Panduan terstruktur agar tulisan tidak keluar jalur."
            },
            {
                question: "Manakah kalimat yang menggunakan konjungsi penanda tujuan?",
                options: [
                    "Pemerintah mengalokasikan dana besar agar fasilitas kesehatan di daerah pelosok merata.",
                    "Meskipun anggarannya terbatas, pembangunan tetap berjalan lancar.",
                    "Oleh karena itu, masyarakat diminta bersabar.",
                    "Selain itu, kualitas tenaga medis juga terus ditingkatkan."
                ],
                correctIndex: 0,
                rationale: "Konjungsi 'agar' digunakan untuk menyatakan maksud atau tujuan dari suatu tindakan.",
                hint: "Mencari kata penanda maksud/tujuan."
            },
            {
                question: "Bagaimanakah bentuk penalaran induktif dalam teks argumentasi?",
                options: [
                    "Menarik kesimpulan umum berdasarkan fakta-fakta khusus yang terkumpul.",
                    "Menarik kesimpulan khusus dari prinsip umum yang sudah diakui.",
                    "Membuat cerita fiktif tanpa akhir yang jelas.",
                    "Mengulang kalimat yang sama di setiap paragraf."
                ],
                correctIndex: 0,
                rationale: "Penalaran induktif bergerak dari hal-hal spesifik (fakta khusus) menuju generalisasi umum di akhir.",
                hint: "Dari khusus menuju umum."
            },
            {
                question: "Manakah kalimat opini yang mencerminkan ketidakpastian atau keraguan?",
                options: [
                    "Berdasarkan data sensus, jumlah penduduk usia produktif mencapai 70%.",
                    "Barangkali kebijakan pembatasan kendaraan pribadi ini belum efektif menekan kemacetan.",
                    "Hukum gravitasi bumi menyebabkan benda jatuh ke bawah.",
                    "Indonesia terletak di antara dua benua dan dua samudra."
                ],
                correctIndex: 1,
                rationale: "Kata 'Barangkali' menunjukkan keraguan atau opini subjektif yang belum dipastikan kebenarannya.",
                hint: "Menunjukkan dugaan atau keraguan."
            },
            {
                question: "Apa ciri kebahasaan dari penggunaan kalimat direktif dalam beberapa konteks teks argumentasi persuasif?",
                    options: [
                    "Berisi ajakan atau seruan agar pembaca melakukan tindakan tertentu.",
                    "Berisi rincian data angka kematian yang sangat kaku.",
                    "Berisi deskripsi fisik warna bangunan secara detail.",
                    "Berisi daftar pustaka buku referensi ilmiah."
                ],
                correctIndex: 0,
                rationale: "Kalimat direktif atau imperatif dalam teks argumentasi berfungsi menggerakkan pembaca untuk mendukung atau melakukan aksi nyata terkait argumen.",
                hint: "Kalimat yang bersifat menyerukan atau mengajak."
            },
            {
                question: "Manakah kalimat yang menunjukkan hubungan penambahan (aditif) antarkalimat?",
                options: [
                    "Di samping itu, program magang industri juga memberikan pengalaman kerja nyata bagi mahasiswa.",
                    "Akan tetapi, masih banyak kendala birokrasi yang menghambat.",
                    "Oleh karena itu, reformasi birokrasi mendesak dilakukan.",
                    "Akibatnya, banyak lulusan kesulitan mencari pekerjaan."
                ],
                correctIndex: 0,
                rationale: "Frasa 'Di samping itu' berfungsi menambahkan informasi atau argumen baru yang selaras.",
                hint: "Menambahkan informasi atau poin baru."
            },
            {
                question: "Mengapa argumen yang menggunakan bukti kesaksian saksi mata atau pakar perlu diuji kredibilitasnya?",
                options: [
                    "Agar kesaksian tersebut terbebas dari bias kepentingan pribadi dan benar-benar objektif.",
                    "Agar saksi mata tidak perlu hadir di pengadilan.",
                    "Supaya jumlah halaman naskah bertambah banyak.",
                    "Agar pembaca merasa bosan dengan kutipan."
                ],
                correctIndex: 0,
                rationale: "Uji kredibilitas penting untuk memastikan bahwa narasumber atau pakar tidak memiliki konflik kepentingan dan memang kompeten di bidangnya.",
                hint: "Memastikan narasumber terpercaya dan bebas bias."
            },
            {
                question: "Manakah kalimat fakta yang didukung oleh data penelitian resmi?",
                options: [
                    "Menurut laporan Bank Dunia 2024, pertumbuhan ekonomi Indonesia berada di kisaran 5%."),
                    "Menurut saya, pertumbuhan ekonomi tahun ini akan meroket tajam.",
                    "Seharusnya bank sentral menurunkan suku bunga pinjaman.",
                    "Tampaknya kondisi finansial masyarakat mulai membaik."
                ],
                correctIndex: 0,
                rationale: "Penyebutan lembaga resmi (Bank Dunia) beserta tahun laporan dan angka statistik merupakan fakta terverifikasi.",
                hint: "Memuat laporan institusi resmi dan data statistik."
            },
            {
                question: "Apa fungsi utama dari kalimat penegas (reiterasi) di bagian simpulan teks argumentasi?",
                options: [
                    "Mengingatkan kembali kepada pembaca mengenai inti tesis dan kekuatan argumen yang telah dibahas.",
                    "Mengajukan teka-teki baru yang belum terjawab.",
                    "Memuat iklan komersial produk sponsor.",
                    "Mengubah seluruh argumen yang sudah ditulis di atas."
                ],
                correctIndex: 0,
                rationale: "Reiterasi di penutup berfungsi mempertegas kembali pandangan penulis agar melekat kuat di benak pembaca.",
                hint: "Menegaskan kembali inti pokok pembahasan."
            },
            {
                question: "Manakah kalimat opini yang menggunakan modalitas kemampuan/kemungkinan?",
                options: [
                    "Teknologi kecerdasan buatan dapat mengubah lanskap dunia kerja di masa depan.",
                    "Bumi berputar mengelilingi porosnya dalam waktu 24 jam.",
                    "Titik didih air adalah 100 derajat Celsius pada tekanan normal.",
                    "Indonesia mendeklarasikan kemerdekaannya pada 17 Agustus 1945."
                ],
                correctIndex: 0,
                rationale: "Kata 'dapat' merupakan modalitas yang menyatakan kemampuan atau kemungkinan terjadinya suatu hal di masa depan (opini prediktif).",
                hint: "Menunjukkan potensi atau kemungkinan."
            },
            {
                question: "Bagaimana hubungan antara paragraf tubuh argumen yang satu dengan tubuh argumen berikutnya?",
                options: [
                    "Harus saling mendukung dan memperluas dimensi pembuktian tesis secara sistematis.",
                    "Harus saling bertentangan dan meniadakan satu sama lain.",
                    "Tidak memiliki hubungan transisi sama sekali.",
                    "Harus membahas topik kuliner yang berbeda."
                ],
                correctIndex: 0,
                rationale: "Setiap paragraf di tubuh argumen memegang aspek pembuktian yang berbeda namun saling menopang untuk menguatkan tesis utama.",
                hint: "Saling memperluas dan menopang pembuktian."
            },
            {
                question: "Manakah kalimat yang menggunakan konjungsi temporal dalam narasi pendukung argumentasi?",
                options: [
                    "Setelah melalui serangkaian uji klinis, vaksin tersebut akhirnya dinyatakan aman untuk didistribusikan.",
                    "Oleh karena itu, masyarakat diminta tidak panik.",
                    "Meskipun demikian, pengawasan tetap diperketat.",
                    "Selain itu, efek sampingnya tergolong sangat ringan."
                ],
                correctIndex: 0,
                rationale: "Kata 'Setelah' berfungsi sebagai konjungsi temporal yang menyatakan urutan waktu kejadian.",
                hint: "Menunjukkan urutan waktu atau kejadian."
            },
            {
                question: "Apa yang membedakan argumen berbasis logika deduktif dan induktif?",
                options: [
                    "Deduktif bergerak dari umum ke khusus, sedangkan induktif dari khusus ke umum.",
                    "Deduktif menggunakan fiksi, sedangkan induktif menggunakan puisi.",
                    "Deduktif tidak memerlukan fakta, sedangkan induktif wajib fakta.",
                    "Tidak ada perbedaan sama sekali di antara keduanya."
                ],
                correctIndex: 0,
                rationale: "Perbedaan utamanya terletak pada arah penalaran: deduktif (umum ke khusus) vs induktif (khusus ke umum).",
                hint: "Perhatikan arah alur penalaran umum dan khususnya."
            },
            {
                question: "Manakah kalimat opini yang bersifat evaluatif?",
                options: [
                    "Kebijakan pembatasan jam operasional kendaraan berat dinilai sangat efektif mengurangi kemacetan.",
                    "Panjang jembatan Suramadu adalah sekitar 5,4 kilometer.",
                    "Provinsi Bali terletak di sebelah timur pulau Jawa.",
                    "Candi Borobudur dibangun pada masa dinasti Syailendra."
                ],
                correctIndex: 0,
                rationale: "Penilaian 'dinilai sangat efektif' merupakan bentuk evaluasi subjektif atau opini dari pengamat/penulis.",
                hint: "Mengandung penilaian atau evaluasi tertentu."
            },
            {
                question: "Mengapa penggunaan bahasa yang persuasif namun tetap objektif sangat dianjurkan dalam teks argumentasi?",
                options: [
                    "Agar pembaca tertarik dan terbujuk secara rasional tanpa merasa dikendalikan secara emosional.",
                    "Agar teks berubah menjadi naskah drama teater.",
                    "Supaya pembaca langsung menolak isi teks.",
                    "Agar tidak ada satu pun fakta yang tercantum."
                ],
                correctIndex: 0,
                rationale: "Keseimbangan antara daya tarik persuasif dan objektivitas data membuat pembaca yakin secara intelektual.",
                hint: "Membujuk secara rasional dan objektif."
            },
            {
                question: "Manakah kalimat yang menunjukkan hubungan penguatan argumen (penegasan)?",
                options: [
                    "Bahkan, beberapa studi independen menunjukkan hasil yang serupa mengenai penurunan kualitas air tanah.",
                    "Sebaliknya, sebagian kecil warga menolak program tersebut.",
                    "Oleh karena itu, proyek terpaksa dihentikan.",
                    "Meskipun demikian, anggaran tetap dicairkan."
                ],
                correctIndex: 0,
                rationale: "Kata 'Bahkan' berfungsi sebagai penanda penguatan atau eskalasi argumen yang semakin memperkuat klaim sebelumnya.",
                hint: "Menandakan penegasan atau penguatan tingkat lanjut."
            },
            {
                question: "Apa peran dari contoh konkret dalam paragraf tubuh argumentasi?",
                options: [
                    "Membumikan teori atau konsep abstrak agar lebih mudah dipahami dan diverifikasi oleh pembaca.",
                    "Mengisi ruang kosong agar halaman terlihat penuh.",
                    "Mengubah teks argumentasi menjadi buku cerita anak.",
                    "Menghilangkan kebutuhan akan gagasan utama."
                ],
                correctIndex: 0,
                rationale: "Contoh konkret memberikan gambaran nyata di dunia nyata yang membuat argumen teoretis menjadi masuk akal.",
                hint: "Memberikan ilustrasi nyata di lapangan."
            },
            {
                question: "Manakah kalimat fakta yang dapat diverifikasi melalui dokumen hukum?",
                options: [
                    "Undang-Undang Nomor 20 Tahun 2003 mengatur tentang Sistem Pendidikan Nasional di Indonesia.",
                    "Menurut saya, sistem pendidikan nasional saat ini sudah sangat ideal.",
                    "Seharusnya kurikulum sekolah direvisi setiap lima tahun sekali.",
                    "Tampaknya para siswa lebih menyukai metode belajar kelompok."
                ],
                correctIndex: 0,
                rationale: "Peraturan perundang-undangan resmi yang tercatat dalam lembaran negara merupakan fakta hukum yang valid.",
                hint: "Mengacu pada peraturan atau undang-undang resmi."
            },
            {
                question: "Bagaimana struktur paragraf campuran dalam teks argumentasi?",
                options: [
                    "Gagasan utama diletakkan di awal paragraf dan ditegaskan kembali di akhir paragraf.",
                    "Gagasan utama hanya diletakkan di tengah paragraf tanpa ada di tempat lain.",
                    "Paragraf tidak memiliki gagasan utama sama sekali.",
                    "Gagasan utama diletakkan secara tersembunyi di judul."
                ],
                correctIndex: 0,
                rationale: "Paragraf campuran (deduktif-induktif) memiliki gagasan utama di kalimat pertama dan ditekankan ulang di kalimat terakhir.",
                hint: "Ide pokok muncul di awal dan ditegaskan di akhir."
            },
            {
                question: "Manakah kalimat yang menggunakan konjungsi antarkalimat penanda konsekuensi?",
                options: [
                    "Konsekuensinya, perusahaan harus menanggung kerugian besar akibat kelalaian operasional tersebut.",
                    "Selain itu, manajemen juga harus merombak sistem keamanan.",
                    "Akan tetapi, para pegawai tetap bekerja seperti biasa.",
                    "Oleh karena itu, suasana tetap kondusif."
                ],
                correctIndex: 0,
                rationale: "Frasa 'Konsekuensinya' dengan jelas menyatakan akibat atau risiko logis dari tindakan sebelumnya.",
                hint: "Menyatakan akibat atau risiko dari suatu tindakan."
            },
            {
                question: "Mengapa penulisan tesis di awal teks argumentasi harus dirumuskan secara jelas dan tegas?",
                options: [
                    "Agar arah pembahasan dan fokus argumen mudah dipahami serta tidak melebar ke mana-mana.",
                    "Agar pembaca langsung merasa bosan di awal.",
                    "Supaya penulis tidak perlu menyusun tubuh argumen.",
                    "Agar teks tidak memiliki paragraf kesimpulan."
                ],
                correctIndex: 0,
                rationale: "Tesis yang jelas menjadi mercusuar penuntun arah bagi seluruh argumen dan bukti yang akan dijabarkan di bawahnya.",
                hint: "Sebagai panduan arah fokus utama tulisan."
            },
            {
                question: "Manakah kalimat opini yang memuat dugaan atau prediksi masa depan?",
                options: [
                    "Diprediksi pada tahun 2045 sebagian besar kota besar di dunia akan beralih menggunakan energi hijau.",
                    "Bumi mengelilingi matahari dalam waktu 365 hari.",
                    "Titik beku air murni adalah 0 derajat Celsius.",
                    "Jumlah provinsi di Indonesia saat ini tercatat secara resmi."
                ],
                correctIndex: 0,
                rationale: "Kata 'Diprediksi' menunjukkan ramalan atau opini prediktif terhadap kondisi masa depan.",
                hint: "Ramalan atau prediksi mengenai masa depan."
            },
            {
                question: "Apa hubungan antara kohesi leksikal (seperti repetisi dan sinonimi) dengan keutuhan teks argumentasi?",
                options: [
                    "Mempererat kepaduan bentuk bahasa sehingga pembaca tidak kehilangan benang merah pembahasan.",
                    "Membuat kalimat menjadi sangat repetitif dan membosankan.",
                    "Menghilangkan fungsi konjungsi secara total.",
                    "Mengubah genre tulisan menjadi puisi lama."
                ],
                correctIndex: 0,
                    rationale: "Kohesi leksikal melalui pengulangan kata kunci atau sinonim menjaga fokus pembaca pada topik utama argumen.",
                    hint: "Menjaga fokus topik melalui pengulangan kata kunci."
            },
            {
                question: "Manakah kalimat yang menunjukkan hubungan pengontrasan (pertentangan kuat) antarparagraf?",
                options: [
                    "Kendati demikian, masih terdapat segelintir pihak yang meragukan efektivitas kebijakan tersebut.",
                    "Selain itu, dukungan publik terus mengalir deras.",
                    "Oleh karena itu, program dilanjutkan ke tahap berikutnya.",
                    "Dengan demikian, target tercapai dengan baik."
                ],
                correctIndex: 0,
                rationale: "Frasa 'Kendati demikian' adalah konjungsi antarkalimat penanda pertentangan atau konsesi yang kuat.",
                hint: "Menyatakan pertentangan atau pengecualian."
            },
            {
                question: "Apa yang harus dilakukan penulis di bagian akhir paragraf simpulan teks argumentasi?",
                options: [
                    "Memberikan penegasan akhir yang menggugah kesadaran pembaca tanpa memunculkan argumen baru yang belum dibahas.",
                    "Memulai topik baru yang sama sekali belum dibahas di atas.",
                    "Memasukkan daftar seluruh buku referensi secara acak.",
                    "Meminta maaf kepada pembaca atas kesalahan penulisan."
                ],
                correctIndex: 0,
                rationale: "Simpulan yang baik merangkum poin-poin yang sudah dibahas dan memberikan kesan penutup yang kuat tanpa membuka topik baru.",
                hint: "Merangkum tanpa memunculkan topik baru."
            },
            {
                question: "Manakah kalimat fakta yang dapat diverifikasi melalui ilmu geografi?",
                options: [
                    "Gunung Merapi terletak di perbatasan Provinsi Jawa Tengah dan Daerah Istimewa Yogyakarta.",
                    "Menurut saya, pemandangan di lereng Gunung Merapi sangat menakjubkan.",
                    "Seharusnya para pendaki lebih berhati-hati saat cuaca mendung.",
                    "Tampaknya letusan gunung berapi membawa berkah tersendiri bagi kesuburan tanah."
                ],
                correctIndex: 0,
                rationale: "Letak geografis suatu gunung adalah data faktual nyata yang dapat diverifikasi di peta.",
                hint: "Fakta geografis yang nyata dan terpetakan."
            },
            {
                question: "Mengapa argumen yang menggunakan generalisasi terlalu luas (overgeneralization) dianggap cacat secara logis?",
                options: [
                    "Karena menarik kesimpulan umum untuk seluruh kelompok hanya berdasarkan sedikit sampel yang tidak representatif.",
                    "Karena terlalu banyak menggunakan angka statistik.",
                    "Karena menggunakan bahasa yang terlalu ilmiah.",
                    "Karena tidak memiliki judul karangan."
                ],
                correctIndex: 0,
                rationale: "Generalisasi berlebihan terjadi ketika sedikit kasus dianggap mewakili keseluruhan populasi, sehingga merusak validitas penalaran.",
                hint: "Menyamaratakan semua hal dari sampel yang sangat sedikit."
            },
            {
                question: "Manakah kalimat yang menggunakan konjungsi antarkalimat penanda pilihan atau kondisi lain?",
                options: [
                    "Di sisi lain, ada pula kelompok yang mengusulkan pendekatan alternatif melalui dialog terbuka.",
                    "Oleh karena itu, keputusan segera diambil.",
                    "Selain itu, dukungan logistik sudah siap.",
                    "Akibatnya, masalah dapat diselesaikan."
                ],
                correctIndex: 0,
                rationale: "Frasa 'Di sisi lain' menunjukkan sudut pandang atau kondisi alternatif lain dalam kerangka argumentasi.",
                hint: "Menunjukkan sudut pandang alternatif yang lain."
            },
            {
                question: "Apa kriteria utama penentu keberhasilan sebuah teks argumentasi?",
                options: [
                    "Kemampuannya menyajikan bukti logis dan data akurat sehingga berhasil meyakinkan pembaca secara rasional.",
                    "Kemampuannya membuat pembaca menangis terharu.",
                    "Jumlah halaman yang mencapai ratusan lembar.",
                    "Penggunaan gambar ilustrasi warna-warni."
                ],
                correctIndex: 0,
                rationale: "Keberhasilan teks argumentasi diukur dari kekuatan bukti logis dan rasionalitasnya dalam mengubah atau memperkuat keyakinan pembaca.",
                hint: "Sukses meyakinkan pembaca melalui bukti logis."
            }
        ];

        let currentQuestionIndex = 0;
        let score = 0;
        let answered = false;

        const startScreen = document.getElementById('start-screen');
        const quizScreen = document.getElementById('quiz-screen');
        const resultScreen = document.getElementById('result-screen');
        
        const questionNumberEl = document.getElementById('question-number');
        const currentScoreEl = document.getElementById('current-score');
        const questionTextEl = document.getElementById('question-text');
        const optionsContainer = document.getElementById('options-container');
        const feedbackArea = document.getElementById('feedback-area');
        const rationaleBox = document.getElementById('rationale-box');
        const hintContainer = document.getElementById('hint-container');
        const hintTextEl = document.getElementById('hint-text');
        
        const finalScoreDisplay = document.getElementById('final-score-display');
        const finalPercentage = document.getElementById('final-percentage');

        function startQuiz() {
            startScreen.classList.add('hidden');
            quizScreen.classList.remove('hidden');
            loadQuestion();
        }

        function loadQuestion() {
            answered = false;
            feedbackArea.classList.add('hidden');
            hintContainer.classList.add('hidden');
            
            const q = questionsData[currentQuestionIndex];
            questionNumberEl.innerText = `Soal ${currentQuestionIndex + 1} dari ${questionsData.length}`;
            currentScoreEl.innerText = score;
            questionTextEl.innerText = q.question;
            
            if (q.hint) {
                hintTextEl.innerText = q.hint;
                hintContainer.classList.remove('hidden');
            }

            optionsContainer.innerHTML = '';
            q.options.forEach((option, index) => {
                const btn = document.createElement('button');
                btn.className = "w-full text-left p-4 rounded-xl bg-slate-700/60 hover:bg-slate-700 border border-slate-600/60 text-slate-200 text-sm sm:text-base font-medium transition-all duration-150 flex items-center justify-between group";
                btn.innerHTML = `<span>${option}</span><span class="w-6 h-6 rounded-full border border-slate-500 flex items-center justify-center text-xs text-slate-400 group-hover:border-indigo-400 group-hover:text-indigo-400">${String.fromCharCode(65 + index)}</span>`;
                btn.onclick = () => selectOption(index, btn);
                optionsContainer.appendChild(btn);
            });
        }

        function selectOption(selectedIndex, btnElement) {
            if (answered) return;
            answered = true;

            const q = questionsData[currentQuestionIndex];
            const optionButtons = optionsContainer.children;

            if (selectedIndex === q.correctIndex) {
                score++;
                currentScoreEl.innerText = score;
                btnElement.className = "w-full text-left p-4 rounded-xl bg-emerald-950/80 border border-emerald-500 text-emerald-200 text-sm sm:text-base font-medium flex items-center justify-between shadow-lg";
                btnElement.innerHTML += `<span class="text-emerald-400 font-bold">✓ Benar</span>`;
            } else {
                btnElement.className = "w-full text-left p-4 rounded-xl bg-rose-950/80 border border-rose-500 text-rose-200 text-sm sm:text-base font-medium flex items-center justify-between shadow-lg";
                btnElement.innerHTML += `<span class="text-rose-400 font-bold">✕ Salah</span>`;
                
                // Highlight correct option
                const correctBtn = optionButtons[q.correctIndex];
                correctBtn.className = "w-full text-left p-4 rounded-xl bg-emerald-950/80 border border-emerald-500 text-emerald-200 text-sm sm:text-base font-medium flex items-center justify-between shadow-lg";
            }

            // Tampilkan Rationale
            rationaleBox.className = selectedIndex === q.correctIndex 
                ? "p-4 rounded-xl text-sm leading-relaxed bg-emerald-950/40 border border-emerald-900 text-emerald-300"
                : "p-4 rounded-xl text-sm leading-relaxed bg-rose-950/40 border border-rose-900 text-rose-300";
            
            rationaleBox.innerHTML = `<strong>Pembahasan:</strong> ${q.rationale}`;
            feedbackArea.classList.remove('hidden');

            // Nonaktifkan semua tombol setelah memilih
            for (let btn of optionButtons) {
                btn.disabled = true;
                btn.classList.add('cursor-not-allowed', 'opacity-80');
            }
        }

        function nextQuestion() {
            currentQuestionIndex++;
            if (currentQuestionIndex < questionsData.length) {
                loadQuestion();
            } else {
                showResults();
            }
        }

        function showResults() {
            quizScreen.classList.add('hidden');
            resultScreen.classList.remove('hidden');
            
            finalScoreDisplay.innerText = `${score} / ${questionsData.length}`;
            const percentage = Math.round((score / questionsData.length) * 100);
            finalPercentage.innerText = `Akurasi Ketepatan: ${percentage}%`;
        }

        function restartQuiz() {
            currentQuestionIndex = 0;
            score = 0;
            resultScreen.classList.add('hidden');
            startScreen.classList.remove('hidden');
        }
    </script>
</body>
</html>
```eof

### Ringkasan Kuis yang Dibuat
* **Jumlah Soal:** 80 Butir Soal Pilihan Ganda berkualitas tinggi.
* **Cakupan Materi:** Fakta & Opini, Struktur Teks Argumentasi (Pendahuluan, Tubuh Argumen, Penutup), Kaidah Kebahasaan (Konjungsi kausalitas/temporal, modalitas, verba mental), serta Hubungan Antarparagraf (Sebab-akibat, perbandingan, pertentangan, penambahan).
* **Fitur Interaktif:** Dilengkapi dengan sistem skor real-time, petunjuk (hint) pada tiap soal, pembahasan (rationale) mendalam di setiap jawaban, serta tampilan responsif modern berbasis Tailwind CSS.

Semoga kuis interaktif ini bermanfaat untuk menguji dan memperdalam pemahaman materi teks argumentasi Anda. Selamat berlatih dan semoga sukses!
