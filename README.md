<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>lifecolor.com - Life Color Quà Tặng Doanh Nghiệp & Khắc Laser Đà Nẵng</title>
    <meta name="description" content="Life Color (lifecolor.com) - Chuyên cung cấp Quà Tặng Doanh Nghiệp, Bình Giữ Nhiệt, Sổ Tay, Bút Ký, Bộ Giftset In Khắc Laser Logo Theo Yêu Cầu tại Trần Cao Vân, Thanh Khê, Đà Nẵng. Hotline: 0935.828.376">

    <!-- Open Graph Thumbnail là Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://lifecolor.com/">
    <meta property="og:title" content="lifecolor.com - Life Color Quà Tặng Doanh Nghiệp & Khắc Laser Đà Nẵng">
    <meta property="og:description" content="Giải pháp quà tặng in khắc logo nâng tầm thương hiệu tại Đà Nẵng. Địa chỉ: Trần Cao Vân, Thanh Khê, Đà Nẵng - ĐT: 0935.828.376">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2&sz=w1200">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2&sz=w200">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            blue: '#164e87',      /* Màu xanh thương hiệu chủ đạo theo logo & Flatsome */
                            dark: '#0f355e',
                            light: '#eff6ff',
                            red: '#d92626',       /* Màu đỏ cam điểm nhấn & giảm giá Flatsome */
                            accent: '#f59e0b'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn UX Builder Flatsome: 95% trên máy tính, 100% trên điện thoại */
        .ux-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 10px;
            padding-right: 10px;
        }
        @media (min-width: 1024px) {
            .ux-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng chữ bên trong 1 danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 14px;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            line-height: 1.8;
            transition: color 0.2s ease;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title Container) */
        .flatsome-title-wrap {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 16px;
            padding-bottom: 8px;
            flex-wrap: wrap;
            gap: 8px;
        }
        .flatsome-title-main {
            position: relative;
            font-weight: 700;
            text-transform: uppercase;
            color: #164e87;
            letter-spacing: 0.02em;
        }
        .flatsome-title-main::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #d92626;
        }

        /* Nhãn % Giảm Giá Flatsome góc trên bên trái */
        .flatsome-sale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d92626;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            width: 38px;
            height: 38px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            pointer-events: none;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài khung */
        .product-full-title {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
            display: block;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 38, 38, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 38, 38, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 38, 38, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ================= TOP BAR (Đơn giản chuẩn Flatsome, không có thanh công cụ UX Builder) ================= -->
    <div class="bg-brand-dark text-white text-[11px] md:text-xs py-1.5 border-b border-white/10">
        <div class="ux-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <span class="font-semibold text-amber-300">LIFECOLOR.COM</span>
                <span class="hidden sm:inline text-white/60">|</span>
                <span class="truncate">Quà Tặng Doanh Nghiệp & Cắt Khắc Laser Uy Tín Đà Nẵng</span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-white/90 whitespace-nowrap">
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Trần Cao Vân, Thanh Khê, Đà Nẵng</span>
                <span><i class="fa-solid fa-clock text-amber-400 mr-1"></i>08:00 - 20:00 (T2 - CN)</span>
            </div>
        </div>
    </div>

    <!-- ================= HEADER (Logo gọn nhỏ, Không để nút gọi ngay tránh tràn viền) ================= -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="ux-container py-2.5 flex items-center justify-between gap-2 sm:gap-4">
            
            <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
            <button onclick="toggleMobileDrawer()" aria-label="Menu danh mục" class="lg:hidden p-2 rounded-lg text-brand-blue hover:bg-slate-100 shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>

            <!-- Logo Life Color (Đã chỉnh gọn nhỏ lại) -->
            <a href="#" class="flex items-center gap-2 shrink-0 group">
                <img id="site-logo"
                     src="https://drive.google.com/thumbnail?id=1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2&sz=w400"
                      data-id="1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2"
                     onerror="handleDriveImgError(this, 'Life+Color')"
                     alt="Life Color Logo"
                     class="h-9 sm:h-10 md:h-11 w-auto max-w-[115px] object-contain rounded">
                <div class="hidden sm:block leading-tight">
                    <span class="block font-extrabold text-sm md:text-base text-brand-blue tracking-tight">LIFE COLOR</span>
                    <span class="block text-[10px] text-slate-500 font-medium">lifecolor.com</span>
                </div>
            </a>

            <!-- Ô Tìm Kiếm Sản Phẩm (Giống mẫu quatang3s.vn) -->
            <div class="flex-1 max-w-xl mx-1 sm:mx-3">
                <form onsubmit="handleSearch(event)" class="relative flex items-center w-full">
                    <input id="search-input" type="text"
                           placeholder="Tìm bình giữ nhiệt, sổ da, bút ký, bộ giftset..."
                           class="w-full pl-3 pr-9 py-1.5 sm:py-2 text-xs sm:text-sm bg-slate-50 border border-slate-300 rounded-full focus:outline-none focus:border-brand-blue focus:bg-white">
                    <button type="submit" aria-label="Tìm kiếm" class="absolute right-1.5 w-7 h-7 rounded-full bg-brand-blue text-white flex items-center justify-center hover:bg-brand-dark">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </form>
            </div>

            <!-- Nút Yêu Cầu Báo Giá Nhanh & Giỏ Hàng (Nhỏ gọn, không để số ĐT/nút gọi ngay trên Header) -->
            <div class="flex items-center gap-2 shrink-0">
                <a href="#form-bao-gia" class="hidden md:inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-brand-light text-brand-blue border border-brand-blue/20 text-xs font-semibold hover:bg-brand-blue hover:text-white transition">
                    <i class="fa-solid fa-file-signature"></i>
                    <span>Báo Giá Sỉ</span>
                </a>
                <button onclick="scrollToSection('form-bao-gia')" class="relative p-2 rounded-full bg-slate-100 text-brand-blue hover:bg-brand-blue hover:text-white transition" title="Giỏ hàng báo giá">
                    <i class="fa-solid fa-bag-shopping text-sm sm:text-base"></i>
                    <span id="quote-count" class="absolute -top-1 -right-1 bg-brand-red text-white text-[10px] font-bold w-4 h-4 rounded-full flex items-center justify-center">0</span>
                </button>
            </div>
        </div>

        <!-- Thanh Danh Mục Trên Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc tự xuống hàng 2 nguyên cụm -->
        <nav class="hidden lg:block bg-brand-blue text-white border-t border-brand-dark/30">
            <div class="ux-container py-1.5">
                <ul class="desktop-nav-list">
                    <li><a href="#" onclick="filterCategory('all'); return false;" class="desktop-nav-item text-amber-300 hover:text-white"><i class="fa-solid fa-house mr-1"></i>TRANG CHỦ</a></li>
                    <li><a href="#sec-giftset" class="desktop-nav-item hover:text-amber-300">BỘ GIFT</a></li>
                    <li><a href="#sec-binh-ly" class="desktop-nav-item hover:text-amber-300">BÌNH GIỮ NHIỆT</a></li>
                    <li><a href="#sec-binh-ly" class="desktop-nav-item hover:text-amber-300">LY GIỮ NHIỆT IN LOGO</a></li>
                    <li><a href="#sec-but-so" class="desktop-nav-item hover:text-amber-300">QUÀ TẶNG SỔ TAY</a></li>
                    <li><a href="#sec-but-so" class="desktop-nav-item hover:text-amber-300">QUÀ TẶNG BÚT</a></li>
                    <li><a href="#sec-da-go-laser" class="desktop-nav-item hover:text-amber-300">QUÀ TẶNG DA</a></li>
                    <li><a href="#sec-da-go-laser" class="desktop-nav-item hover:text-amber-300">QUÀ TẶNG GỖ - TRE</a></li>
                    <li><a href="#sec-da-go-laser" class="desktop-nav-item hover:text-amber-300">QUÀ TẶNG IN LOGO</a></li>
                    <li><a href="#sec-da-go-laser" class="desktop-nav-item hover:text-amber-300">DỊCH VỤ SẢN XUẤT & KHẮC LASER</a></li>
                    <li><a href="#sec-doi-tac" class="desktop-nav-item hover:text-amber-300">ĐỐI TÁC</a></li>
                    <li><a href="#sec-tin-tuc" class="desktop-nav-item hover:text-amber-300">TIN TỨC</a></li>
                    <li><a href="#sec-lien-he" class="desktop-nav-item hover:text-amber-300">LIÊN HỆ</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ================= MENU DRAWER TRÊN ĐIỆN THOẠI ================= -->
    <div id="mobile-drawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileDrawer()" class="fixed inset-0 bg-black/50 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[82vw] bg-white h-full shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-brand-blue text-white flex items-center justify-between">
                <span class="font-bold text-sm tracking-wide">DANH MỤC SẢN PHẨM</span>
                <button onclick="toggleMobileDrawer()" class="w-7 h-7 rounded-full bg-white/15 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <ul class="divide-y divide-slate-100 text-xs font-semibold text-slate-700">
                <li><a href="#sec-giftset" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Bộ Gift (Bộ Quà Tặng)</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-binh-ly" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Bình Giữ Nhiệt In Khắc Logo</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-binh-ly" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Ly Giữ Nhiệt In Logo</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-but-so" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Quà Tặng Sổ Tay (Sổ Da, Sổ Giấy)</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-but-so" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Quà Tặng Bút (Bút Kim Loại, Bút Gỗ)</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-da-go-laser" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Quà Tặng Da & Hộp Đựng Namecard</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-da-go-laser" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Quà Tặng Gỗ - Tre & Khắc Laser</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-doi-tac" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Đối Tác Tiêu Biểu</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#form-bao-gia" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50 text-brand-red"><span>Yêu Cầu Báo Giá Nhanh</span><i class="fa-solid fa-angle-right"></i></a></li>
                <li><a href="#sec-tin-tuc" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Tin Tức & Kinh Nghiệm</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
                <li><a href="#sec-lien-he" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50"><span>Bản Đồ & Fanpage Life Color</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
            </ul>
            <div class="mt-auto p-4 bg-slate-50 border-t border-slate-200 text-xs space-y-1.5">
                <p class="font-bold text-brand-blue">LIFE COLOR ĐÀ NẴNG</p>
                <p class="text-slate-600"><i class="fa-solid fa-location-dot text-brand-red mr-1.5"></i>Trần Cao Vân, Thanh Khê, Đà Nẵng</p>
                <p class="text-slate-600"><i class="fa-solid fa-phone text-brand-red mr-1.5"></i>0935.828.376</p>
            </div>
        </div>
    </div>

    <!-- ================= SECTION 1: SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU ================= -->
    <!-- Thiết kế riêng 2 Banner Máy Tính và 2 Banner Điện Thoại khác nhau để tối ưu chữ nhỏ gọn nằm trọn bên trong ảnh -->
    <section class="py-3">
        <div class="ux-container">
            <div class="relative rounded-xl overflow-hidden shadow-md bg-brand-dark">

                <!-- ====== 2 BANNER DÀNH RIÊNG CHO MÁY TÍNH (Kích thước bằng nhau: h-[320px] lg:h-[360px]) ====== -->
                <div class="hidden md:block relative w-full h-[320px] lg:h-[360px]">
                    <!-- Desktop Slide 1 -->
                    <div id="desktop-slide-0" class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-100 flex items-center bg-gradient-to-r from-[#0d2d52] via-[#164e87] to-[#1e6091] px-10 lg:px-14">
                        <div class="w-7/12 text-white pr-6 space-y-2.5">
                            <div class="inline-block bg-amber-400 text-slate-900 font-bold text-xs px-3 py-1 rounded-full">
                                LIFE COLOR - QUÀ TẶNG DOANH NGHIỆP ĐÀ NẴNG
                            </div>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug">
                                GIẢI PHÁP QUÀ TẶNG IN KHẮC LOGO<br>NÂNG TẦM THƯƠNG HIỆU DOANH NGHIỆP
                            </h1>
                            <p class="text-xs lg:text-sm text-sky-100 max-w-xl leading-relaxed">
                                Chuyên sản xuất Bộ Giftset, Bình Giữ Nhiệt, Ly Giữ Nhiệt, Sổ Da, Bút Ký & Gia Công Cắt Khắc Laser sắc nét theo yêu cầu tại Đà Nẵng. Hỗ trợ thiết kế miễn phí – Giao hàng đúng hẹn.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#form-bao-gia" class="bg-brand-red hover:bg-red-700 text-white font-bold px-4 py-2 rounded-lg shadow transition">
                                    NHẬN BÁO GIÁ SỈ NGAY
                                </a>
                                <span class="bg-white/10 border border-white/20 px-3 py-2 rounded-lg font-medium">
                                    <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>Trần Cao Vân, Thanh Khê, Đà Nẵng | ĐT: 0935.828.376
                                </span>
                            </div>
                        </div>
                        <div class="w-5/12 grid grid-cols-2 gap-3">
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g&sz=w600"
                                     data-id="14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g"
                                     onerror="handleDriveImgError(this, 'Giftset+LifeColor')"
                                     alt="Bộ Giftset Quà Tặng" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=1KPyRzcOTVW819K_coUk2xwZFF8z-Ukwe&sz=w600"
                                     data-id="1KPyRzcOTVW819K_coUk2xwZFF8z-Ukwe"
                                     onerror="handleDriveImgError(this, 'Binh+Giu+Nhiet')"
                                     alt="Bình Giữ Nhiệt In Logo" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N&sz=w600"
                                     data-id="1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N"
                                     onerror="handleDriveImgError(this, 'So+Da+But+Ky')"
                                     alt="Sổ Tay Bút Ký" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=13nKX5wxl4FakMOYREVDpeRllQ3mMRVmW&sz=w600"
                                     data-id="13nKX5wxl4FakMOYREVDpeRllQ3mMRVmW"
                                     onerror="handleDriveImgError(this, 'Khac+Laser')"
                                     alt="Khắc Laser Theo Yêu Cầu" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                        </div>
                    </div>

                    <!-- Desktop Slide 2 -->
                    <div id="desktop-slide-1" class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none flex items-center bg-gradient-to-r from-[#581c1c] via-[#991b1b] to-[#b91c1c] px-10 lg:px-14">
                        <div class="w-7/12 text-white pr-6 space-y-2.5">
                            <div class="inline-block bg-white text-brand-red font-bold text-xs px-3 py-1 rounded-full">
                                XƯỞNG KHẮC LASER & IN ẤN QUÀ TẶNG TRỰC TIẾP
                            </div>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug">
                                ƯU ĐÃI ĐẶT HÀNG SỐ LƯỢNG LỚN<br>CHIẾT KHẤU LÊN ĐẾN 25% CHO ĐỐI TÁC
                            </h2>
                            <p class="text-xs lg:text-sm text-rose-100 max-w-xl leading-relaxed">
                                Nhận gia công khắc laser kim loại, gỗ, tre, da, bình giữ nhiệt, bút ký, kỷ niệm chương lấy nhanh tại Đà Nẵng. Lên mẫu miễn phí 100% trước khi sản xuất hàng loạt.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#sec-giftset" class="bg-amber-400 hover:bg-amber-300 text-slate-900 font-bold px-4 py-2 rounded-lg shadow transition">
                                    XEM MẪU SẢN PHẨM THỰC TẾ
                                </a>
                                <span class="bg-black/25 border border-white/20 px-3 py-2 rounded-lg font-medium">
                                    Website: lifecolor.com | Hotline/Zalo: 0935.828.376
                                </span>
                            </div>
                        </div>
                        <div class="w-5/12 grid grid-cols-2 gap-3">
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=1kp6irPQj2TxTlJng0pPCidnSuc3Vv-rM&sz=w600"
                                     data-id="1kp6irPQj2TxTlJng0pPCidnSuc3Vv-rM"
                                     onerror="handleDriveImgError(this, 'Qua+Tang+Go')"
                                     alt="Quà Tặng Gỗ Khắc Laser" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=1kz0371VNuLu_ta2W0ZzrVCUX_-nSOk8k&sz=w600"
                                     data-id="1kz0371VNuLu_ta2W0ZzrVCUX_-nSOk8k"
                                     onerror="handleDriveImgError(this, 'Ly+Giu+Nhiet')"
                                     alt="Ly Giữ Nhiệt In Logo" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=1O4Bw7Rpi8aEAT90HsnrEi4hbI5MUocF3&sz=w600"
                                     data-id="1O4Bw7Rpi8aEAT90HsnrEi4hbI5MUocF3"
                                     onerror="handleDriveImgError(this, 'Bo+Gift+Cao+Cap')"
                                     alt="Bộ Gift Doanh Nghiệp" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                            <div class="bg-white p-1.5 rounded-lg shadow-lg">
                                <img src="https://drive.google.com/thumbnail?id=13C5xqdR9VnOnNe-Vk5xZGxOn3S3ZYRzS&sz=w600"
                                     data-id="13C5xqdR9VnOnNe-Vk5xZGxOn3S3ZYRzS"
                                     onerror="handleDriveImgError(this, 'But+Ky+Khac+Logo')"
                                     alt="Bút Ký Khắc Logo" class="w-full h-28 lg:h-32 object-cover rounded">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ====== 2 BANNER THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Kích thước bằng nhau: h-[205px], chữ nhỏ gọn nằm trọn bên trong) ====== -->
                <div class="block md:hidden relative w-full h-[205px]">
                    <!-- Mobile Slide 1 -->
                    <div id="mobile-slide-0" class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-100 bg-gradient-to-br from-[#0f355e] via-[#164e87] to-[#1d4ed8] p-3.5 flex items-center justify-between gap-2.5">
                        <div class="w-[62%] text-white space-y-1.5 pl-1">
                            <span class="inline-block bg-amber-400 text-slate-900 font-bold text-[9px] px-2 py-0.5 rounded">
                                LIFECOLOR.COM - ĐÀ NẴNG
                            </span>
                            <h2 class="text-[13px] font-extrabold leading-tight">
                                QUÀ TẶNG DOANH NGHIỆP & KHẮC LASER THEO YÊU CẦU
                            </h2>
                            <p class="text-[10px] text-sky-100 leading-snug">
                                Bình giữ nhiệt, Sổ da, Bút ký, Bộ Giftset in logo sắc nét.
                            </p>
                            <div class="pt-0.5 text-[10px] font-semibold text-amber-300">
                                ĐC: Trần Cao Vân, Đà Nẵng<br>ĐT: 0935.828.376
                            </div>
                        </div>
                        <div class="w-[38%] flex flex-col gap-1.5 pr-1">
                            <img src="https://drive.google.com/thumbnail?id=14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g&sz=w400"
                                 data-id="14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g"
                                 onerror="handleDriveImgError(this, 'Giftset')"
                                 alt="Quà tặng Life Color" class="w-full h-20 object-cover rounded-lg border border-white/40 bg-white">
                            <img src="https://drive.google.com/thumbnail?id=1KPyRzcOTVW819K_coUk2xwZFF8z-Ukwe&sz=w400"
                                 data-id="1KPyRzcOTVW819K_coUk2xwZFF8z-Ukwe"
                                 onerror="handleDriveImgError(this, 'Binh+GN')"
                                 alt="Bình giữ nhiệt" class="w-full h-20 object-cover rounded-lg border border-white/40 bg-white">
                        </div>
                    </div>

                    <!-- Mobile Slide 2 -->
                    <div id="mobile-slide-1" class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none bg-gradient-to-br from-[#7f1d1d] via-[#b91c1c] to-[#dc2626] p-3.5 flex items-center justify-between gap-2.5">
                        <div class="w-[62%] text-white space-y-1.5 pl-1">
                            <span class="inline-block bg-white text-brand-red font-bold text-[9px] px-2 py-0.5 rounded">
                                MIỄN PHÍ THIẾT KẾ LOGO
                            </span>
                            <h2 class="text-[13px] font-extrabold leading-tight">
                                XƯỞNG SẢN XUẤT GIFTSET & CẮT KHẮC LASER LẤY NHANH
                            </h2>
                            <p class="text-[10px] text-rose-100 leading-snug">
                                Chiết khấu đến 25% đơn hàng sỉ. Giao hàng tận nơi toàn quốc.
                            </p>
                            <div class="pt-0.5 text-[10px] font-semibold text-amber-300">
                                Hotline/Zalo: 0935.828.376<br>Thanh Khê, Đà Nẵng
                            </div>
                        </div>
                        <div class="w-[38%] flex flex-col gap-1.5 pr-1">
                            <img src="https://drive.google.com/thumbnail?id=1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N&sz=w400"
                                 data-id="1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N"
                                 onerror="handleDriveImgError(this, 'So+Tay')"
                                 alt="Sổ tay in logo" class="w-full h-20 object-cover rounded-lg border border-white/40 bg-white">
                            <img src="https://drive.google.com/thumbnail?id=13nKX5wxl4FakMOYREVDpeRllQ3mMRVmW&sz=w400"
                                 data-id="13nKX5wxl4FakMOYREVDpeRllQ3mMRVmW"
                                 onerror="handleDriveImgError(this, 'But+Ky')"
                                 alt="Bút ký khắc laser" class="w-full h-20 object-cover rounded-lg border border-white/40 bg-white">
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng chấm tròn dưới Banner -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="setSlide(0)" id="dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="setSlide(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy theo mẫu quatang3s.vn, chữ nhỏ gọn 1 hàng) ================= -->
    <section class="py-4">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">DANH MỤC SẢN PHẨM</h2>
                    <span class="text-[11px] text-slate-500">Chọn danh mục quà tặng doanh nghiệp</span>
                </div>

                <!-- Chia 4 cột trên điện thoại, 8 cột trên máy tính; chữ danh mục nhỏ gọn viết liền trên 1 hàng -->
                <div class="grid grid-cols-4 lg:grid-cols-8 gap-2 sm:gap-3 pt-1">
                    <a href="#sec-but-so" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=13C5xqdR9VnOnNe-Vk5xZGxOn3S3ZYRzS&sz=w300" data-id="13C5xqdR9VnOnNe-Vk5xZGxOn3S3ZYRzS" onerror="handleDriveImgError(this, 'But+Ky')" alt="Quà Tặng Bút" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Quà Tặng Bút</span>
                    </a>

                    <a href="#sec-but-so" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N&sz=w300" data-id="1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N" onerror="handleDriveImgError(this, 'So+Tay')" alt="Quà Tặng Sổ Tay" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Quà Tặng Sổ Tay</span>
                    </a>

                    <a href="#sec-giftset" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g&sz=w300" data-id="14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g" onerror="handleDriveImgError(this, 'Gift+So+Tay')" alt="Bộ Gift Sổ Tay" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Bộ Gift Sổ Tay</span>
                    </a>

                    <a href="#sec-giftset" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1O4Bw7Rpi8aEAT90HsnrEi4hbI5MUocF3&sz=w300" data-id="1O4Bw7Rpi8aEAT90HsnrEi4hbI5MUocF3" onerror="handleDriveImgError(this, 'Gift+BGN')" alt="Bộ Gift BGN" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Bộ Gift BGN</span>
                    </a>

                    <a href="#sec-binh-ly" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1KPyRzcOTVW819K_coUk2xwZFF8z-Ukwe&sz=w300" data-id="1KPyRzcOTVW819K_coUk2xwZFF8z-Ukwe" onerror="handleDriveImgError(this, 'Binh+Giu+Nhiet')" alt="Bình Giữ Nhiệt" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Bình Giữ Nhiệt</span>
                    </a>

                    <a href="#sec-binh-ly" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1kz0371VNuLu_ta2W0ZzrVCUX_-nSOk8k&sz=w300" data-id="1kz0371VNuLu_ta2W0ZzrVCUX_-nSOk8k" onerror="handleDriveImgError(this, 'Ly+Giu+Nhiet')" alt="Ly Giữ Nhiệt" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Ly Giữ Nhiệt</span>
                    </a>

                    <a href="#sec-da-go-laser" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1xPzFCjOWLv2tybEgJXdDh_54uHQTIluO&sz=w300" data-id="1xPzFCjOWLv2tybEgJXdDh_54uHQTIluO" onerror="handleDriveImgError(this, 'Qua+Tang+Da')" alt="Quà Tặng Da" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Quà Tặng Da</span>
                    </a>

                    <a href="#sec-da-go-laser" class="group flex flex-col items-center p-2 rounded-lg bg-slate-50 hover:bg-brand-light border border-slate-200/80 transition text-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-slate-200 bg-white mb-1.5 shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1kp6irPQj2TxTlJng0pPCidnSuc3Vv-rM&sz=w300" data-id="1kp6irPQj2TxTlJng0pPCidnSuc3Vv-rM" onerror="handleDriveImgError(this, 'Khac+Laser')" alt="Quà Tặng Gỗ" class="w-full h-full object-cover group-hover:scale-105 transition">
                        </div>
                        <span class="text-[10px] sm:text-[11px] font-semibold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Quà Tặng Gỗ</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 3: DANH MỤC 1 - BỘ GIFT (BỘ QUÀ TẶNG DOANH NGHIỆP) ================= -->
    <section id="sec-giftset" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">BỘ GIFT QUÀ TẶNG IN KHẮC LOGO</h2>
                    <div class="flex flex-wrap items-center gap-2 text-[11px] font-medium text-slate-600">
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Bộ Gift Sổ Tay</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Bộ Gift Bình Giữ Nhiệt</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Bộ Gift Quà Tặng Gỗ</span>
                    </div>
                </div>

                <!-- Grid 2 cột trên điện thoại, 4 cột trên máy tính (Tên sản phẩm đầy đủ không bị cắt chữ) -->
                <div id="grid-giftset" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 4: DANH MỤC 2 - BÌNH GIỮ NHIỆT & LY GIỮ NHIỆT IN LOGO ================= -->
    <section id="sec-binh-ly" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">BÌNH GIỮ NHIỆT & LY GIỮ NHIỆT IN LOGO</h2>
                    <div class="flex flex-wrap items-center gap-2 text-[11px] font-medium text-slate-600">
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Bình Giữ Nhiệt Inox 304</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Bình Giữ Nhiệt Vỏ Tre</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Ly Giữ Nhiệt Khắc Laser</span>
                    </div>
                </div>

                <div id="grid-binh-ly" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 5: DANH MỤC 3 - QUÀ TẶNG SỔ TAY & QUÀ TẶNG BÚT KÝ ================= -->
    <section id="sec-but-so" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">QUÀ TẶNG SỔ TAY & QUÀ TẶNG BÚT KÝ</h2>
                    <div class="flex flex-wrap items-center gap-2 text-[11px] font-medium text-slate-600">
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Sổ Bìa Da</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Bút Kim Loại Khắc Tên</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Bút Gỗ Khắc Laser</span>
                    </div>
                </div>

                <div id="grid-but-so" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 6: DANH MỤC 4 - QUÀ TẶNG DA, GỖ & DỊCH VỤ KHẮC LASER ĐÀ NẴNG ================= -->
    <section id="sec-da-go-laser" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">QUÀ TẶNG DA - GỖ & GIA CÔNG KHẮC LASER</h2>
                    <div class="flex flex-wrap items-center gap-2 text-[11px] font-medium text-slate-600">
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Hộp Đựng Namecard</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Ví Đựng Passport</span>
                        <span class="whitespace-nowrap px-2 py-0.5 bg-slate-100 rounded">Cắt Khắc Laser Đà Nẵng</span>
                    </div>
                </div>

                <div id="grid-da-go-laser" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 7: CHÍNH SÁCH ĐẶT HÀNG TẠI LIFE COLOR (Giống mẫu quatang3s.vn) ================= -->
    <section class="py-4">
        <div class="ux-container">
            <div class="bg-brand-blue text-white rounded-xl p-4 sm:p-6 shadow-xs">
                <h2 class="text-center font-bold text-sm sm:text-base uppercase tracking-wide mb-4 text-amber-300">
                    CHÍNH SÁCH ĐẶT HÀNG TẠI LIFE COLOR ĐÀ NẴNG
                </h2>
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                    <div class="bg-white/10 rounded-lg p-3 text-center border border-white/15">
                        <i class="fa-solid fa-headset text-amber-300 text-xl mb-1.5"></i>
                        <h3 class="font-bold text-xs sm:text-sm">Báo giá 24/7 nhanh chóng</h3>
                        <p class="text-[11px] text-sky-100 mt-1">Tư vấn tận tình theo đúng ngân sách sự kiện doanh nghiệp.</p>
                    </div>
                    <div class="bg-white/10 rounded-lg p-3 text-center border border-white/15">
                        <i class="fa-solid fa-pen-ruler text-amber-300 text-xl mb-1.5"></i>
                        <h3 class="font-bold text-xs sm:text-sm">Thiết kế & lên mẫu miễn phí</h3>
                        <p class="text-[11px] text-sky-100 mt-1">Demo file in UV & khắc laser logo sắc nét trước khi sản xuất.</p>
                    </div>
                    <div class="bg-white/10 rounded-lg p-3 text-center border border-white/15">
                        <i class="fa-solid fa-gears text-amber-300 text-xl mb-1.5"></i>
                        <h3 class="font-bold text-xs sm:text-sm">Sản xuất hàng linh động</h3>
                        <p class="text-[11px] text-sky-100 mt-1">Xưởng gia công trực tiếp tại Đà Nẵng, đáp ứng đơn hàng gấp.</p>
                    </div>
                    <div class="bg-white/10 rounded-lg p-3 text-center border border-white/15">
                        <i class="fa-solid fa-truck-fast text-amber-300 text-xl mb-1.5"></i>
                        <h3 class="font-bold text-xs sm:text-sm">Giao hàng đúng hẹn</h3>
                        <p class="text-[11px] text-sky-100 mt-1">Cam kết chất lượng đồng đều, bảo hành uy tín trên từng sản phẩm.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 8: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ================= -->
    <section id="form-bao-gia" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-4 sm:p-6 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">FORM YÊU CẦU TƯ VẤN & BÁO GIÁ SỈ</h2>
                    <span class="text-xs font-semibold text-brand-red">Phản hồi báo giá trong 5 phút</span>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    <div class="lg:col-span-5 space-y-3 text-xs sm:text-sm text-slate-600 bg-slate-50 p-4 rounded-xl border border-slate-200">
                        <h3 class="font-bold text-brand-blue text-sm sm:text-base">
                            ĐẶT QUÀ TẶNG IN KHẮC LOGO TẠI LIFECOLOR.COM
                        </h3>
                        <p>
                            Quý khách hàng, doanh nghiệp tại Đà Nẵng và toàn quốc cần báo giá quà tặng sự kiện, đại hội, tri ân khách hàng vui lòng điền thông tin bên cạnh.
                        </p>
                        <ul class="space-y-2 text-slate-700 font-medium">
                            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-2"></i>Chiết khấu cao cho đơn hàng số lượng từ 30 - 5.000+ phần quà.</li>
                            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-2"></i>Nhận khắc laser lẻ & sỉ lấy ngay tại Trần Cao Vân, Thanh Khê, Đà Nẵng.</li>
                            <li><i class="fa-solid fa-circle-check text-emerald-600 mr-2"></i>Xuất hóa đơn VAT đầy đủ theo yêu cầu công ty.</li>
                        </ul>
                        <div class="p-3 bg-white rounded-lg border border-slate-200 space-y-1">
                            <p class="font-bold text-slate-800">Thông tin liên hệ trực tiếp:</p>
                            <p><i class="fa-solid fa-location-dot text-brand-red mr-1.5"></i>Địa chỉ: Trần Cao Vân, Thanh Khê, Đà Nẵng</p>
                            <p><i class="fa-solid fa-phone-volume text-brand-red mr-1.5"></i>Hotline / Zalo: <a href="tel:0935828376" class="font-bold text-brand-blue">0935.828.376</a></p>
                        </div>
                    </div>

                    <form onsubmit="submitQuoteForm(event)" class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-3">
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên / Tên đơn vị *</label>
                            <input id="q-name" type="text" required placeholder="Nhập họ tên hoặc tên công ty"
                                   class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-blue">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                            <input id="q-phone" type="tel" required placeholder="Ví dụ: 0935828376"
                                   class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-blue">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục sản phẩm quan tâm</label>
                            <select id="q-category" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-blue bg-white">
                                <option value="Bộ Giftset Sổ Tay - Bút Ký - Bình Giữ Nhiệt">Bộ Giftset Sổ Tay - Bút Ký - Bình Giữ Nhiệt</option>
                                <option value="Bình Giữ Nhiệt In Khắc Logo">Bình Giữ Nhiệt In Khắc Logo</option>
                                <option value="Ly Giữ Nhiệt In Logo">Ly Giữ Nhiệt In Logo</option>
                                <option value="Quà Tặng Sổ Tay (Sổ Da, Sổ Bìa Còng)">Quà Tặng Sổ Tay (Sổ Da, Sổ Bìa Còng)</option>
                                <option value="Quà Tặng Bút Ký Kim Loại / Bút Gỗ">Quà Tặng Bút Ký Kim Loại / Bút Gỗ</option>
                                <option value="Quà Tặng Da / Hộp Đựng Namecard">Quà Tặng Da / Hộp Đựng Namecard</option>
                                <option value="Gia Công Cắt Khắc Laser Theo Yêu Cầu">Gia Công Cắt Khắc Laser Theo Yêu Cầu</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Số lượng dự kiến</label>
                            <input id="q-qty" type="text" placeholder="Ví dụ: 50 bộ, 100 bình..."
                                   class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-blue">
                        </div>
                        <div class="sm:col-span-2">
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết (Nội dung in/khắc logo, thời gian cần nhận hàng)</label>
                            <textarea id="q-note" rows="3" placeholder="Nhập yêu cầu in ấn, khắc laser hoặc sản phẩm bạn đã chọn..."
                                      class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-blue"></textarea>
                        </div>
                        <div class="sm:col-span-2 flex flex-wrap items-center justify-between gap-2 pt-1">
                            <span class="text-[11px] text-slate-500">* Tư vấn viên Life Color sẽ liên hệ qua SĐT/Zalo ngay sau khi nhận yêu cầu.</span>
                            <button type="submit" class="w-full sm:w-auto bg-brand-red hover:bg-red-700 text-white font-bold text-xs sm:text-sm px-6 py-2.5 rounded-lg shadow transition">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 9: DANH MỤC CÁC ĐỐI TÁC TIÊU BIỂU ================= -->
    <section id="sec-doi-tac" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU</h2>
                    <span class="text-[11px] text-slate-500">Hơn 500+ doanh nghiệp tại Đà Nẵng & miền Trung tin chọn</span>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3">
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
                        <span class="font-extrabold text-sm text-emerald-700 tracking-wider">VIETCOMBANK</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Chi nhánh Đà Nẵng</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
                        <span class="font-extrabold text-sm text-amber-600 tracking-wider">SUN GROUP</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Đối tác quà tặng sự kiện</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
                        <span class="font-extrabold text-sm text-orange-600 tracking-wider">FPT DA NANG</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Giftset nhân viên & đối tác</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
                        <span class="font-extrabold text-sm text-red-600 tracking-wider">VIETTEL</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Quà tặng tri ân khách hàng</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
                        <span class="font-extrabold text-sm text-blue-800 tracking-wider">BIDV ĐÀ NẴNG</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Bình giữ nhiệt & sổ da</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-brand-blue transition">
                        <span class="font-extrabold text-sm text-teal-700 tracking-wider">FURAMA RESORT</span>
                        <span class="text-[10px] text-slate-500 mt-0.5">Quà tặng gỗ & khắc laser</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 10: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC) ================= -->
    <section id="sec-tin-tuc" class="py-3">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">TIN TỨC & KINH NGHIỆM CHỌN QUÀ TẶNG</h2>
                    <span class="text-[11px] text-slate-500">Cập nhật xu hướng quà tặng doanh nghiệp mới nhất</span>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <!-- Bài viết 1 -->
                    <article class="rounded-lg border border-slate-200 overflow-hidden bg-white flex flex-col hover:shadow-md transition">
                        <div class="relative h-44 bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g&sz=w600"
                                 data-id="14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g"
                                 onerror="handleDriveImgError(this, 'Tin+Tuc+Giftset')"
                                 alt="Bộ Giftset Quà Tặng" class="w-full h-full object-cover">
                            <div class="absolute top-2.5 left-2.5 bg-brand-blue text-white text-center px-2 py-1 rounded leading-tight shadow">
                                <span class="block font-bold text-xs">12</span>
                                <span class="block text-[10px]">Th11</span>
                            </div>
                        </div>
                        <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand-blue leading-snug">
                                    Bộ Giftset Bình Giữ Nhiệt Inox 304 & Bút Ký Khắc Logo – Quà Tặng Doanh Nghiệp Sang Trọng Tại Đà Nẵng
                                </h3>
                                <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    Bộ sản phẩm kết hợp sổ tay bìa da, bút ký kim loại và bình giữ nhiệt khắc laser sắc nét giúp quảng bá thương hiệu bền vững...
                                </p>
                            </div>
                            <a href="#form-bao-gia" class="text-xs font-semibold text-brand-blue hover:text-brand-red inline-flex items-center gap-1">
                                <span>Xem chi tiết & nhận báo giá</span>
                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </a>
                        </div>
                    </article>

                    <!-- Bài viết 2 -->
                    <article class="rounded-lg border border-slate-200 overflow-hidden bg-white flex flex-col hover:shadow-md transition">
                        <div class="relative h-44 bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=13nKX5wxl4FakMOYREVDpeRllQ3mMRVmW&sz=w600"
                                 data-id="13nKX5wxl4FakMOYREVDpeRllQ3mMRVmW"
                                 onerror="handleDriveImgError(this, 'Khac+Laser+Da+Nang')"
                                 alt="Dịch vụ khắc laser Đà Nẵng" class="w-full h-full object-cover">
                            <div class="absolute top-2.5 left-2.5 bg-brand-blue text-white text-center px-2 py-1 rounded leading-tight shadow">
                                <span class="block font-bold text-xs">08</span>
                                <span class="block text-[10px]">Th11</span>
                            </div>
                        </div>
                        <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand-blue leading-snug">
                                    Dịch Vụ Cắt Khắc Laser Đà Nẵng Nhanh Chóng, Sắc Nét Trên Kim Loại, Gỗ, Da & Bình Giữ Nhiệt
                                </h3>
                                <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    Life Color (Trần Cao Vân, Thanh Khê, Đà Nẵng) sở hữu hệ thống máy khắc laser hiện đại, đường khắc tinh xảo, không lem, lấy nhanh...
                                </p>
                            </div>
                            <a href="#form-bao-gia" class="text-xs font-semibold text-brand-blue hover:text-brand-red inline-flex items-center gap-1">
                                <span>Xem chi tiết & nhận báo giá</span>
                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </a>
                        </div>
                    </article>

                    <!-- Bài viết 3 -->
                    <article class="rounded-lg border border-slate-200 overflow-hidden bg-white flex flex-col hover:shadow-md transition">
                        <div class="relative h-44 bg-slate-100 overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N&sz=w600"
                                 data-id="1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N"
                                 onerror="handleDriveImgError(this, 'In+So+Da+Da+Nang')"
                                 alt="Đặt in sổ da quà tặng" class="w-full h-full object-cover">
                            <div class="absolute top-2.5 left-2.5 bg-brand-blue text-white text-center px-2 py-1 rounded leading-tight shadow">
                                <span class="block font-bold text-xs">02</span>
                                <span class="block text-[10px]">Th11</span>
                            </div>
                        </div>
                        <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand-blue leading-snug">
                                    Kinh Nghiệm Đặt Sản Xuất Sổ Bìa Da, Bút Quà Tặng In Logo Theo Ngân Sách Sự Kiện Công Ty
                                </h3>
                                <p class="text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    Tổng hợp các mẫu sổ da bìa còng, sổ dán gáy ép kim logo kèm bút ký kim loại, bút gỗ hộp tre sang trọng với chi phí tối ưu nhất...
                                </p>
                            </div>
                            <a href="#form-bao-gia" class="text-xs font-semibold text-brand-blue hover:text-brand-red inline-flex items-center gap-1">
                                <span>Xem chi tiết & nhận báo giá</span>
                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </a>
                        </div>
                    </article>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= SECTION 11: ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ ================= -->
    <section id="sec-lien-he" class="py-3 pb-6">
        <div class="ux-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
                <div class="flatsome-title-wrap">
                    <h2 class="flatsome-title-main text-sm sm:text-base">KẾT NỐI FANPAGE & BẢN ĐỒ ĐƯỜNG ĐI LIFE COLOR ĐÀ NẴNG</h2>
                    <span class="text-xs text-slate-600">Trần Cao Vân, Thanh Khê, Đà Nẵng | ĐT: 0935.828.376</span>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-4">
                    <!-- Khung Fanpage Facebook ngoài Trang Chủ -->
                    <div class="rounded-xl border border-slate-200 p-3 bg-slate-50 flex flex-col justify-between space-y-3">
                        <div class="flex items-center justify-between gap-2 border-b border-slate-200 pb-2.5">
                            <div class="flex items-center gap-2.5">
                                <img src="https://drive.google.com/thumbnail?id=1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2&sz=w200"
                                     data-id="1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2"
                                     onerror="handleDriveImgError(this, 'LC')"
                                     alt="Logo Fanpage" class="w-10 h-10 rounded-full object-contain bg-white border border-slate-200 p-0.5">
                                <div>
                                    <h3 class="font-bold text-xs sm:text-sm text-brand-blue">Life Color – Quà Tặng Đà Nẵng</h3>
                                    <p class="text-[11px] text-slate-500">facebook.com/Lifecolor.Danang</p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/Lifecolor.Danang/" target="_blank" rel="noopener"
                               class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold px-3 py-1.5 rounded-lg inline-flex items-center gap-1.5 shrink-0">
                                <i class="fa-brands fa-facebook"></i>
                                <span>Theo dõi Trang</span>
                            </a>
                        </div>

                        <!-- Nhúng Facebook Page Plugin kết hợp khung hiển thị trực tiếp -->
                        <div class="w-full overflow-hidden rounded-lg bg-white border border-slate-200 flex flex-col items-center">
                            <iframe
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FLifecolor.Danang%2F&tabs=timeline&width=500&height=220&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                width="100%" height="220" style="border:none;overflow:hidden" scrolling="no" frameborder="0"
                                allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600 pt-1">
                            <span><i class="fa-solid fa-circle-check text-blue-600 mr-1"></i>Cập nhật mẫu thực tế mỗi ngày trên Fanpage</span>
                            <a href="https://www.facebook.com/Lifecolor.Danang/" target="_blank" rel="noopener" class="font-semibold text-brand-blue hover:underline">
                                Mở Fanpage Facebook <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>
                    </div>

                    <!-- Khung Ảnh & Bản Đồ Google Map ngoài Trang Chủ -->
                    <div class="rounded-xl border border-slate-200 p-3 bg-slate-50 flex flex-col justify-between space-y-3">
                        <div class="flex items-center justify-between gap-2 border-b border-slate-200 pb-2.5">
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-brand-blue">
                                    <i class="fa-solid fa-map-location-dot text-brand-red mr-1"></i>Bản Đồ Google Map - Life Color Đà Nẵng
                                </h3>
                                <p class="text-[11px] text-slate-600">Địa chỉ: Trần Cao Vân, Quận Thanh Khê, TP. Đà Nẵng</p>
                            </div>
                            <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJe4CIRAAZQjER9Nl6lnABO-4" target="_blank" rel="noopener"
                               class="bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-semibold px-3 py-1.5 rounded-lg inline-flex items-center gap-1.5 shrink-0">
                                <i class="fa-solid fa-diamond-turn-right"></i>
                                <span>Chỉ đường</span>
                            </a>
                        </div>

                        <!-- Google Map Embed trực tiếp ngoài trang chủ -->
                        <div class="w-full h-[220px] rounded-lg overflow-hidden border border-slate-200 bg-slate-200 relative">
                            <iframe
                                title="Bản đồ Life Color Trần Cao Vân, Thanh Khê, Đà Nẵng"
                                src="https://maps.google.com/maps?q=Tr%E1%BA%A7n%20Cao%20V%C3%A2n,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                                width="100%" height="220" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600 pt-1">
                            <span><i class="fa-solid fa-location-dot text-brand-red mr-1"></i>Trần Cao Vân, Thanh Khê, Đà Nẵng</span>
                            <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJUWMNmVMYQjERN5h945-_BBs" target="_blank" rel="noopener" class="font-semibold text-brand-blue hover:underline">
                                Xem bản đồ lớn <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FOOTER CHUẨN FLATSOME (Giống mẫu quatang3s.vn) ================= -->
    <footer class="bg-brand-dark text-white pt-8 pb-20 md:pb-8 border-t-4 border-brand-red">
        <div class="ux-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/15 text-xs">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://drive.google.com/thumbnail?id=1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2&sz=w200"
                             data-id="1z7MUaHuKI1HFhRjXSvqnN0BxKHq6QLi2"
                             onerror="handleDriveImgError(this, 'Life+Color')"
                             alt="Life Color" class="h-9 w-auto bg-white p-1 rounded">
                        <div>
                            <span class="block font-extrabold text-sm text-amber-300">LIFE COLOR ĐÀ NẴNG</span>
                            <span class="block text-[11px] text-sky-200">Website: lifecolor.com</span>
                        </div>
                    </div>
                    <p class="text-slate-200 leading-relaxed">
                        Chuyên sản xuất, cung cấp Quà Tặng Doanh Nghiệp, Quà Tặng In Logo, Bình Giữ Nhiệt, Sổ Tay, Bút Ký, Bộ Giftset & Gia Công Cắt Khắc Laser Uy Tín Hàng Đầu Tại Đà Nẵng.
                    </p>
                    <ul class="space-y-1.5 text-slate-100">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> Trần Cao Vân, Thanh Khê, Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 mr-2"></i><strong>Hotline/Zalo:</strong> 0935.828.376</li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> lifecolor.com</li>
                        <li><i class="fa-brands fa-facebook text-amber-400 mr-2"></i><strong>Fanpage:</strong> fb.com/Lifecolor.Danang</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="space-y-2">
                    <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><a href="#sec-giftset" class="hover:text-amber-300">Bộ Giftset Quà Tặng Doanh Nghiệp</a></li>
                        <li><a href="#sec-binh-ly" class="hover:text-amber-300">Bình Giữ Nhiệt In Khắc Logo</a></li>
                        <li><a href="#sec-binh-ly" class="hover:text-amber-300">Ly Giữ Nhiệt In Logo Theo Yêu Cầu</a></li>
                        <li><a href="#sec-but-so" class="hover:text-amber-300">Quà Tặng Sổ Tay (Sổ Da, Sổ Bìa Giấy)</a></li>
                        <li><a href="#sec-but-so" class="hover:text-amber-300">Quà Tặng Bút Ký Kim Loại & Bút Gỗ</a></li>
                        <li><a href="#sec-da-go-laser" class="hover:text-amber-300">Quà Tặng Da & Hộp Đựng Namecard</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Dịch vụ sản xuất -->
                <div class="space-y-2">
                    <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">DỊCH VỤ SẢN XUẤT</h4>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><a href="#sec-da-go-laser" class="hover:text-amber-300">Dịch Vụ Cắt Khắc Laser Đà Nẵng</a></li>
                        <li><a href="#sec-but-so" class="hover:text-amber-300">Sản Xuất Sổ Da & In Sổ Tay Theo Yêu Cầu</a></li>
                        <li><a href="#sec-binh-ly" class="hover:text-amber-300">Bình Giữ Nhiệt Vỏ Tre Khắc Logo</a></li>
                        <li><a href="#sec-giftset" class="hover:text-amber-300">Sản Xuất Hộp Quà Cứng In Logo</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300">Thiết Kế & Lên Mẫu Quà Tặng Miễn Phí</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Chính sách khách hàng -->
                <div class="space-y-2">
                    <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">CHÍNH SÁCH</h4>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách đặt hàng & báo giá sỉ</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách thiết kế & duyệt mẫu</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách thanh toán & hóa đơn VAT</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách giao hàng toàn quốc</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách bảo hành & đổi trả</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-300 text-center sm:text-left">
                <p>© Bản quyền thuộc về <strong>LIFE COLOR (lifecolor.com)</strong> - Trần Cao Vân, Thanh Khê, Đà Nẵng.</p>
                <p>Hotline / Zalo: <strong>0935.828.376</strong></p>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed bottom-3 right-3 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/Lifecolor.Danang/" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
            <i class="fa-brands fa-facebook-messenger text-base sm:text-lg"></i>
            <span class="text-[11px] sm:text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0935828376" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
            <span class="bg-white text-[#0068FF] font-extrabold text-[10px] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-[11px] sm:text-xs font-bold">0935.828.376</span>
        </a>

        <!-- Nút Gọi Hotline -->
        <a href="tel:0935828376"
           class="floating-pulse flex items-center gap-2 bg-brand-red hover:bg-red-700 text-white px-3.5 py-2 rounded-full shadow-lg transition">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-[11px] sm:text-xs font-extrabold">0935.828.376</span>
        </a>
    </div>

    <!-- ================= HỘP THOẠI THÔNG BÁO (Thay thế hoàn toàn alert/confirm) ================= -->
    <div id="custom-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-4 bg-black/60 backdrop-blur-xs">
        <div class="bg-white rounded-xl max-w-md w-full p-5 shadow-2xl border border-slate-200 text-center space-y-3">
            <div class="w-12 h-12 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center mx-auto text-xl">
                <i class="fa-solid fa-check"></i>
            </div>
            <h3 id="modal-title" class="font-bold text-base text-brand-blue">Đã ghi nhận yêu cầu!</h3>
            <p id="modal-message" class="text-xs sm:text-sm text-slate-600 leading-relaxed"></p>
            <div class="pt-2 flex items-center justify-center gap-2">
                <a href="https://zalo.me/0935828376" target="_blank" rel="noopener" class="bg-[#0068FF] text-white text-xs font-bold px-4 py-2 rounded-lg">
                    Chat Zalo 0935.828.376
                </a>
                <button onclick="closeModal()" class="bg-slate-200 hover:bg-slate-300 text-slate-800 text-xs font-bold px-4 py-2 rounded-lg">
                    Đóng
                </button>
            </div>
        </div>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ DỮ LIỆU 13 ẢNH SẢN PHẨM THỰC TẾ, SLIDER & FORM ================= -->
    <script>
        /* Cơ chế tải ảnh Google Drive an toàn với nhiều lớp dự phòng để luôn hiển thị ảnh thực tế */
        function handleDriveImgError(img, fallbackText) {
            const fileId = img.getAttribute('data-id');
            const step = parseInt(img.getAttribute('data-fallback-step') || '0', 10);
            if (fileId && step === 0) {
                img.setAttribute('data-fallback-step', '1');
                img.src = 'https://lh3.googleusercontent.com/d/' + fileId;
            } else if (fileId && step === 1) {
                img.setAttribute('data-fallback-step', '2');
                img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                img.onerror = null;
                img.src = 'https://placehold.co/600x600/f1f5f9/164e87?text=' + (fallbackText || 'Life+Color');
            }
        }

        /* Danh sách toàn bộ 13 ảnh sản phẩm thực tế từ Google Drive của khách hàng,
           được phân vào đúng Danh Mục & Tên Sản Phẩm chuẩn mẫu quatang3s.vn & Life Color Đà Nẵng */
        const productsData = [
            // --- NHÓM 1: BỘ GIFT (GIFTSET QUÀ TẶNG DOANH NGHIỆP) ---
            {
                id: 'LC-GIFT01',
                driveId: '14ZJoQ9TrhscVi1SwO1DRqBZlMGe-1E0g',
                category: 'Bộ Gift',
                section: 'grid-giftset',
                name: 'Bộ Giftset Sổ Tay Bìa Da, Bút Ký & Bình Giữ Nhiệt In Logo Theo Yêu Cầu',
                oldPrice: '390.000₫',
                newPrice: '312.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-GIFT02',
                driveId: '1O4Bw7Rpi8aEAT90HsnrEi4hbI5MUocF3',
                category: 'Bộ Gift',
                section: 'grid-giftset',
                name: 'Bộ Quà Tặng Sổ Da Cao Cấp Kèm Bút Ký Kim Loại Khắc Laser Logo',
                oldPrice: '220.000₫',
                newPrice: '175.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-GIFT03',
                driveId: '1xPzFCjOWLv2tybEgJXdDh_54uHQTIluO',
                category: 'Bộ Gift Bình Giữ Nhiệt',
                section: 'grid-giftset',
                name: 'Bộ Gift Bình Giữ Nhiệt & Bút Ký Hộp Cứng In Logo Doanh Nghiệp',
                oldPrice: '195.000₫',
                newPrice: '156.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-GIFT04',
                driveId: '1YjfU6gpDlQ0z4q6nxIep41QVNPKp4vE_',
                category: 'Bộ Gift Quà Tặng Gỗ',
                section: 'grid-giftset',
                name: 'Bộ Quà Tặng Bình Giữ Nhiệt Vỏ Tre & Bút Gỗ Khắc Laser Theo Yêu Cầu',
                oldPrice: '280.000₫',
                newPrice: '238.000₫',
                discount: '-15%'
            },

            // --- NHÓM 2: BÌNH GIỮ NHIỆT & LY GIỮ NHIỆT IN LOGO ---
            {
                id: 'LC-BGN01',
                driveId: '1KPyRzcOTVW819K_coUk2xwZFF8z-Ukwe',
                category: 'Bình Giữ Nhiệt',
                section: 'grid-binh-ly',
                name: 'Bình Giữ Nhiệt Inox 304 500ml In UV & Khắc Laser Logo Công Ty',
                oldPrice: '135.000₫',
                newPrice: '108.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-BGN02',
                driveId: '1kz0371VNuLu_ta2W0ZzrVCUX_-nSOk8k',
                category: 'Ly Giữ Nhiệt In Logo',
                section: 'grid-binh-ly',
                name: 'Ly Giữ Nhiệt Inox 304 Kèm Hộp Đựng In Khắc Logo Theo Yêu Cầu',
                oldPrice: '140.000₫',
                newPrice: '112.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-BGN03',
                driveId: '1rsB6kjdLLp-vt8K5Yqg-rfGiKkv9VBr8',
                category: 'Bình Giữ Nhiệt',
                section: 'grid-binh-ly',
                name: 'Bình Giữ Nhiệt Hiển Thị Nhiệt Độ Inox 304 Khắc Tên & Logo Sắc Nét',
                oldPrice: '120.000₫',
                newPrice: '96.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-BGN04',
                driveId: '1SzXu6VM99LKrAM89P3EBxYfGxxZseSAi',
                category: 'Bình Giữ Nhiệt Vỏ Tre',
                section: 'grid-binh-ly',
                name: 'Bình Giữ Nhiệt Vỏ Tre Khắc Laser Logo Làm Quà Tặng Khách Hàng',
                oldPrice: '165.000₫',
                newPrice: '135.000₫',
                discount: '-18%'
            },

            // --- NHÓM 3: QUÀ TẶNG SỔ TAY & QUÀ TẶNG BÚT ---
            {
                id: 'LC-BS01',
                driveId: '1qpABMzEKhssUQjYVHoUBBDvtWYn3DT3N',
                category: 'Quà Tặng Sổ Tay',
                section: 'grid-but-so',
                name: 'Sổ Bìa Da PU Cao Cấp A5 Dập Chìm & Ép Kim Logo Theo Yêu Cầu',
                oldPrice: '125.000₫',
                newPrice: '98.000₫',
                discount: '-22%'
            },
            {
                id: 'LC-BS02',
                driveId: '13C5xqdR9VnOnNe-Vk5xZGxOn3S3ZYRzS',
                category: 'Quà Tặng Bút',
                section: 'grid-but-so',
                name: 'Bút Ký Kim Loại Cao Cấp Khắc Laser Tên & Logo Kèm Hộp Đựng',
                oldPrice: '75.000₫',
                newPrice: '56.000₫',
                discount: '-25%'
            },
            {
                id: 'LC-BS03',
                driveId: '13qZdq6GSlGR4-M-RKN2K-ZZUAiAMRwNd',
                category: 'Bút Gỗ',
                section: 'grid-but-so',
                name: 'Bộ Bút Ký Gỗ Vỏ Tre Kèm Hộp Gỗ Khắc Laser Theo Yêu Cầu Đà Nẵng',
                oldPrice: '130.000₫',
                newPrice: '104.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-BS04',
                driveId: '13nKX5wxl4FakMOYREVDpeRllQ3mMRVmW',
                category: 'Quà Tặng Sổ Tay',
                section: 'grid-but-so',
                name: 'Sổ Tay Bìa Cứng Lò Xo Kèm Bút Bi Nhựa In Logo Quảng Cáo Giá Rẻ',
                oldPrice: '65.000₫',
                newPrice: '49.000₫',
                discount: '-25%'
            },

            // --- NHÓM 4: QUÀ TẶNG DA, GỖ & GIA CÔNG CẮT KHẮC LASER ---
            {
                id: 'LC-DG01',
                driveId: '1kp6irPQj2TxTlJng0pPCidnSuc3Vv-rM',
                category: 'Quà Tặng Gỗ - Laser',
                section: 'grid-da-go-laser',
                name: 'Quà Tặng Gỗ & Kỷ Niệm Chương Khắc Laser Theo Yêu Cầu Tại Đà Nẵng',
                oldPrice: '160.000₫',
                newPrice: '128.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-DG02',
                driveId: '1xPzFCjOWLv2tybEgJXdDh_54uHQTIluO',
                category: 'Hộp Đựng Namecard',
                section: 'grid-da-go-laser',
                name: 'Hộp Đựng Namecard Da Phối Kim Loại Khắc Laser Logo Doanh Nghiệp',
                oldPrice: '85.000₫',
                newPrice: '68.000₫',
                discount: '-20%'
            },
            {
                id: 'LC-DG03',
                driveId: '1YjfU6gpDlQ0z4q6nxIep41QVNPKp4vE_',
                category: 'Quà Tặng In Logo',
                section: 'grid-da-go-laser',
                name: 'Móc Khóa Gỗ & Kim Loại Khắc Laser Logo Quảng Cáo Theo Yêu Cầu',
                oldPrice: '35.000₫',
                newPrice: '25.000₫',
                discount: '-28%'
            },
            {
                id: 'LC-DG04',
                driveId: '13qZdq6GSlGR4-M-RKN2K-ZZUAiAMRwNd',
                category: 'Dịch Vụ Khắc Laser',
                section: 'grid-da-go-laser',
                name: 'Gia Công Cắt Khắc Laser Trên Kim Loại, Gỗ, Da, Mica Lấy Nhanh Đà Nẵng',
                oldPrice: '50.000₫',
                newPrice: '35.000₫',
                discount: '-30%'
            }
        ];

        /* Hàm tạo thẻ sản phẩm chuẩn Flatsome:
           - Chỉ có đúng vòng tròn % giảm giá góc trên bên trái (không để các nhãn dán khác ở trang chủ)
           - Chia 2 cột trên điện thoại, tên sản phẩm hiển thị đầy đủ không bị cắt hay tràn chữ */
        function createProductCardHTML(product) {
            const imgUrl = 'https://drive.google.com/thumbnail?id=' + product.driveId + '&sz=w700';
            return `
                <div class="product-small box bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div class="box-image relative w-full aspect-square bg-slate-50 overflow-hidden">
                        <!-- Chỉ hiển thị duy nhất % giảm giá góc trên bên trái chuẩn Flatsome -->
                        <div class="flatsome-sale-badge">${product.discount}</div>
                        <img src="${imgUrl}"
                             data-id="${product.driveId}"
                             onerror="handleDriveImgError(this, '${encodeURIComponent(product.category)}')"
                             alt="${product.name}"
                             loading="lazy"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>

                    <div class="box-text box-text-products p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10px] uppercase tracking-wider text-slate-400 font-semibold mb-1">
                                ${product.category}
                            </p>
                            <!-- Tên sản phẩm đầy đủ, tự xuống dòng gọn gàng, không bị thiếu chữ hay tràn khung -->
                            <h3 class="product-full-title text-xs sm:text-[13px] font-semibold text-slate-800 hover:text-brand-blue mb-2">
                                ${product.name}
                            </h3>
                        </div>

                        <div class="pt-1 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                                <del class="text-[11px] text-slate-400">${product.oldPrice}</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brand-red">${product.newPrice}</span>
                            </div>
                            <button onclick="selectProductForQuote('${product.name.replace(/'/g, "\\'")}')"
                                    class="w-full py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white text-[11px] font-semibold transition">
                                Nhận Báo Giá In Logo
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        /* Render toàn bộ sản phẩm ra 4 danh mục trên trang chủ */
        function renderAllProducts(filterKeyword = '') {
            const sections = ['grid-giftset', 'grid-binh-ly', 'grid-but-so', 'grid-da-go-laser'];
            sections.forEach(secId => {
                const container = document.getElementById(secId);
                if (!container) return;
                const list = productsData.filter(item => {
                    const matchSection = item.section === secId;
                    const matchSearch = !filterKeyword ||
                        item.name.toLowerCase().includes(filterKeyword.toLowerCase()) ||
                        item.category.toLowerCase().includes(filterKeyword.toLowerCase());
                    return matchSection && matchSearch;
                });
                container.innerHTML = list.map(createProductCardHTML).join('');
            });
        }

        /* Xử lý chọn sản phẩm đưa xuống Form Báo Giá */
        let quoteItemCount = 0;
        function selectProductForQuote(productName) {
            quoteItemCount++;
            const badge = document.getElementById('quote-count');
            if (badge) badge.textContent = quoteItemCount;

            const noteInput = document.getElementById('q-note');
            if (noteInput) {
                noteInput.value = 'Tôi cần tư vấn & báo giá in khắc logo mẫu: ' + productName;
            }
            scrollToSection('form-bao-gia');
        }

        /* Xử lý Tìm Kiếm */
        function handleSearch(e) {
            e.preventDefault();
            const keyword = document.getElementById('search-input').value.trim();
            renderAllProducts(keyword);
            scrollToSection('sec-giftset');
        }

        function filterCategory(cat) {
            document.getElementById('search-input').value = '';
            renderAllProducts('');
        }

        function scrollToSection(id) {
            const el = document.getElementById(id);
            if (el) el.scrollIntoView({ behavior: 'smooth' });
        }

        /* Đóng/mở Menu Danh Mục trên Điện Thoại */
        function toggleMobileDrawer() {
            const drawer = document.getElementById('mobile-drawer');
            drawer.classList.toggle('hidden');
        }

        /* Xử lý Tự Trượt 2 Banner (Đồng bộ cả Desktop và Mobile) */
        let currentSlide = 0;
        const totalSlides = 2;

        function setSlide(index) {
            currentSlide = index;
            for (let i = 0; i < totalSlides; i++) {
                const dSlide = document.getElementById('desktop-slide-' + i);
                const mSlide = document.getElementById('mobile-slide-' + i);
                const dot = document.getElementById('dot-' + i);

                if (i === currentSlide) {
                    if (dSlide) { dSlide.classList.remove('opacity-0', 'pointer-events-none'); dSlide.classList.add('opacity-100'); }
                    if (mSlide) { mSlide.classList.remove('opacity-0', 'pointer-events-none'); mSlide.classList.add('opacity-100'); }
                    if (dot) { dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all'; }
                } else {
                    if (dSlide) { dSlide.classList.remove('opacity-100'); dSlide.classList.add('opacity-0', 'pointer-events-none'); }
                    if (mSlide) { mSlide.classList.remove('opacity-100'); mSlide.classList.add('opacity-0', 'pointer-events-none'); }
                    if (dot) { dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all'; }
                }
            }
        }

        /* Xử lý gửi Form Báo Giá (Không dùng alert) */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const cat = document.getElementById('q-category').value;
            const qty = document.getElementById('q-qty').value.trim() || 'Chưa xác định';

            const modal = document.getElementById('custom-modal');
            const msg = document.getElementById('modal-message');
            msg.innerHTML = `Cảm ơn <strong>${name}</strong> (${phone})!<br>Yêu cầu báo giá danh mục <strong>${cat}</strong> (Số lượng: ${qty}) đã được gửi tới <strong>Life Color Đà Nẵng (0935.828.376)</strong>. Bộ phận kinh doanh sẽ liên hệ gửi mẫu & bảng giá ngay!`;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            e.target.reset();
        }

        function closeModal() {
            const modal = document.getElementById('custom-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Khởi chạy khi tải trang */
        window.onload = function () {
            renderAllProducts('');
            setInterval(function () {
                const next = (currentSlide + 1) % totalSlides;
                setSlide(next);
            }, 4500);
        };
    </script>
</body>
</html>
