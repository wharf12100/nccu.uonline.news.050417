<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>跨國銜轉的教育擺渡人 - 互動困境模擬</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;700&display=swap');
        
        body {
            font-family: 'Noto Sans TC', sans-serif;
            background-color: #f8fafc;
            color: #334155;
        }

        .status-bar {
            transition: width 0.6s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .card-enter {
            animation: slideUp 0.6s ease-out;
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .stat-card {
            background: white;
            border-radius: 1.25rem;
            padding: 1rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
            border: 1px solid #e2e8f0;
        }

        .option-btn {
            transition: all 0.2s ease;
            border: 2px solid #f1f5f9;
        }

        .option-btn:hover {
            border-color: #10b981;
            background-color: #f0fdf4;
            transform: translateX(4px);
        }

        .scenario-header {
            background: linear-gradient(135deg, #065f46 0%, #059669 100%);
        }
    </style>
</head>
<body class="min-h-screen flex items-center justify-center p-4">

    <div id="game-container" class="max-w-4xl w-full">
        <!-- Start Screen -->
        <div id="start-screen" class="bg-white rounded-3xl shadow-2xl p-8 md:p-16 text-center card-enter">
            <div class="mb-8 inline-block p-6 bg-emerald-100 rounded-full text-emerald-600 text-6xl">
                <i class="fas fa-bridge-circle-exclamation"></i>
            </div>
            <h1 class="text-4xl font-bold mb-6 text-gray-800 tracking-tight">跨國銜轉的教育擺渡人</h1>
            <div class="text-left bg-slate-50 p-8 rounded-2xl mb-10 border-l-8 border-emerald-500 shadow-inner">
                <p class="text-gray-700 leading-relaxed text-lg">
                    你是一位擁有東南亞血緣背景的扶助教師。你深知學生的困難，因為你也是這麼走過來的。<br><br>
                    然而，即便你擁有雙語專業與熱忱，受限於體制，你始終無法考取「正職教師」。你是一座沒有終點站的橋樑，面對著：<br><br>
                    <span class="font-bold text-orange-600">● 奔波的體力</span>、<span class="font-bold text-red-600">● 情緒的磨損</span>、<span class="font-bold text-green-600">● 微薄的收入</span>、<span class="font-bold text-blue-600">● 職業的天花板</span>。<br><br>
                    當其中一項指標歸零，你的擺渡之路就將終止。你能撐過這個學期嗎？
                </p>
            </div>
            <button onclick="startGame()" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-5 px-16 rounded-full transition duration-300 shadow-xl transform hover:scale-105 text-xl tracking-widest">
                開始接案人生
            </button>
        </div>

        <!-- Main Game UI -->
        <div id="game-ui" class="hidden space-y-6">
            <!-- Status Panel - 4 Dimensions -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 sticky top-4 z-20">
                <div class="stat-card">
                    <div class="flex justify-between mb-2 text-sm font-bold text-orange-600">
                        <span><i class="fas fa-motorcycle mr-1"></i> 通勤體力</span>
                        <span id="stat-time-val">100%</span>
                    </div>
                    <div class="w-full bg-slate-100 rounded-full h-3">
                        <div id="stat-time-bar" class="status-bar bg-orange-500 h-3 rounded-full" style="width: 100%"></div>
                    </div>
                </div>
                <div class="stat-card">
                    <div class="flex justify-between mb-2 text-sm font-bold text-red-600">
                        <span><i class="fas fa-heart-pulse mr-1"></i> 心理能量</span>
                        <span id="stat-mental-val">100%</span>
                    </div>
                    <div class="w-full bg-slate-100 rounded-full h-3">
                        <div id="stat-mental-bar" class="status-bar bg-red-500 h-3 rounded-full" style="width: 100%"></div>
                    </div>
                </div>
                <div class="stat-card">
                    <div class="flex justify-between mb-2 text-sm font-bold text-green-600">
                        <span><i class="fas fa-wallet mr-1"></i> 經濟穩定</span>
                        <span id="stat-money-val">100%</span>
                    </div>
                    <div class="w-full bg-slate-100 rounded-full h-3">
                        <div id="stat-money-bar" class="status-bar bg-green-500 h-3 rounded-full" style="width: 100%"></div>
                    </div>
                </div>
                <div class="stat-card">
                    <div class="flex justify-between mb-2 text-sm font-bold text-blue-600" title="在體制中的專業認同與未來性">
                        <span><i class="fas fa-arrow-up-right-dots mr-1"></i> 職業認同</span>
                        <span id="stat-growth-val">100%</span>
                    </div>
                    <div class="w-full bg-slate-100 rounded-full h-3">
                        <div id="stat-growth-bar" class="status-bar bg-blue-500 h-3 rounded-full" style="width: 100%"></div>
                    </div>
                </div>
            </div>

            <!-- Scenario Card -->
            <div id="scenario-card" class="bg-white rounded-3xl shadow-2xl overflow-hidden card-enter border border-slate-200">
                <div class="scenario-header p-8 text-white flex items-center space-x-6">
                    <div id="scenario-icon" class="text-5xl opacity-80"></div>
                    <div>
                        <div class="text-emerald-200 text-xs font-bold tracking-widest mb-1 uppercase">Stage <span id="current-stage">1</span> / 8</div>
                        <h2 id="scenario-title" class="text-2xl font-bold"></h2>
                    </div>
                </div>
                <div class="p-8 md:p-10">
                    <p id="scenario-desc" class="text-gray-700 mb-10 leading-relaxed text-xl"></p>
                    <div id="options-container" class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <!-- Options injected here -->
                    </div>
                </div>
            </div>
        </div>

        <!-- Result Screen -->
        <div id="result-screen" class="hidden bg-white rounded-3xl shadow-2xl p-12 text-center card-enter">
            <div id="result-icon" class="text-8xl mb-8"></div>
            <h2 id="result-title" class="text-4xl font-bold mb-6 text-slate-800"></h2>
            <p id="result-desc" class="text-gray-600 mb-10 leading-relaxed text-xl max-w-2xl mx-auto"></p>
            <div id="result-stats" class="mb-10 text-left grid grid-cols-2 md:grid-cols-4 gap-4">
                <!-- Final stats injected here -->
            </div>
            <button onclick="location.reload()" class="bg-slate-800 hover:bg-black text-white font-bold py-5 px-16 rounded-full transition shadow-2xl text-lg">
                重新進入現場
            </button>
        </div>
    </div>

    <script>
        const stats = {
            time: 100,
            mental: 100,
            money: 100,
            growth: 100
        };

        const stages = [
            {
                title: "學期初的排課焦慮",
                desc: "雖然你有母語優勢，但在校園裡你只是「鐘點教學支援人員」。薪水按件計酬，若想維持生活，你必須在各區接案。",
                icon: "<i class='fas fa-calendar-check'></i>",
                options: [
                    {
                        text: "全力衝刺：跨三區接滿 22 堂課，填補經濟缺口。",
                        impact: { time: -35, money: 20, growth: -15, mental: -10 },
                        feedback: "你確保了收入，但每天在公路上與時間賽跑，讓你開始懷疑工作的價值。"
                    },
                    {
                        text: "平衡考量：只接鄰近區 15 堂課，留點時間生活。",
                        impact: { time: -15, money: -10, growth: 10, mental: 5 },
                        feedback: "比較從容，但你深刻感受到「鐘點身分」在扣掉保費後的經濟脆弱。"
                    },
                    {
                        text: "尋求兼職：接少量課，晚上去翻譯社打工補貼。",
                        impact: { time: -25, money: 25, growth: -20, mental: -5 },
                        feedback: "翻譯社薪水更高，你漸漸覺得校園教學只是某種「兼差」。"
                    },
                    {
                        text: "深耕教學：只接 8 堂，花心力自編教材求認同。",
                        impact: { time: -5, money: -35, growth: 25, mental: 0 },
                        feedback: "雖然這無法讓你考上正職，但你希望專業能被看見。"
                    }
                ]
            },
            {
                title: "同鄉家長的求救信",
                desc: "學生的越南籍媽媽在工廠受傷，因語言不通不敢就醫。這不是教學工作，但你是她唯一能求助的人。",
                icon: "<i class='fas fa-briefcase-medical'></i>",
                options: [
                    {
                        text: "熱血支援：請假一天陪同，處理職災補償。",
                        impact: { time: -25, mental: -10, growth: -5, money: -10 },
                        feedback: "家長感激，但你因缺課被校方微詞：『外聘老師請假很麻煩』。"
                    },
                    {
                        text: "限時協助：午休翻譯文件，引介社福單位。",
                        impact: { time: -10, mental: -5, growth: 0, money: 0 },
                        feedback: "你完成了對家長的交代，也守住了本職工作的底線。"
                    },
                    {
                        text: "專業切割：告知這不在教學範圍，請找仲介。",
                        impact: { time: 0, mental: -25, growth: -10, money: 0 },
                        feedback: "雖然省下時間，但「自己人都不幫」的罪惡感嚴重侵蝕你的內心。"
                    },
                    {
                        text: "社群動員：在同鄉社團徵求志工，分擔翻譯。",
                        impact: { time: -15, mental: 10, growth: 15, money: 0 },
                        feedback: "你建立了互助網，讓自己不再只是個體勞工，而是社群連結者。"
                    }
                ]
            },
            {
                title: "研習活動的排除感",
                desc: "教育局辦理教學增能研習，但規定只給編制內教師參加，外聘教支人員需自行申請且無補貼。你感覺被排斥在體制外。",
                icon: "<i class='fas fa-award'></i>",
                options: [
                    {
                        text: "自費參與：自行請假自費搭車，硬是要學。",
                        impact: { time: -10, money: -20, growth: 25, mental: -10 },
                        feedback: "你學到了專業，但體制的拒絕感讓你在研習現場感到非常孤單。"
                    },
                    {
                        text: "職場生存：不去研習，照常上課領鐘點費。",
                        impact: { time: -5, money: 5, growth: -15, mental: -5 },
                        feedback: "你保住了收入，但也默認了自己只是個體制外的「翻譯工人」。"
                    },
                    {
                        text: "主動串聯：找其他教支老師私下組讀書會自學。",
                        impact: { time: -15, mental: 15, growth: 20, money: 0 },
                        feedback: "你們決定不靠體制，靠彼此。這種同儕支持讓你重新找回認同。"
                    },
                    {
                        text: "放棄精進：認清現況，教完課就走，不再進修。",
                        impact: { time: 0, money: 0, growth: -30, mental: -5 },
                        feedback: "心冷了，你開始覺得學再多也無法改變身分，何必呢？"
                    }
                ]
            },
            {
                title: "教材在地化的重擔",
                desc: "校方沒有提供專屬教材，你得針對學生的母語特徵手寫教案。這耗費大量心力，卻無任何額外津貼。",
                icon: "<i class='fas fa-file-pen'></i>",
                options: [
                    {
                        text: "完美主義：每週熬夜三天，親自開發雙語學習單。",
                        impact: { time: -30, mental: 10, growth: 20, money: 0 },
                        feedback: "學生進步明顯，但你發現這份心血在學校系統裡根本不算考績。"
                    },
                    {
                        text: "務實整合：利用網路資源剪貼，快速出爐。",
                        impact: { time: -10, mental: -5, growth: -10, money: 0 },
                        feedback: "教學效果普通，但你明白沒人會因為你寫得好而幫你轉正。"
                    },
                    {
                        text: "要求支薪：向學校反映教材製作應計費。",
                        impact: { time: -5, mental: -30, growth: 0, money: 0 },
                        feedback: "主任表示沒這筆預算，並暗示「如果不願意，還有別人排隊」。"
                    },
                    {
                        text: "照本宣科：完全使用官方中文課本，不管難度。",
                        impact: { time: 0, mental: -20, growth: -25, money: 0 },
                        feedback: "你看著孩子眼神中的迷惘，痛苦地意識到自己正成為體制的共犯。"
                    }
                ]
            },
            {
                title: "交通意外與脆弱性",
                desc: "在趕往另一間學校的路上，你的機車拋錨了。維修費是你三天的鐘點費，且你正處於無勞健保保障的狀態。",
                icon: "<i class='fas fa-tools'></i>",
                options: [
                    {
                        text: "忍痛維修：立刻叫修並搭車趕課，守住信用。",
                        impact: { time: -10, money: -35, growth: 0, mental: -10 },
                        feedback: "你保住了專業形象，但本月的生存壓力讓你晚上失眠。"
                    },
                    {
                        text: "放棄該節：聯絡學校取消，推車去修，省下車資。",
                        impact: { time: -25, money: -15, growth: -10, mental: -5 },
                        feedback: "少了鐘點費又被學校行政記點，你深感勞動條件的不堪。"
                    },
                    {
                        text: "忍受不便：暫時不修，改搭公車，每天多花 2 小時。",
                        impact: { time: -40, money: 0, growth: -10, mental: -20 },
                        feedback: "金錢保住了，但長途候車與體力透支讓你整個人變得極度易怒。"
                    },
                    {
                        text: "轉向社群：求助於同鄉會，看有無人能低價讓機車。",
                        impact: { time: -15, money: -10, mental: 15, growth: 5 },
                        feedback: "同鄉伸出援手，你再次體會到體制外社群才是你的真實支柱。"
                    }
                ]
            },
            {
                title: "校園角色的邊緣化",
                desc: "學校開會討論學生問題，卻沒通知你。事後要你依照他們的決定執行，因為你只是「外聘人員」。",
                icon: "<i class='fas fa-users-slash'></i>",
                options: [
                    {
                        text: "隱忍配合：默默按照指示教課，不發表意見。",
                        impact: { time: 0, mental: -20, growth: -25, money: 0 },
                        feedback: "你保住了飯碗，但感覺自己只是一個可以被隨時替換的螺絲釘。"
                    },
                    {
                        text: "爭取話語：主動找主任溝通，強調外聘師的觀察。",
                        impact: { time: -10, mental: -35, growth: 10, money: 0 },
                        feedback: "雖然你有理，但在正式會議上被冷落的感覺讓你感到極大的羞辱。"
                    },
                    {
                        text: "專注學生：不理會行政，直接與班導師建立私交。",
                        impact: { time: -15, mental: 5, growth: 15, money: 0 },
                        feedback: "雖然繞過體制，但直接幫助到孩子的成就感讓你撐了下來。"
                    },
                    {
                        text: "冷處理：時間到就走人，不介入任何行政討論。",
                        impact: { time: 5, mental: 5, growth: -20, money: 0 },
                        feedback: "你保住了情緒，但你與這間學校的連結已經徹底斷裂。"
                    }
                ]
            },
            {
                title: "二代身分的心理折耗",
                desc: "一名孩子因為不願承認自己是新住民二代而哭泣。你彷彿看見過去的自己，但你此時的身分也無法給予他「翻身」的保證。",
                icon: "<i class='fas fa-language'></i>",
                options: [
                    {
                        text: "誠實分享：告訴他現實很難，但我們必須在一起。",
                        impact: { time: -10, mental: -30, growth: 15, money: 0 },
                        feedback: "這是一場靈魂的掏洗，你們都哭了，但你感到能量極速耗盡。"
                    },
                    {
                        text: "正向激勵：鼓勵他學好母語，未來能做跨國貿易。",
                        impact: { time: -5, mental: -10, growth: -10, money: 0 },
                        feedback: "雖然是標準答案，但你自己也知道這在目前的體制內談何容易。"
                    },
                    {
                        text: "尋求外援：引進新住民二代培力組織，擴大視野。",
                        impact: { time: -20, mental: 10, growth: 20, money: 0 },
                        feedback: "透過集體力量，孩子看到了更多可能，你也感到了專業的擴張。"
                    },
                    {
                        text: "壓抑情緒：叫他別想太多，寫完手上的練習單。",
                        impact: { time: 0, mental: -20, growth: -30, money: 0 },
                        feedback: "你選擇了最冷酷的方式，因為你已無力承擔更多學生的痛苦。"
                    }
                ]
            },
            {
                title: "最終的續聘抉擇",
                desc: "學期末，主任稱讚你，但表示鐘點費明年可能因為案量微調而下降，且依舊無法提供勞健保。你決定...",
                icon: "<i class='fas fa-door-open'></i>",
                options: [
                    {
                        text: "繼續忍受：為了那些孩子，接受更差的勞動條件。",
                        impact: { time: -20, mental: -25, money: -20, growth: -20 },
                        feedback: "你選擇了燃燒，但在這座天花板極低的體制下，你感到窒息。"
                    },
                    {
                        text: "調整比例：大幅減少教課，轉往非營利組織工作。",
                        impact: { time: 10, money: 10, growth: 30, mental: 15 },
                        feedback: "你決定跳脫正式教育體系，在公民社會尋求更具尊嚴的專業身分。"
                    },
                    {
                        text: "憤而離去：不再接案，全職轉行做私人通譯。",
                        impact: { time: 20, money: 40, growth: -40, mental: -10 },
                        feedback: "你選擇了生存。在離開校園的那刻，你知道那群孩子又少了一個同鄉老師。"
                    },
                    {
                        text: "微弱抵抗：聯合其他教支人員向教育局陳情勞權。",
                        impact: { time: -25, mental: -45, growth: 25, money: 0 },
                        feedback: "你們成了體制內的「刺頭」，前路艱險，但你第一次感到自己有聲音。"
                    }
                ]
            }
        ];

        let currentStage = 0;

        function startGame() {
            document.getElementById('start-screen').classList.add('hidden');
            document.getElementById('game-ui').classList.remove('hidden');
            renderStage();
        }

        function updateBars() {
            const fields = ['time', 'mental', 'money', 'growth'];
            let isGameOver = false;

            fields.forEach(f => {
                const val = Math.max(0, stats[f]);
                document.getElementById(`stat-${f}-val`).innerText = `${val}%`;
                const bar = document.getElementById(`stat-${f}-bar`);
                bar.style.width = `${val}%`;
                
                if (val < 25) {
                    bar.classList.add('animate-pulse');
                    bar.style.backgroundColor = '#ef4444';
                } else {
                    bar.classList.remove('animate-pulse');
                    const colors = {time:'#f97316', mental:'#ef4444', money:'#10b981', growth:'#3b82f6'};
                    bar.style.backgroundColor = colors[f];
                }

                if (val <= 0) isGameOver = true;
            });

            if (isGameOver) {
                endGame(false);
                return true;
            }
            return false;
        }

        function renderStage() {
            if (currentStage >= stages.length) {
                endGame(true);
                return;
            }

            const stage = stages[currentStage];
            document.getElementById('current-stage').innerText = currentStage + 1;
            document.getElementById('scenario-title').innerText = stage.title;
            document.getElementById('scenario-desc').innerText = stage.desc;
            document.getElementById('scenario-icon').innerHTML = stage.icon;

            const container = document.getElementById('options-container');
            container.innerHTML = '';

            stage.options.forEach((opt) => {
                const btn = document.createElement('button');
                btn.className = "option-btn w-full text-left p-6 rounded-2xl bg-white shadow-sm flex flex-col justify-between";
                btn.onclick = () => handleChoice(opt);
                btn.innerHTML = `
                    <span class="font-bold text-gray-800 mb-2 leading-snug">${opt.text}</span>
                    <span class="text-xs text-slate-400 font-medium italic">選擇此對策將改變你的處境</span>
                `;
                container.appendChild(btn);
            });
        }

        function handleChoice(option) {
            Object.keys(option.impact).forEach(k => {
                stats[k] = Math.min(100, Math.max(0, stats[k] + option.impact[k]));
            });

            if (updateBars()) return;

            const card = document.getElementById('scenario-card');
            card.innerHTML = `
                <div class="p-16 text-center animate-pulse">
                    <div class="text-6xl mb-8 text-emerald-500"><i class="fas fa-quote-left"></i></div>
                    <p class="text-2xl font-bold text-gray-800 mb-10 leading-relaxed">「${option.feedback}」</p>
                    <button onclick="nextStage()" class="bg-emerald-600 text-white px-16 py-4 rounded-full font-bold shadow-xl hover:bg-emerald-700 transition tracking-widest text-lg">進入下一階段</button>
                </div>
            `;
        }

        function nextStage() {
            currentStage++;
            document.getElementById('scenario-card').innerHTML = `
                <div class="scenario-header p-8 text-white flex items-center space-x-6">
                    <div id="scenario-icon" class="text-5xl opacity-80"></div>
                    <div>
                        <div class="text-emerald-200 text-xs font-bold tracking-widest mb-1 uppercase">Stage <span id="current-stage"></span> / 8</div>
                        <h2 id="scenario-title" class="text-2xl font-bold"></h2>
                    </div>
                </div>
                <div class="p-8 md:p-10">
                    <p id="scenario-desc" class="text-gray-700 mb-10 leading-relaxed text-xl"></p>
                    <div id="options-container" class="grid grid-cols-1 md:grid-cols-2 gap-4"></div>
                </div>
            `;
            renderStage();
        }

        function endGame(win) {
            document.getElementById('game-ui').classList.add('hidden');
            const screen = document.getElementById('result-screen');
            screen.classList.remove('hidden');

            const icon = document.getElementById('result-icon');
            const title = document.getElementById('result-title');
            const desc = document.getElementById('result-desc');
            const statsDiv = document.getElementById('result-stats');

            if (win) {
                icon.innerHTML = "<i class='fas fa-bridge text-emerald-600'></i>";
                title.innerText = "你是這座體制邊緣的守護者";
                desc.innerText = "雖然這條路看不見終點，你也深知自己永遠無法成為體制內的正式教師，但你撐過了一個學期。你的存在，讓這群孩子不至於在主流校園中徹底溺水。未來的路，依然需要你在縫隙中尋找尊嚴。";
            } else {
                icon.innerHTML = "<i class='fas fa-ban text-red-400'></i>";
                title.innerText = "擺渡之路戛然而止";
                
                let reason = "";
                if (stats.time <= 0) reason = "身體崩潰：你因為過度奔波與缺乏保障的長途騎行而體力透支，因病失去了所有的鐘點案件。";
                else if (stats.mental <= 0) reason = "心理瓦解：長期處於體制邊緣與歧視環境，你對教育的熱情已燃燒殆盡，無法再面對學生的眼神。";
                else if (stats.money <= 0) reason = "經濟崩解：微薄且不穩定的總收入已無法支撐最基本的生活開銷。你不得不選擇離開校園。";
                else if (stats.growth <= 0) reason = "身分絕望：你意識到在目前的體制下永遠只有被工具化的份，毫無專業尊嚴可言，最終選擇徹底轉職。";

                desc.innerText = `${reason} 你的離開，印證了這套制度對於東南亞裔扶助教師的漠視與結構性不公。`;
            }

            statsDiv.innerHTML = `
                <div class="bg-orange-50 p-4 rounded-xl border border-orange-100 text-orange-700 font-bold">體力: ${stats.time}%</div>
                <div class="bg-red-50 p-4 rounded-xl border border-red-100 text-red-700 font-bold">情緒: ${stats.mental}%</div>
                <div class="bg-emerald-50 p-4 rounded-xl border border-emerald-100 text-emerald-700 font-bold">經濟: ${stats.money}%</div>
                <div class="bg-blue-50 p-4 rounded-xl border border-blue-100 text-blue-700 font-bold">認同: ${stats.growth}%</div>
            `;
        }
    </script>
</body>
</html>
