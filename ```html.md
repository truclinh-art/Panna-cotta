#   
```html  
<!DOCTYPE html>  
<html lang="vi" class="scroll-smooth">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>PannaDelight - Trải Nghiệm Panna Cotta Ý Cao Cấp & Thượng Hạng</title>  
    <!-- Tailwind CSS CDN -->  
    <script src="https://cdn.tailwindcss.com"></script>  
    <!-- Google Fonts -->  
    <link rel="preconnect" href="https://fonts.googleapis.com">  
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">  
  
    <style>  
        body {  
            font-family: 'Plus Jakarta Sans', sans-serif;  
            background-color: #fffdfa; /* Nền kem sữa ấm áp dồi dào cảm xúc */  
        }  
        .font-serif {  
            font-family: 'Playfair Display', serif;  
        }  
        /* Hiệu ứng kính mờ sang trọng */  
        .glass-premium {  
            background: rgba(255, 255, 255, 0.85);  
            backdrop-filter: blur(16px);  
            -webkit-backdrop-filter: blur(16px);  
            border-bottom: 1px solid rgba(251, 191, 36, 0.15);  
        }  
        /* Cốc thủy tinh 3D mượt mà cho phần Custom Mixer */  
        .premium-glass {  
            position: relative;  
            width: 90px;  
            height: 120px;  
            border: 4px solid rgba(255, 255, 255, 0.9);  
            border-top: none;  
            border-radius: 0 0 30px 30px;  
            display: flex;  
            flex-direction: column;  
            justify-content: flex-end;  
            overflow: hidden;  
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0.05));  
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.05), inset 0 0 15px rgba(255, 255, 255, 0.6);  
        }  
        .pudding-fluid {  
            height: 65px;  
            background-color: #fcfaf2;  
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);  
        }  
        .syrup-fluid {  
            height: 22px;  
            background-color: #f43f5e;  
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);  
        }  
    </style>  
</head>  
<body class="text-stone-800 antialiased selection:bg-amber-100">  
  
    <!-- THANH MENU DIỀU HƯỚNG SANG TRỌNG -->  
    <header class="sticky top-0 z-50 glass-premium shadow-sm">  
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">  
            <!-- Logo -->  
            <a href="#" class="flex items-center gap-2">  
                <span class="text-2xl font-serif font-black text-amber-900 tracking-wider">PannaDelight</span>  
            </a>  
              
            <!-- Menu liên kết -->  
            <nav class="hidden md:flex space-x-10 font-bold text-xs tracking-widest uppercase text-stone-600">  
                <a href="#gioi-thieu" class="hover:text-amber-800 transition duration-300">Câu chuyện</a>  
                <a href="#menu" class="hover:text-amber-800 transition duration-300">Thực đơn</a>  
                <a href="#tu-phoi-vi" class="hover:text-amber-800 transition duration-300">Tự phối vị</a>  
                <a href="#cam-nhan" class="hover:text-amber-800 transition duration-300">Đánh giá</a>  
            </nav>  
  
            <!-- CTA mua nhanh -->  
            <a href="#tu-phoi-vi" class="bg-amber-800 hover:bg-amber-950 text-white px-6 py-2.5 rounded-full text-xs font-bold tracking-widest uppercase transition-all duration-300 hover:shadow-md active:scale-95">  
                Thiết Kế Vị Bánh  
            </a>  
        </div>  
    </header>  
  
    <!-- HERO SECTION - KHƠI GỢI CẢM XÚC ẨM THỰC -->  
    <section class="relative min-h-[85vh] flex items-center justify-center px-6 overflow-hidden">  
        <!-- Nền mờ nghệ thuật -->  
        <div class="absolute -top-40 -left-40 w-96 h-96 bg-amber-100 rounded-full blur-3xl opacity-60"></div>  
        <div class="absolute bottom-10 -right-20 w-96 h-96 bg-rose-100 rounded-full blur-3xl opacity-50"></div>  
  
        <div class="max-w-4xl text-center space-y-8 relative z-10">  
            <span class="inline-flex items-center gap-2 bg-amber-50 border border-amber-200 text-amber-950 text-[10px] font-black uppercase tracking-widest px-4 py-1.5 rounded-full">  
                ✨ Món Tráng Miệng Tan Chảy Từ Nước Ý  
            </span>  
              
            <h1 class="text-5xl md:text-7xl font-serif font-bold text-stone-900 leading-tight">  
                Vị béo mịn <span class="text-amber-800 italic">quyến rũ</span> <br class="hidden md:inline">ngọt thanh tan chậm  
            </h1>  
              
            <p class="text-base md:text-lg text-stone-600 max-w-2xl mx-auto leading-relaxed">  
                Tại PannaDelight, mỗi hũ Panna Cotta là kết tinh của dòng kem sữa hảo hạng nguyên chất, sáp gelatin dẻo mềm rúng rính cùng lớp sốt mứt sên từ quả tươi mọng. Ít ngọt hơn, mát lành hơn.  
            </p>  
  
            <div class="pt-4 flex flex-col sm:flex-row justify-center gap-4">  
                <a href="#menu" class="bg-amber-800 hover:bg-amber-900 text-white text-xs font-bold uppercase tracking-widest px-10 py-4 rounded-xl shadow-lg transition-all duration-300 hover:-translate-y-0.5">  
                    Khám phá thực đơn  
                </a>  
                <a href="#tu-phoi-vi" class="bg-white hover:bg-stone-50 text-stone-800 text-xs font-bold uppercase tracking-widest px-10 py-4 rounded-xl border border-stone-200 shadow-sm transition-all duration-300 hover:-translate-y-0.5">  
                    Tự tay mix vị hũ bánh  
                </a>  
            </div>  
        </div>  
    </section>  
  
    <!-- CÂU CHUYỆN & ĐIỂM KHÁC BIỆT THƯƠNG HIỆU -->  
    <section id="gioi-thieu" class="max-w-6xl mx-auto px-6 py-20 border-t border-amber-100/50">  
        <div class="text-center max-w-2xl mx-auto mb-16 space-y-3">  
            <span class="text-amber-800 text-xs font-black uppercase tracking-widest">Triết Lý PannaDelight</span>  
            <h2 class="text-3xl md:text-4xl font-serif font-bold text-stone-900">Nghệ Thuật Làm Bánh Bằng Cả Trái Tim</h2>  
            <div class="h-0.5 w-16 bg-amber-800 mx-auto mt-4"></div>  
        </div>  
  
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">  
            <!-- Card 1 -->  
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-stone-100 hover:shadow-md transition-all duration-300 space-y-4">  
                <div class="w-14 h-14 bg-amber-50 rounded-xl flex items-center justify-center text-amber-800 text-2xl font-bold">🥛</div>  
                <h3 class="text-lg font-bold text-stone-900">Kem Sữa Thượng Hạng</h3>  
                <p class="text-stone-600 text-sm leading-relaxed">Nói không với bột sữa pha hay phụ gia nhân tạo. Chúng tôi chỉ sử dụng kem tươi Whipping Cream đắt đỏ để có cấu trúc rúng rính mướt mịn nguyên bản.</p>  
            </div>  
              
            <!-- Card 2 -->  
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-stone-100 hover:shadow-md transition-all duration-300 space-y-4">  
                <div class="w-14 h-14 bg-rose-50 rounded-xl flex items-center justify-center text-rose-600 text-2xl font-bold">🍓</div>  
                <h3 class="text-lg font-bold text-stone-900">Sốt Trái Cây Tự Sên</h3>  
                <p class="text-stone-600 text-sm leading-relaxed">Từng mẻ dâu tây Đà Lạt chín ngọt, xoài cát mọng nước hay việt quất tươi đều được sên tỉ mỉ mỗi sáng để giữ trọn vị thanh sảng khoái của quả mọng tự nhiên.</p>  
            </div>  
  
            <!-- Card 3 -->  
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-stone-100 hover:shadow-md transition-all duration-300 space-y-4">  
                <div class="w-14 h-14 bg-emerald-50 rounded-xl flex items-center justify-center text-emerald-700 text-2xl font-bold">🌱</div>  
                <h3 class="text-lg font-bold text-stone-900">Công Thức Ít Đường</h3>  
                <p class="text-stone-600 text-sm leading-relaxed">Giảm thiểu tới 40% lượng đường để bảo vệ vóc dáng và sức khỏe của bạn. Mang lại hậu vị ngọt nhẹ êm dịu, không hề bị khé hay gắt cổ họng.</p>  
            </div>  
        </div>  
    </section>  
  
    <!-- THỰC ĐƠN HƯƠNG VỊ CAO CẤP -->  
    <section id="menu" class="bg-stone-950 text-stone-200 py-24 px-6 rounded-[3rem] mx-4 my-8">  
        <div class="max-w-6xl mx-auto">  
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 border-b border-stone-800 pb-8">  
                <div>  
                    <span class="text-amber-400 text-xs font-black uppercase tracking-widest">Tuyển Chọn Tốt Nhất</span>  
                    <h2 class="text-3xl md:text-5xl font-serif font-bold text-white mt-2">Bốn Hương Vị Trứ Danh</h2>  
                </div>  
                <p class="text-stone-400 max-w-sm text-sm mt-4 md:mt-0 leading-relaxed">  
                    Sự kết hợp hoàn mỹ giữa kem béo ngọt dịu cùng lớp sốt quả sặc sỡ quyến rũ vị giác của bạn ngay từ muỗng đầu tiên.  
                </p>  
            </div>  
  
            <!-- Menu Grid -->  
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">  
                  
                <!-- Bánh 1 -->  
                <div class="bg-stone-900 rounded-3xl overflow-hidden border border-stone-800/80 group transition duration-300 hover:border-amber-500/30">  
                    <div class="h-56 bg-gradient-to-br from-rose-900/40 to-stone-950 flex items-center justify-center relative overflow-hidden text-5xl">  
                        <!-- Quả dâu vẽ SVG tối giản -->  
                        <span class="z-10 group-hover:scale-110 transition duration-500">🍓</span>  
                        <div class="absolute bottom-2 right-2 bg-rose-500/10 text-rose-400 text-[10px] font-black uppercase px-2.5 py-1 rounded">Bán Chạy</div>  
                    </div>  
                    <div class="p-6 space-y-3">  
                        <h3 class="font-bold text-lg text-white">Sốt Dâu Tây Đà Lạt</h3>  
                        <p class="text-stone-400 text-xs leading-relaxed">Mứt sốt ngọt dịu xen chút vị chua nhẹ mơn man đầu lưỡi, vô cùng kích thích cảm xúc dồi dào quả mọng.</p>  
                        <div class="flex justify-between items-center pt-2 border-t border-stone-800">  
                            <span class="text-amber-400 font-extrabold text-base">35.000 đ</span>  
                            <a href="#dat-hang-nhanh" onclick="autoSelectFlavor('strawberry')" class="text-[10px] uppercase font-bold text-amber-200 bg-amber-500/10 hover:bg-amber-500 hover:text-stone-950 px-3 py-1.5 rounded-lg transition duration-300">Đặt ngay</a>  
                        </div>  
                    </div>  
                </div>  
  
                <!-- Bánh 2 -->  
                <div class="bg-stone-900 rounded-3xl overflow-hidden border border-stone-800/80 group transition duration-300 hover:border-amber-500/30">  
                    <div class="h-56 bg-gradient-to-br from-amber-900/40 to-stone-950 flex items-center justify-center relative overflow-hidden text-5xl">  
                        <!-- Quả xoài -->  
                        <span class="z-10 group-hover:scale-110 transition duration-500">🥭</span>  
                        <div class="absolute bottom-2 right-2 bg-amber-500/10 text-amber-400 text-[10px] font-black uppercase px-2.5 py-1 rounded">Yêu Thích</div>  
                    </div>  
                    <div class="p-6 space-y-3">  
                        <h3 class="font-bold text-lg text-white">Sốt Xoài Cát Hòa Lộc</h3>  
                        <p class="text-stone-400 text-xs leading-relaxed">Màu sốt vàng mượt lấp lánh nồng nàn mứt thơm, đậm sắc ấm áp và dồi dào vitamin từ thiên nhiên Nam Bộ.</p>  
                        <div class="flex justify-between items-center pt-2 border-t border-stone-800">  
                            <span class="text-amber-400 font-extrabold text-base">35.000 đ</span>  
                            <a href="#dat-hang-nhanh" onclick="autoSelectFlavor('mango')" class="text-[10px] uppercase font-bold text-amber-200 bg-amber-500/10 hover:bg-amber-50 hover:text-stone-950 px-3 py-1.5 rounded-lg transition duration-300">Đặt ngay</a>  
                        </div>  
                    </div>  
                </div>  
  
                <!-- Bánh 3 -->  
                <div class="bg-stone-900 rounded-3xl overflow-hidden border border-stone-800/80 group transition duration-300 hover:border-amber-500/30">  
                    <div class="h-56 bg-gradient-to-br from-emerald-900/40 to-stone-950 flex items-center justify-center relative overflow-hidden text-5xl">  
                        <!-- Matcha -->  
                        <span class="z-10 group-hover:scale-110 transition duration-500">🍵</span>  
                        <div class="absolute bottom-2 right-2 bg-emerald-500/10 text-emerald-400 text-[10px] font-black uppercase px-2.5 py-1 rounded">Đậm Đà</div>  
                    </div>  
                    <div class="p-6 space-y-3">  
                        <h3 class="font-bold text-lg text-white">Matcha Uji Nhật Bản</h3>  
                        <p class="text-stone-400 text-xs leading-relaxed">Cảm giác chát dịu đặc trưng hòa quyện hoàn hảo vào độ béo tinh khôi, khơi dậy vị giác thanh mát mê say.</p>  
                        <div class="flex justify-between items-center pt-2 border-t border-stone-800">  
                            <span class="text-amber-400 font-extrabold text-base">38.000 đ</span>  
                            <a href="#dat-hang-nhanh" onclick="autoSelectFlavor('matcha')" class="text-[10px] uppercase font-bold text-amber-200 bg-amber-500/10 hover:bg-amber-500 hover:text-stone-950 px-3 py-1.5 rounded-lg transition duration-300">Đặt ngay</a>  
                        </div>  
                    </div>  
                </div>  
  
                <!-- Bánh 4 -->  
                <div class="bg-stone-900 rounded-3xl overflow-hidden border border-stone-800/80 group transition duration-300 hover:border-amber-500/30">  
                    <div class="h-56 bg-gradient-to-br from-indigo-900/40 to-stone-950 flex items-center justify-center relative overflow-hidden text-5xl">  
                        <!-- Việt quất -->  
                        <span class="z-10 group-hover:scale-110 transition duration-500">🫐</span>  
                        <div class="absolute bottom-2 right-2 bg-indigo-500/10 text-indigo-400 text-[10px] font-black uppercase px-2.5 py-1 rounded">Mới Lạ</div>  
                    </div>  
                    <div class="p-6 space-y-3">  
                        <h3 class="font-bold text-lg text-white">Sốt Việt Quất Thượng Hạng</h3>  
                        <p class="text-stone-400 text-xs leading-relaxed">Chua chua ngọt ngọt quyến rũ mê li từ những quả việt quất nhập khẩu nguyên hạt căng tràn mọng nước.</p>  
                        <div class="flex justify-between items-center pt-2 border-t border-stone-800">  
                            <span class="text-amber-400 font-extrabold text-base">38.000 đ</span>  
                            <a href="#dat-hang-nhanh" onclick="autoSelectFlavor('blueberry')" class="text-[10px] uppercase font-bold text-amber-200 bg-amber-500/10 hover:bg-amber-500 hover:text-stone-950 px-3 py-1.5 rounded-lg transition duration-300">Đặt ngay</a>  
                        </div>  
                    </div>  
                </div>  
  
            </div>  
        </div>  
    </section>  
  
    <!-- TỰ MIX VỊ LY PANNA COTTA CỦA RIÊNG BẠN (TƯƠNG TÁC CUSTOM MIXER) -->  
    <section id="tu-phoi-vi" class="max-w-4xl mx-auto px-6 py-20">  
        <div class="bg-gradient-to-br from-amber-900 to-amber-950 text-white rounded-3xl p-8 md:p-12 shadow-2xl relative overflow-hidden">  
            <div class="absolute top-0 right-0 w-64 h-64 bg-amber-500/10 rounded-full blur-2xl"></div>  
  
            <div class="grid grid-cols-1 md:grid-cols-2 gap-10 items-center">  
                <!-- Cột trái: Ly nước chuyển đổi màu sắc trực tiếp cực đẹp -->  
                <div class="flex flex-col items-center space-y-6">  
                    <h3 class="font-serif font-bold text-2xl text-center text-amber-100">Hũ Bánh Mô Phỏng</h3>  
                      
                    <!-- Ly thủy tinh DIY -->  
                    <div class="relative w-32 h-40 flex justify-center items-end bg-black/10 rounded-3xl p-4 border border-white/5">  
                          
                        <!-- Lớp thạch kem pudding -->  
                        <div id="puddingVisual" class="absolute bottom-4 w-[66px] h-[60px] rounded-b-[18px] bg-[#faf6f0] transition-all duration-500 z-10 shadow-inner"></div>  
                          
                        <!-- Lớp sốt trái cây rực rỡ ở trên -->  
                        <div id="syrupVisual" class="absolute bottom-[64px] w-[72px] h-[18px] bg-rose-500 transition-all duration-500 z-10 opacity-90"></div>  
                          
                        <!-- Quả mọng và lá bạc hà topping -->  
                        <div class="absolute bottom-[82px] flex justify-center items-center w-full z-20">  
                            <span class="text-xl transform -rotate-12 animate-pulse">🍃</span>  
                            <span id="toppingFruitEmoji" class="text-xl -ml-1">🍓</span>  
                        </div>  
  
                        <!-- Cốc thuỷ tinh vẽ SVG sắc xảo chồng lên trên -->  
                        <svg class="absolute bottom-1 w-28 h-36 drop-shadow-xl z-30 pointer-events-none" viewBox="0 0 100 120" fill="none" xmlns="http://www.w3.org/2000/svg">  
                            <path d="M15 10 L25 105 A 6 6 0 0 0 31 111 L69 111 A 6 6 0 0 0 75 105 L85 10" stroke="rgba(255,255,255,0.85)" stroke-width="4" stroke-linecap="round" fill="none"/>  
                            <path d="M22 15 L28 85" stroke="rgba(255,255,255,0.25)" stroke-width="1.5"/>  
                        </svg>  
                    </div>  
  
                    <p class="text-center text-[11px] text-amber-200/80 italic max-w-xs">  
                        Thay đổi hương vị ở bảng bên cạnh để chiêm ngưỡng tuyệt tác của bạn trực quan tức thì!  
                    </p>  
                </div>  
  
                <!-- Cột phải: Bộ chọn vị -->  
                <div class="space-y-6">  
                    <div class="space-y-1">  
                        <span class="text-xs text-amber-400 font-black uppercase tracking-widest">Sáng tạo hương vị</span>  
                        <h4 class="text-2xl font-bold font-serif text-white">Tự Mix Ly Hạnh Phúc</h4>  
                        <p class="text-xs text-amber-200/70">Tự phối hương vị lớp nền thạch và nước sốt thơm phức theo đúng gu ẩm thực của riêng mình.</p>  
                    </div>  
  
                    <div class="space-y-4 text-xs">  
                        <!-- Chọn mứt sốt -->  
                        <div class="space-y-1.5">  
                            <label class="font-bold text-amber-200 block">Lớp sốt quả rạng ngời:</label>  
                            <select id="syrupSelect" onchange="updateCustomPannaCotta()" class="w-full bg-white/10 text-white font-bold p-3 rounded-xl border border-white/20 focus:outline-none focus:border-amber-400">  
                                <option class="text-stone-900 font-semibold" value="strawberry">🍓 Sốt Dâu Tây Đỏ Mọng (Mặc định)</option>  
                                <option class="text-stone-900 font-semibold" value="mango">🥭 Sốt Xoài Cát Vàng Thơm</option>  
                                <option class="text-stone-900 font-semibold" value="matcha">🍵 Sốt Matcha Trà Xanh</option>  
                                <option class="text-stone-900 font-semibold" value="blueberry">🫐 Sốt Việt Quất Thượng Hạng</option>  
                            </select>  
                        </div>  
  
                        <!-- Chọn thạch thô nền -->  
                        <div class="space-y-1.5">  
                            <label class="font-bold text-amber-200 block">Nền thạch đông kem sữa:</label>  
                            <select id="puddingSelect" onchange="updateCustomPannaCotta()" class="w-full bg-white/10 text-white font-bold p-3 rounded-xl border border-white/20 focus:outline-none focus:border-amber-400">  
                                <option class="text-stone-900 font-semibold" value="vanilla">🥛 Vani Sữa Truyền Thống</option>  
                                <option class="text-stone-900 font-semibold" value="matcha_pud">🍵 Matcha Uji Nhật Bản</option>  
                                <option class="text-stone-900 font-semibold" value="chocolate">🍫 Sô-cô-la Bỉ Đậm Đà</option>  
                            </select>  
                        </div>  
                    </div>  
  
                    <button onclick="orderCustomMix()" class="w-full py-4 bg-white text-amber-950 hover:bg-amber-50 active:scale-[0.98] transition font-black rounded-xl text-xs uppercase tracking-wider shadow-lg">  
                        ⚡ Đặt Giao Ngay Hương Vị Này  
                    </button>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <!-- CẢM NHẬN KHÁCH HÀNG THỰC TẾ -->  
    <section id="cam-nhan" class="max-w-6xl mx-auto px-6 py-12">  
        <div class="text-center max-w-2xl mx-auto mb-16 space-y-2">  
            <span class="text-amber-800 text-xs font-black uppercase tracking-widest">Đánh Giá Thực Tế</span>  
            <h2 class="text-3xl md:text-4xl font-serif font-bold text-stone-900">Những Chia Sẻ Đầy Yêu Thương</h2>  
            <div class="h-0.5 w-16 bg-amber-800 mx-auto mt-4"></div>  
        </div>  
  
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">  
            <div class="bg-white p-8 rounded-3xl shadow-sm border border-stone-150 space-y-4 relative">  
                <span class="text-5xl text-amber-100 font-serif absolute top-4 left-4 pointer-events-none">“</span>  
                <div class="flex text-amber-500 text-sm">★★★★★</div>  
                <p class="text-stone-600 text-sm italic relative z-10 leading-relaxed">  
                    "Bánh panna cotta của PannaDelight siêu ngon và mịn mịn dẻo mềm rúng rính. Đổ ra dĩa múa lắc thích cực kỳ. Thích nhất là mứt quả chua ngọt tự nhiên sên chất lượng chứ không phải hương liệu ngọt gắt hóa chất."  
                </p>  
                <div class="font-bold text-xs text-stone-900">— Minh Thư (Q. Bình Thạnh, TP.HCM)</div>  
            </div>  
  
            <div class="bg-white p-8 rounded-3xl shadow-sm border border-stone-150 space-y-4 relative">  
                <span class="text-5xl text-amber-100 font-serif absolute top-4 left-4 pointer-events-none">“</span>  
                <div class="flex text-amber-500 text-sm">★★★★★</div>  
                <p class="text-stone-600 text-sm italic relative z-10 leading-relaxed">  
                    "Cả văn phòng mình đều là fan cứng ở đây. Bánh ít ngọt nhẹ nhàng nên ăn không sợ ngấy hay mập bụng. Đóng gói chỉn chu, có đá gel đi kèm bảo quản giao mát lạnh."  
                </p>  
                <div class="font-bold text-xs text-stone-900">— Anh Vũ (Quận 1, TP.HCM)</div>  
            </div>  
        </div>  
    </section>  
  
    <!-- FORM ĐẶT HÀNG NHANH GIAO HOẢ TỐC -->  
    <section id="dat-hang-nhanh" class="bg-amber-900 text-white py-20 px-6 rounded-[3rem] mx-4 my-8">  
        <div class="max-w-md mx-auto text-center space-y-6">  
            <div class="space-y-2">  
                <span class="text-amber-300 text-xs font-black uppercase tracking-widest">Ship Hỏa Tốc Sài Gòn</span>  
                <h2 class="text-3xl font-serif font-bold">Đặt Mua Nhanh Giao 1H</h2>  
                <p class="text-amber-100 text-xs">Vui lòng điền thông tin bên dưới, nhân viên hỗ trợ sẽ gọi xác nhận đơn và giao ngay sau 1 giờ mát lạnh.</p>  
            </div>  
  
            <form onsubmit="handleCheckoutForm(event)" class="text-left space-y-4">  
                <div>  
                    <label class="block text-[10px] font-bold text-amber-200 uppercase tracking-widest mb-1.5">Họ và tên khách hàng</label>  
                    <input id="formName" type="text" placeholder="Ví dụ: Nguyễn Thị Lan Anh" required class="w-full text-xs p-3.5 rounded-xl bg-amber-950/40 border border-amber-700/60 text-white placeholder-amber-200/30 focus:outline-none focus:border-white focus:ring-1 focus:ring-white">  
                </div>  
                <div>  
                    <label class="block text-[10px] font-bold text-amber-200 uppercase tracking-widest mb-1.5">Số điện thoại giao hàng</label>  
                    <input id="formPhone" type="tel" placeholder="Ví dụ: 0901234567" required class="w-full text-xs p-3.5 rounded-xl bg-amber-950/40 border border-amber-700/60 text-white placeholder-amber-200/30 focus:outline-none focus:border-white focus:ring-1 focus:ring-white">  
                </div>  
                <div>  
                    <label class="block text-[10px] font-bold text-amber-200 uppercase tracking-widest mb-1.5">Địa chỉ giao hàng nhận bánh</label>  
                    <input id="formAddress" type="text" placeholder="Ví dụ: 120 Điện Biên Phủ, Quận 1" required class="w-full text-xs p-3.5 rounded-xl bg-amber-950/40 border border-amber-700/60 text-white placeholder-amber-200/30 focus:outline-none focus:border-white focus:ring-1 focus:ring-white">  
                </div>  
                <div>  
                    <label class="block text-[10px] font-bold text-amber-200 uppercase tracking-widest mb-1.5">Hương vị lựa chọn</label>  
                    <select id="formFlavor" class="w-full text-xs p-3.5 rounded-xl bg-amber-950 text-white border border-amber-700/60 focus:outline-none">  
                        <option value="strawberry">🍓 Hũ Panna Cotta Sốt Dâu Tây Đà Lạt (35k)</option>  
                        <option value="mango">🥭 Hũ Panna Cotta Sốt Xoài Cát Hòa Lộc (35k)</option>  
                        <option value="matcha">🍵 Hũ Panna Cotta Matcha Nhật Bản (38k)</option>  
                        <option value="blueberry">🫐 Hũ Panna Cotta Sốt Việt Quất Thượng Hạng (38k)</option>  
                        <option value="combo">🎁 Combo Mix Thử Cả 4 Vị (Ưu đãi 140k)</option>  
                    </select>  
                </div>  
  
                <button type="submit" class="w-full py-4 bg-white text-amber-950 hover:bg-amber-50 active:scale-[0.98] transition font-black rounded-xl text-xs uppercase tracking-widest shadow-md">  
                    ⚡ Xác Nhận Đơn Hàng Ngay  
                </button>  
            </form>  
        </div>  
    </section>  
  
    <!-- FOOTER CHÂN TRANG -->  
    <footer class="bg-stone-900 text-stone-400 text-xs py-12 px-6">  
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-6">  
            <div class="text-center md:text-left space-y-1.5">  
                <p class="font-bold text-stone-200 text-sm tracking-wider font-serif">PannaDelight - Hương Vị Từ Hũ Sữa Ý</p>  
                <p class="text-stone-500">Mở cửa phục vụ giao bánh từ: 8:00 - 21:30 hàng ngày (kể cả lễ tết)</p>  
                <p class="text-[10px] text-stone-600">Trải nghiệm sảng khoái với cam kết sạch ngon 100% không hoá chất phụ gia.</p>  
            </div>  
            <div class="text-stone-500 text-[10px] text-center md:text-right">  
                <p>&copy; 2026 PannaDelight Corporation. All rights reserved.</p>  
                <p class="mt-1 text-stone-600">Nền tảng ẩm thực làm mát mẻ tâm hồn hảo ngọt.</p>  
            </div>  
        </div>  
    </footer>  
  
    <!-- POPUP THÔNG BÁO THÀNH CÔNG (MODAL TIỆN LỢI - NO BROWSER ALERT) -->  
    <div id="successModal" class="fixed inset-0 bg-black/60 backdrop-blur-md z-50 flex items-center justify-center hidden px-4">  
        <div class="bg-white rounded-[2rem] p-8 max-w-sm w-full shadow-2xl border border-amber-100 text-center space-y-5 transform scale-95 transition-all duration-300">  
            <div class="w-16 h-16 bg-emerald-100 text-emerald-600 rounded-full flex items-center justify-center mx-auto text-3xl font-bold">  
                ✓  
            </div>  
            <div class="space-y-1">  
                <h4 class="font-black text-xl text-stone-900">Nhận đơn hàng!</h4>  
                <p class="text-xs text-stone-500">PannaDelight đang chuẩn bị những ly bánh mát lạnh nhất cho bạn.</p>  
            </div>  
              
            <div class="bg-stone-50 p-4 rounded-2xl text-left text-xs text-stone-600 space-y-2 border border-stone-150">  
                <p>• <strong>Khách hàng:</strong> <span id="modalName" class="font-bold text-stone-800">-</span></p>  
                <p>• <strong>Số điện thoại:</strong> <span id="modalPhone" class="font-bold text-stone-800">-</span></p>  
                <p>• <strong>Sản phẩm:</strong> <span id="modalFlavor" class="font-bold text-stone-800">-</span></p>  
                <p class="text-amber-800 font-bold mt-2 text-center text-[10px] bg-amber-50 py-1.5 rounded-lg border border-amber-100">🛵 Giao hỏa tốc lạnh ngay trong 1 giờ!</p>  
            </div>  
  
            <button onclick="closeSuccessModal()" class="w-full py-3 bg-stone-900 hover:bg-stone-800 text-white font-bold rounded-xl text-xs transition duration-300 shadow-sm">  
                Tuyệt Vời & Đóng  
            </button>  
        </div>  
    </div>  
  
    <!-- JAVASCRIPT XỬ LÝ HOẠT ĐỘNG TƯƠNG TÁC ĐỘNG -->  
    <script>  
        // Cập nhật cốc thuỷ tinh đổi hương vị khi người dùng chọn trong Custom Mixer  
        function updateCustomPannaCotta() {  
            const syrupVal = document.getElementById('syrupSelect').value;  
            const puddingVal = document.getElementById('puddingSelect').value;  
  
            const syrupVisual = document.getElementById('syrupVisual');  
            const puddingVisual = document.getElementById('puddingVisual');  
            const toppingFruitEmoji = document.getElementById('toppingFruitEmoji');  
  
            // Cập nhật lớp mứt phủ trái cây  
            if (syrupVal === 'strawberry') {  
                syrupVisual.style.backgroundColor = '#f43f5e'; // Hồng đỏ dâu  
                toppingFruitEmoji.textContent = '🍓';  
            } else if (syrupVal === 'mango') {  
                syrupVisual.style.backgroundColor = '#fb923c'; // Vàng xoài cát  
                toppingFruitEmoji.textContent = '🥭';  
            } else if (syrupVal === 'matcha') {  
                syrupVisual.style.backgroundColor = '#10b981'; // Xanh Matcha đậm  
                toppingFruitEmoji.textContent = '🍵';  
            } else if (syrupVal === 'blueberry') {  
                syrupVisual.style.backgroundColor = '#4f46e5'; // Xanh việt quất sẫm  
                toppingFruitEmoji.textContent = '🫐';  
            }  
  
            // Cập nhật lớp thạch thô pudding kem sữa sữa bên dưới  
            if (puddingVal === 'vanilla') {  
                puddingVisual.style.backgroundColor = '#faf6f0'; // Vani kem sữa  
            } else if (puddingVal === 'matcha_pud') {  
                puddingVisual.style.backgroundColor = '#bbf7d0'; // Trà xanh Matcha nhẹ sữa  
            } else if (puddingVal === 'chocolate') {  
                puddingVisual.style.backgroundColor = '#854d0e'; // Sô cô la đầm ấm  
            }  
        }  
  
        // Tự động ghim hương vị từ menu xuống form đặt hàng dưới  
        function autoSelectFlavor(flavor) {  
            const formFlavor = document.getElementById('formFlavor');  
            formFlavor.value = flavor;  
        }  
  
        // Người dùng đặt hương vị tự phối của họ  
        function orderCustomMix() {  
            const syrupSelect = document.getElementById('syrupSelect');  
            const puddingSelect = document.getElementById('puddingSelect');  
  
            const txtSyrup = syrupSelect.options[syrupSelect.selectedIndex].text;  
            const txtPudding = puddingSelect.options[puddingSelect.selectedIndex].text;  
  
            // Đồng bộ sang form dưới và cuộn đến khu đặt hàng  
            const formFlavor = document.getElementById('formFlavor');  
              
            // Tìm sự tương đồng để đổi giá trị của form  
            formFlavor.value = syrupSelect.value;  
              
            // Cuộn mượt mà  
            document.getElementById('dat-hang-nhanh').scrollIntoView({ behavior: 'smooth' });  
        }  
  
        // Xử lý gửi biểu mẫu thanh toán nhanh  
        function handleCheckoutForm(event) {  
            event.preventDefault();  
  
            const name = document.getElementById('formName').value;  
            const phone = document.getElementById('formPhone').value;  
            const flavorSelect = document.getElementById('formFlavor');  
            const flavorText = flavorSelect.options[flavorSelect.selectedIndex].text;  
  
            // Truyền dữ liệu lên Modal  
            document.getElementById('modalName').textContent = name;  
            document.getElementById('modalPhone').textContent = phone;  
            document.getElementById('modalFlavor').textContent = flavorText;  
  
            // Mở modal  
            const modal = document.getElementById('successModal');  
            modal.classList.remove('hidden');  
            setTimeout(() => {  
                modal.firstElementChild.classList.remove('scale-95');  
                modal.firstElementChild.classList.add('scale-100');  
            }, 50);  
        }  
  
        // Đóng Popup thông báo thành công  
        function closeSuccessModal() {  
            const modal = document.getElementById('successModal');  
            modal.firstElementChild.classList.remove('scale-100');  
            modal.firstElementChild.classList.add('scale-95');  
            setTimeout(() => {  
                modal.classList.add('hidden');  
            }, 150);  
  
            // Làm mới form nhập liệu sau khi gửi thành công  
            document.getElementById('formName').value = '';  
            document.getElementById('formPhone').value = '';  
            document.getElementById('formAddress').value = '';  
        }  
  
        // Khởi động giao diện ly Panna Cotta ban đầu đúng sắc thái mặc định  
        updateCustomPannaCotta();  
    </script>  
</body>  
</html>  
  
```  
