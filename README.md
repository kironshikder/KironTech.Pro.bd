<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script async custom-element="amp-auto-ads"
        src="https://cdn.ampproject.org/v0/amp-auto-ads-0.1.js">
    </script>
    <title>Kiron-Tech - সম্পূর্ণ ফ্রি লাইভ স্ট্রিমিং</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://vjs.zencdn.net/8.3.0/video-js.css" rel="stylesheet" />
    <script src="https://vjs.zencdn.net/8.3.0/video.min.js"></script>
    <style>
        body { background-color: #0b0f19; color: #fff; }
        .hero-bg { background: linear-gradient(to bottom, rgba(11, 15, 25, 0.4), #0b0f19), url('https://lh3.googleusercontent.com/pw/AP1GczOPgX7ZV6vblOeWt99wR4Gvn-XvalwFXBNgZ2ad9i7VoecvA9Aw3hWbYqBos0tu8EBg1n5Iq-zAqx7Hd4f2fDg-_mbUfXsIxTsypY5r1e4CBq4drNHxL5hDPwIj58d0dtuA-VRoaq1yX_TS6jhqQ6MtHQ=w912-h608-s-no-gm?authuser=0') no-repeat center center/cover; }
        .channel-card:hover { transform: translateY(-5px); border-color: #10b981; }
        
        /* ১৬:৯ সাইজ নিশ্চিত করার জন্য */
        .video-container {
            position: relative;
            width: 100%;
            aspect-ratio: 16 / 9;
            overflow: hidden;
            border-radius: 0.75rem;
        }
        #pstu-player {
            width: 100% !important;
            height: 100% !important;
        }
    </style>
</head>
<body>

    <header class="sticky top-0 z-50 bg-[#0f172a]/90 backdrop-blur-md border-b border-gray-800">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-black text-emerald-500">Kiron <span class="text-white">Tech</span></a>
            <amp-auto-ads type="adsense" data-ad-client="ca-pub-9664454297595711"></amp-auto-ads>
            <span class="bg-emerald-600 px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-widest">সম্পূর্ণ ফ্রি</span>
        </div>
    </header>

    <!-- প্লেয়ার সেকশন -->
    <section class="hero-bg py-8">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto">
                <div class="bg-gray-900/60 p-4 rounded-2xl border border-gray-800 shadow-2xl">
                    <div class="video-container">
                        <video id="pstu-player" class="video-js vjs-big-play-centered" controls preload="auto" data-setup='{}'>
                            <source src="https://owrcovcrpy.gpcdn.net/bpk-tv/1709/output/1709-audio_113392_eng=113200-video=2202800.m3u8" type="application/x-mpegURL">
                        </video>
                    </div>
                </div>
                
                <div class="mt-4 flex flex-col sm:flex-row justify-between items-center gap-4 px-2">
                    <h2 id="channel-title" class="text-xl font-bold text-emerald-400">বর্তমানে চলছে: BTV</h2>
                    <button onclick="goFullscreenLandscape()" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-2 px-5 rounded-lg flex items-center gap-2 transition-all shadow-lg">
                        🔄 ফুলস্ক্রিন 
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- ক্যাটাগরি এবং চ্যানেল সেকশন -->
    <section class="py-6 bg-[#090d16]">
        <div class="container mx-auto px-6">
            <h2 class="text-2xl font-bold mb-6 border-l-4 border-emerald-500 pl-4">সকল চ্যানেল লিস্ট</h2>
            
            <!-- ক্যাটাগরি ফিল্টার বাটন সেকশন -->
            <div class="flex flex-wrap gap-2 mb-8" id="category-buttons">
                <button onclick="filterChannels('bangla', this)" class="cat-btn bg-emerald-600 text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all shadow-md">Bangladeshi</button>
                <button onclick="filterChannels('english', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">English</button>
                <button onclick="filterChannels('indian_bangla', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">Indian Bangla</button>
                <button onclick="filterChannels('drama', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">Drama</button>
                <button onclick="filterChannels('movies', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">Movies</button>
                <button onclick="filterChannels('music', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">Music</button>
                <button onclick="filterChannels('news', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">News</button>

               <button onclick="filterChannels('sports', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">Sports</button>
                <button onclick="filterChannels('all', this)" class="cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700">সবগুলো</button>
            </div>

            <!-- চ্যানেল গ্রিড -->
            <div id="channel-grid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4"></div>
        </div>
    </section>

    <footer class="py-8 text-center text-gray-600 border-t border-gray-800">
        <p>© 2026 Kiron. All Rights Reserved.</p>
    </footer>

    <script>
        const channels = [
            // Bangladeshi
            {
                id: 1,
                name: "BTV",
                category: "bangla",
                streamUrl: "[https://streams.btvlive.gov.bd/live/37fd3e16-f4fd-4220-832a-d8b7e321fb9d/BD/355ba051-9a60-48aa-adcf-5a6c64da8c5c/index.m3u8]",
                logo: "https://images.seeklogo.com/logo-png/45/1/btv-bangladesh-television-logo-png_seeklogo-459657.png"
            },
            {
                id: 2,
                name: "Machranga HD",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1722/output/1722-audio_113522_eng=113200-video=2202800.m3u8",
                logo: "https://mail.maasranga.tv/public/customize/newImage/logo.png"
            },
            {
                id: 3,
                name: "Somoy TV",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1713/output/1713-audio_113432_eng=113200-video=2202800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/53/1/somoy-tv-logo-png_seeklogo-536972.png"
            },
            {
                id: 4,
                name: "Deepto TV HD",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1711/output/1711-audio_113412_eng=113200-video=2202800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/51/1/deepto-tv-logo-png_seeklogo-513994.png"
            },      
            {
                id: 5,
                name: "Independent TV HD",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1704/output/1704-audio_113342_eng=113200-video=1692000.m3u8",
                logo: "https://e7.pngegg.com/pngimages/969/124/png-clipart-logo-bangladesh-independent-television-television-channel-design-television-text-thumbnail.png"
            },
            {
                id: 15,
                name: "Channel 24 HD",
                category:  ["bangla", "news"],
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1703/output/1703-audio_113332_eng=113200-video=2202800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/42/1/channel-24-logo-png_seeklogo-424910.png"
            },
            {
                id: 16,
                name: "NTV HD",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1716/output/1716-audio_113462_eng=113200-video=2202800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/39/1/ntv-channel-logo-png_seeklogo-396286.png"
            },
            {
                id: 17,
                name: "Ekattor TV HD",
                category:  ["bangla", "news"],
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1705/output/1705-audio_113352_eng=113200-video=2202800.m3u8",
                logo: "https://cdn.ekattorbd.com/contents/themes/public/style/images/logo.png"
            },
            {
                id: 18,
                name: "BanglaVision HD",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1715/output/1715-audio_113452_eng=113200-video=2202800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/51/1/bangla-vision-tv-channel-logo-png_seeklogo-513051.png"
            },
            {
                id: 19,
                name: "DBC News HD",
                category:  ["bangla", "news"],
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1728/output/1728-audio_113582_eng=113200-video=3224800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/62/1/dbc-news-logo-png_seeklogo-626101.png"
            },
            {
                id: 20,
                name: "Jamuna TV HD",
                category: ["bangla", "news"],
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1701/output/1701-audio_113312_eng=113200-video=2202800.m3u8",
                logo: "https://assets-prod.services.toffeelive.com/w_480,q_75,f_webp/PiL635oBEef-9-uV2uCe/posters/36f380e0-6c71-4b27-a73b-2afb3ce7e982.png"
            },
            
            // English
            {
                id: 6,
                name: "Channel 1 HD",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1702/output/1702-audio_113322_eng=113200-video=2202800.m3u8",
                logo: "https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhD46az4QUFMgrdxbIN9e4EckzhxmEDtPIOGvWWqyA_5nWquqbZrpD6B11GRryRtWKOVTfjwHjqpX7DiKkik2Rwp0RQMMpfolhiuKKUr9TFdXV9C9hXKOnqyoLnsOVv2gUPdEp5d_O_Uwxx/s1600/channel-one.jpg"
            },
            {
                id: 7,
                name: "Channel 9 HD",
                category: "bangla",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1729/output/1729-audio_113592_eng=113200-video=2202800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/53/1/channel-9-logo-png_seeklogo-532421.png"
            },

            // Music
            {
                id: 11,
                name: "Sangeet Bangla HD",
                category: "music",
                streamUrl: "https://cdn-4.pishow.tv/live/1143/master.m3u8",
                logo: "https://www.medianews4u.com/wp-content/uploads/2021/08/Bengali-Music-channel-Sangeet-Bangla-rebranded-with-a-new-logo-and-fresh-packaging.jpg"
            },

            // Sports
            {
                id: 12,
                name: "T Sports HD",
                category: "sports",
                streamUrl: "https://s1.itcnbd.live/T-Sports-HD/tracks-v1a1/mono.m3u8",
                logo: "https://images.seeklogo.com/logo-png/64/1/t-sports-logo-png_seeklogo-640172.png"
            },
            {
                id: 13,
                name: "beIN Sports 1 HD",
                category: "sports",
                streamUrl: "https://cp11.adabmedia.com/hls2/sport.m3u8",
                logo: "https://cdn.ekatttorbd.com/contents/themes/public/style/images/logo.png"
            },

            // Drama
            {
                id: 14,
                name: "Deepto Drama",
                category: "drama",
                streamUrl: "https://owrcovcrpy.gpcdn.net/bpk-tv/1711/output/1711-audio_113412_eng=113200-video=2202800.m3u8",
                logo: "https://images.seeklogo.com/logo-png/51/1/deepto-tv-logo-png_seeklogo-513994.png"
            },

            // Movies & Indian Bangla
            
            { 
            id: 22, 
            name: "Sony MAX 2 HD", 
            category: "movies", 
            streamUrl: "https://stream.ottplus.bd/live/max_2_abr/live/max_2_720/chunks.m3u8",
            logo: "https://toffeelive.com/images/logos/logo.svg"
            },
            { 
            id: 23,
            name: "Sony SUB HD", 
            category: "movies",
            streamUrl: "https://stream.ottplus.bd/live/sub_hd_abr/live/sony_sub_hd_720/chunks.m3u8",
            logo: "https://toffeelive.com/images/logos/logo.svg"
            },
            { 
            id: 24,
            name: "Sony MAX  HD",
            category: "movies",
            streamUrl: "https://stream.ottplus.bd/live/max_hd_abr/live/max_hd_720/chunks.m3u8",
            logo: "https://toffeelive.com/images/logos/logo.svg"
            },
            { 
            id: 25, 
            name: "ZEE CINEMA HD",
            category: "movies",
            streamUrl: "https://stream.ottplus.bd/live/zee_cinema_hd_abr/live/zee_cinema_hd_720/chunks.m3u8",
            logo: "https://toffeelive.com/images/logos/logo.svg"
            },
            { 
            id: 26, 
            name: "Sony PIX HD",
            category: "movies",
            streamUrl: "https://stream.ottplus.bd/live/pix_hd_abr/live/sony_pix_hd_720/chunks.m3u8",
            logo: "https://toffeelive.com/images/logos/logo.svg" 
            },
            {
            id: 27, 
            name: "Sony Movies HD",
            category: "movies", 
            streamUrl: "https://a-cdn.klowdtv.com/live1/smc_720p/chunks.m3u8",
            logo: "https://toffeelive.com/images/logos/logo.svg"
            },
            { 
            id: 28,
            name: "Movies NOW HD",
            category: "movies",
            streamUrl: "https://autumn-shape-b04a.soft-disk-1347.workers.dev/?url=http://ftpbdlive.com:8097/MOVIES-NOW/index.fmp4.m3u8?token=8291e6bc6d2a2935e204c1838f5730291810b4de-58cc706032206f29cde79dadc472229d-1775633452-1775629852",
            logo: "https://toffeelive.com/images/logos/logo.svg"
            },
            {
                id: 29,
                name: "PTV HD",
                category: "",
                streamUrl: "http://10.10.230.182:8080/ch5/index.m3u8",
                logo: "https://cdn.ekattor-bd.com/contents/themes/public/style/images/logo.png"
            }
        ];

        const grid = document.getElementById('channel-grid');
        const player = videojs('pstu-player');

        // চ্যানেল গ্রিড রেন্ডার করার ফাংশন
        function renderChannels(channelList) {
            grid.innerHTML = '';
            if (channelList.length === 0) {
                grid.innerHTML = `<div class="col-span-full text-center py-8 text-gray-400">এই ক্যাটাগরিতে কোনো চ্যানেল পাওয়া যায়নি।</div>`;
                return;
            }

            channelList.forEach(ch => {
                const card = document.createElement('div');
                card.className = "channel-card bg-[#0f172a] p-4 rounded-xl border border-gray-800 cursor-pointer text-center transition-all duration-200";
                card.innerHTML = `
                    <img src="${ch.logo}" class="w-16 h-16 rounded-full mx-auto mb-3 object-cover border border-gray-700" onerror="this.src='https://via.placeholder.com/64?text=TV'">
                    <h3 class="font-bold text-sm text-gray-200">${ch.name}</h3>
                `;
                card.onclick = () => playStream(ch.streamUrl, ch.name);
                grid.appendChild(card);
            });
        }

        // ক্যাটাগরি ফিল্টার করার আপডেট ফাংশন
function filterChannels(category, btnElement) {
    const buttons = document.querySelectorAll('.cat-btn');
    buttons.forEach(btn => {
        btn.className = "cat-btn bg-gray-800 hover:bg-emerald-600/80 text-gray-300 hover:text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all border border-gray-700";
    });

    if (btnElement) {
        btnElement.className = "cat-btn bg-emerald-600 text-white font-semibold px-4 py-2 rounded-xl text-sm transition-all shadow-md";
    }

    if (category === 'all') {
        renderChannels(channels);
    } else {
        // .includes() দিয়ে চেক করা হচ্ছে ক্যাটাগরিটি অ্যারেতে আছে কিনা
        const filtered = channels.filter(ch => {
            if (Array.isArray(ch.category)) {
                return ch.category.includes(category);
            }
            return ch.category === category;
        });
        renderChannels(filtered);
    }
}


        // প্লেয়ার ফাংশন
        function playStream(url, name) {
            player.src({ src: url, type: 'application/x-mpegURL' });
            player.play();
            document.getElementById('channel-title').innerText = "বর্তমানে চলছে: " + name;
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // ফুলস্ক্রিন ও ল্যান্ডস্কেপ ওরিয়েন্টেশন
        function goFullscreenLandscape() {
            player.requestFullscreen();

            if (screen.orientation && screen.orientation.lock) {
                screen.orientation.lock('landscape').catch(function(error) {
                    console.log("ওরিয়েন্টেশন লক করা যায়নি:", error);
                });
            }
        }

        player.on('fullscreenchange', function() {
            if (!player.isFullscreen() && screen.orientation && screen.orientation.unlock) {
                screen.orientation.unlock();
            }
        });

        // পেজ লোড হওয়ার সাথে সাথেই Bangladeshi ফিল্টার সেট করার লজিক
        document.addEventListener("DOMContentLoaded", function() {
            const firstBtn = document.querySelector('.cat-btn');
            filterChannels('bangla', firstBtn);
        });
    </script>
</body>
</html>
