<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Phúc Minh Quang Window - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng | phucminhquang.com</title>
  <meta name="description" content="Phúc Minh Quang Window - Chuyên thiết kế, sản xuất và thi công cửa nhôm Xingfa, cửa kính cường lực, cửa nhựa lõi thép, cửa kính tự động, cầu thang kính, kính ốp bếp, phòng tắm kính tại Đà Nẵng. Địa chỉ: 378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng. Hotline: 0935.955.652." />

  <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ link trang web -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://phucminhquang.com/" />
  <meta property="og:site_name" content="Phúc Minh Quang Window" />
  <meta property="og:title" content="Phúc Minh Quang Window - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng" />
  <meta property="og:description" content="Thi công cửa nhôm Xingfa chính hãng, cửa kính cường lực, cầu thang kính, phòng tắm kính tại Đà Nẵng. Hotline: 0935.955.652 - 378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY" />
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY" />
  <meta property="og:image:alt" content="Logo Phúc Minh Quang Window" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Phúc Minh Quang Window - phucminhquang.com" />
  <meta name="twitter:description" content="Cửa nhôm Xingfa nhập khẩu & giải pháp nhôm kính cao cấp tại Đà Nẵng - 0935.955.652." />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY" />

  <!-- Google Font Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: '#0B4EA2',   /* Xanh dương chủ đạo theo nhận diện ngành cửa & logo */
              dark: '#073570',      /* Xanh navy đậm */
              light: '#EBF3FC',     /* Nền xanh nhạt */
              accent: '#D9232D',    /* Đỏ nhấn giá bán & giảm giá % */
              accentDark: '#B71922',
              gold: '#F59E0B'
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Thiết lập chuẩn chống tràn viền ngang trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
    }

    body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #F6F8FB;
      color: #1E293B;
      -webkit-font-smoothing: antialiased;
    }

    /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
    .pmq-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .pmq-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tối ưu thanh danh mục máy tính: viết liền 1 hàng, chữ nhỏ gọn, không xuống dòng */
    .desktop-nav-list {
      display: flex;
      flex-wrap: nowrap;
      align-items: center;
      justify-content: space-between;
      width: 100%;
      list-style: none;
      margin: 0;
      padding: 0;
      gap: 2px;
    }

    .desktop-nav-item {
      position: relative;
      flex-shrink: 0;
    }

    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      white-space: nowrap;
      font-size: clamp(11px, 0.85vw, 13px);
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.01em;
      padding: 11px clamp(6px, 0.75vw, 12px);
      color: #FFFFFF;
      transition: background-color 0.2s ease, color 0.2s ease;
      border-radius: 6px;
    }

    .desktop-nav-link:hover,
    .desktop-nav-link.active {
      background-color: rgba(255, 255, 255, 0.16);
      color: #FFFFFF;
    }

    /* Dropdown menu chuẩn Flatsome */
    .desktop-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 220px;
      background: #FFFFFF;
      border: 1px solid #E2E8F0;
      border-radius: 10px;
      box-shadow: 0 12px 28px rgba(7, 53, 112, 0.14);
      padding: 6px 0;
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      z-index: 60;
    }

    .desktop-nav-item:hover > .desktop-dropdown,
    .desktop-nav-item:focus-within > .desktop-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .desktop-dropdown a {
      display: block;
      padding: 9px 16px;
      font-size: 13px;
      font-weight: 500;
      color: #334155;
      white-space: nowrap;
      transition: background-color 0.15s ease, color 0.15s ease;
    }

    .desktop-dropdown a:hover {
      background-color: #EBF3FC;
      color: #0B4EA2;
    }

    /* Hệ thống 2 banner tự trượt bằng nhau tuyệt đối, chữ nằm gọn cách xa viền banner */
    .hero-slider-grid {
      display: grid;
      grid-template-columns: 1fr;
      width: 100%;
      position: relative;
      overflow: hidden;
      border-radius: 14px;
    }

    .hero-slide {
      grid-area: 1 / 1;
      width: 100%;
      height: 100%;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
      transition: opacity 0.6s ease, transform 0.6s ease;
      transform: scale(1.01);
      display: flex;
      align-items: center;
    }

    .hero-slide.is-active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      transform: scale(1);
      z-index: 2;
    }

    /* Tiêu đề Section phong cách Flatsome UX Builder */
    .ux-section-title {
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
      margin-bottom: 22px;
    }

    .ux-section-title::before,
    .ux-section-title::after {
      content: "";
      flex: 1;
      height: 2px;
      background: linear-gradient(90deg, transparent, #CBD5E1);
    }

    .ux-section-title::after {
      background: linear-gradient(90deg, #CBD5E1, transparent);
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes softPulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(217, 35, 45, 0.45); }
      50% { box-shadow: 0 0 0 10px rgba(217, 35, 45, 0); }
    }
    .hotline-pulse {
      animation: softPulse 2.2s infinite;
    }

    /* Ẩn thanh cuộn phụ nhưng vẫn cho cuộn mượt nếu cần */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>

<body class="text-slate-800 bg-[#F6F8FB]">

  <!-- ==================== 1. TOP BAR (FLATSOME TOP BAR - KHÔNG CÓ THANH CHỈNH SỬA UXBUILDER) ==================== -->
  <div class="bg-brand-dark text-white/95 text-xs border-b border-white/10">
    <div class="pmq-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <svg class="w-3.5 h-3.5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span>378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5 text-white/80">
          <svg class="w-3.5 h-3.5 text-amber-400 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <span>Làm việc: 07:30 - 21:00 (T2 - CN)</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <span class="hidden md:inline text-white/85">Website: <strong class="text-white">phucminhquang.com</strong></span>
        <a href="https://www.facebook.com/profile.php?id=100063557834101" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 text-white/90 hover:text-amber-300 transition">
          <svg class="w-3.5 h-3.5 fill-current" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
          <span>Fanpage</span>
        </a>
      </div>
    </div>
  </div>

  <!-- ==================== 2. HEADER MAIN (FLATSOME HEADER - LOGO GỌN NHỎ, KHÔNG NÚT GỌI NGAY) ==================== -->
  <header class="bg-white sticky top-0 z-50 shadow-sm border-b border-slate-200">
    <!-- Hàng Header trên: Logo gọn nhỏ + Thanh tìm kiếm + Nút menu điện thoại -->
    <div class="pmq-container py-2.5 flex items-center justify-between gap-3">
      <!-- Logo gọn nhỏ + Tên thương hiệu -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
        <img
          src="https://lh3.googleusercontent.com/d/1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY"
          alt="Logo Phúc Minh Quang Window"
          class="h-10 sm:h-11 w-auto max-w-[130px] object-contain rounded"
          data-drive-id="1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY"
          onerror="handleDriveImageError(this, 'PMQ+Window')"
        />
        <div class="leading-tight min-w-0">
          <div class="text-sm sm:text-base font-extrabold text-brand-primary tracking-tight truncate">PHÚC MINH QUANG</div>
          <div class="text-[10px] sm:text-[11px] font-semibold text-slate-500 uppercase tracking-wider truncate">Window • Nhôm Kính Đà Nẵng</div>
        </div>
      </a>

      <!-- Ô tìm kiếm sản phẩm (giống mẫu ngochanwindow.com) -->
      <form id="headerSearchForm" class="hidden md:flex items-center flex-1 max-w-md bg-slate-100 border border-slate-200 rounded-lg overflow-hidden focus-within:border-brand-primary focus-within:bg-white transition">
        <input
          id="headerSearchInput"
          type="text"
          placeholder="Tìm cửa nhôm Xingfa, kính cường lực, cầu thang kính..."
          class="w-full bg-transparent px-3.5 py-2 text-xs lg:text-sm text-slate-700 placeholder-slate-400 focus:outline-none"
        />
        <button type="submit" aria-label="Tìm kiếm" class="px-3.5 py-2 bg-brand-primary hover:bg-brand-dark text-white transition shrink-0">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
        </button>
      </form>

      <!-- Thông tin ngắn gọn bên phải trên desktop (KHÔNG đặt nút Gọi ngay để tránh tràn viền) -->
      <div class="hidden lg:flex items-center gap-4 text-xs text-slate-600 shrink-0">
        <div class="text-right leading-snug">
          <div class="font-semibold text-slate-800">Tư vấn & Khảo sát miễn phí</div>
          <div class="text-brand-primary font-bold">378 Âu Cơ, Liên Chiểu, Đà Nẵng</div>
        </div>
      </div>

      <!-- Nút mở Menu Mobile -->
      <button
        id="mobileMenuBtn"
        type="button"
        aria-label="Mở danh mục"
        class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-brand-primary text-white text-xs font-semibold hover:bg-brand-dark transition shrink-0"
      >
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/></svg>
        <span>Danh mục</span>
      </button>
    </div>

    <!-- Hàng Header dưới (Desktop): Thanh Danh Mục 1 hàng duy nhất, chữ nhỏ gọn, không xuống dòng -->
    <nav class="hidden lg:block bg-brand-primary border-t border-brand-dark/20" aria-label="Danh mục chính">
      <div class="pmq-container">
        <ul class="desktop-nav-list">
          <li class="desktop-nav-item">
            <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#san-pham-xingfa" class="desktop-nav-link" onclick="filterProducts('all')">
              <span>Cửa nhôm xingfa</span>
              <svg class="w-3 h-3 opacity-85" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="desktop-dropdown">
              <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')">Cửa nhôm xingfa 1 cánh</a>
              <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')">Cửa nhôm xingfa 2 cánh</a>
              <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')">Cửa nhôm xingfa 3 cánh</a>
              <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')">Cửa nhôm xingfa 4 cánh</a>
              <a href="#san-pham-xingfa" onclick="filterProducts('5-canh')">Cửa nhôm xingfa 5 cánh</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#danh-muc-san-pham" class="desktop-nav-link">Cửa kính cường lực</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#danh-muc-san-pham" class="desktop-nav-link">
              <span>Sản phẩm</span>
              <svg class="w-3 h-3 opacity-85" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <div class="desktop-dropdown">
              <a href="#san-pham-xingfa">Cửa nhôm xingfa</a>
              <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-nhua-loi-thep')">Cửa nhựa lõi thép</a>
              <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-tu-dong')">Cửa kính tự động</a>
              <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cau-thang-kinh')">Cầu thang kính</a>
              <a href="#danh-muc-san-pham" onclick="openCategoryDetail('kinh-op-bep')">Kính ốp bếp</a>
              <a href="#danh-muc-san-pham" onclick="openCategoryDetail('phong-tam-kinh')">Phòng tắm kính</a>
            </div>
          </li>
          <li class="desktop-nav-item">
            <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#bao-gia" class="desktop-nav-link">Báo giá</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
          </li>
          <li class="desktop-nav-item">
            <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Thanh danh mục nhanh nhỏ gọn trên Điện Thoại (Vuốt ngang gọn gàng, dễ chọn) -->
    <div class="lg:hidden bg-brand-primary border-t border-white/10">
      <div class="pmq-container py-1.5 overflow-x-auto no-scrollbar">
        <div class="flex items-center gap-1.5 whitespace-nowrap">
          <a href="#trang-chu" class="px-2.5 py-1 rounded-md text-[11px] font-semibold bg-white/15 text-white">Trang chủ</a>
          <a href="#gioi-thieu" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Giới thiệu</a>
          <a href="#san-pham-xingfa" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Cửa nhôm xingfa</a>
          <a href="#danh-muc-san-pham" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Cửa kính cường lực</a>
          <a href="#danh-muc-san-pham" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Sản phẩm</a>
          <a href="#cong-trinh" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Công trình</a>
          <a href="#bao-gia" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Báo giá</a>
          <a href="#tin-tuc" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Tin tức</a>
          <a href="#lien-he" class="px-2.5 py-1 rounded-md text-[11px] font-semibold text-white/95 hover:bg-white/15">Liên hệ</a>
        </div>
      </div>
    </div>
  </header>

  <!-- ==================== MOBILE DRAWER MENU ==================== -->
  <div id="mobileDrawerBackdrop" class="fixed inset-0 bg-slate-900/50 z-[70] hidden transition-opacity"></div>
  <aside id="mobileDrawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-[80] shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="p-4 bg-brand-primary text-white flex items-center justify-between">
      <div class="font-bold text-sm tracking-wide">DANH MỤC WEBSITE</div>
      <button id="closeMobileMenuBtn" type="button" aria-label="Đóng menu" class="p-1.5 rounded-lg bg-white/15 hover:bg-white/25">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
    </div>

    <!-- Tìm kiếm trong menu mobile -->
    <div class="p-3 border-b border-slate-200 bg-slate-50">
      <form id="mobileSearchForm" class="flex items-center bg-white border border-slate-300 rounded-lg overflow-hidden">
        <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm..." class="w-full px-3 py-2 text-xs text-slate-700 focus:outline-none" />
        <button type="submit" class="px-3 py-2 bg-brand-primary text-white text-xs font-semibold">Tìm</button>
      </form>
    </div>

    <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-sm font-medium">
      <a href="#trang-chu" class="mobile-nav-link block px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">Trang chủ</a>
      <a href="#gioi-thieu" class="mobile-nav-link block px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">Giới thiệu</a>

      <!-- Submenu Cửa nhôm xingfa -->
      <div>
        <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">
          <span>Cửa nhôm xingfa</span>
          <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-xs">
          <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 1 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 2 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 3 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 4 cánh</a>
          <a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa 5 cánh</a>
        </div>
      </div>

      <a href="#danh-muc-san-pham" class="mobile-nav-link block px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">Cửa kính cường lực</a>

      <!-- Submenu Sản phẩm -->
      <div>
        <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">
          <span>Sản phẩm</span>
          <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-xs">
          <a href="#san-pham-xingfa" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa nhôm xingfa</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-nhua-loi-thep')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa nhựa lõi thép</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cua-tu-dong')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cửa kính tự động</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('cau-thang-kinh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Cầu thang kính</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('kinh-op-bep')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Kính ốp bếp</a>
          <a href="#danh-muc-san-pham" onclick="openCategoryDetail('phong-tam-kinh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand-primary">+ Phòng tắm kính</a>
        </div>
      </div>

      <a href="#cong-trinh" class="mobile-nav-link block px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">Công trình</a>
      <a href="#bao-gia" class="mobile-nav-link block px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">Báo giá</a>
      <a href="#tin-tuc" class="mobile-nav-link block px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">Tin tức</a>
      <a href="#lien-he" class="mobile-nav-link block px-4 py-3 text-slate-800 hover:bg-brand-light hover:text-brand-primary">Liên hệ</a>
    </div>

    <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1">
      <div class="font-bold text-brand-primary">PHÚC MINH QUANG WINDOW</div>
      <div>378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng</div>
      <div>Hotline: <a href="tel:0935955652" class="font-bold text-brand-accent">0935.955.652</a></div>
    </div>
  </aside>

  <!-- ==================== 3. HERO SLIDER (2 BANNER TỰ TRƯỢT BẰNG NHAU, CHỮ NẰM TRONG & CÁCH XA VIỀN) ==================== -->
  <section id="trang-chu" class="py-3 sm:py-4">
    <div class="pmq-container">
      <!-- Flatsome UX Slider Block -->
      <div id="heroSlider" class="hero-slider-grid shadow-md bg-brand-dark">

        <!-- BANNER 1 -->
        <div class="hero-slide is-active bg-gradient-to-br from-[#073570] via-[#0B4EA2] to-[#1366C7] text-white">
          <!-- Khoảng đệm rộng (px-7 py-8 trên mobile, px-16 py-12 trên desktop) giúp chữ luôn cách xa viền và không bao giờ bị cắt -->
          <div class="w-full px-7 py-8 sm:px-12 sm:py-10 lg:px-16 lg:py-12 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
            <div class="lg:col-span-7 space-y-3 sm:space-y-4">
              <div class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.14em] text-amber-300">
                PHÚC MINH QUANG WINDOW • PHUCMINHQUANG.COM
              </div>
              <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight">
                THI CÔNG CỬA NHÔM XINGFA CHÍNH HÃNG TẠI ĐÀ NẴNG
              </h1>
              <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed">
                Thanh nhôm Profile Xingfa nhập khẩu tem đỏ hệ 55, 93 kết hợp phụ kiện Kinlong đồng bộ, kính an toàn cường lực chuẩn kỹ thuật. Bảo hành dài hạn đến 5 năm.
              </p>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs sm:text-sm text-white/95 pt-1">
                <div class="flex items-center gap-2">
                  <span class="w-1.5 h-1.5 rounded-full bg-amber-400 shrink-0"></span>
                  <span>Khảo sát, đo đạc miễn phí tận nơi</span>
                </div>
                <div class="flex items-center gap-2">
                  <span class="w-1.5 h-1.5 rounded-full bg-amber-400 shrink-0"></span>
                  <span>Gia công máy ép góc chuẩn xác</span>
                </div>
              </div>
              <div class="flex flex-wrap items-center gap-3 pt-2">
                <a href="#form-bao-gia" class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow transition">
                  Nhận Báo Giá Ngay
                </a>
                <a href="#san-pham-xingfa" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                  Xem Mẫu Cửa Xingfa
                </a>
              </div>
            </div>

            <!-- Hình ảnh nằm gọn bên trong khung banner -->
            <div class="lg:col-span-5">
              <div class="bg-white/10 p-2 rounded-xl border border-white/20 backdrop-blur-sm">
                <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-white">
                  <img
                    src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                    alt="Cửa nhôm Xingfa cao cấp Phúc Minh Quang Window"
                    class="w-full h-full object-cover"
                    data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                    onerror="handleDriveImageError(this, 'Cua+Nhom+Xingfa')"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- BANNER 2 (Cấu trúc và kích thước bằng hệt Banner 1) -->
        <div class="hero-slide bg-gradient-to-br from-[#0B2D5C] via-[#0A458F] to-[#1659A8] text-white">
          <div class="w-full px-7 py-8 sm:px-12 sm:py-10 lg:px-16 lg:py-12 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
            <div class="lg:col-span-7 space-y-3 sm:space-y-4">
              <div class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.14em] text-amber-300">
                GIẢI PHÁP NHÔM KÍNH TOÀN DIỆN • ĐÀ NẴNG
              </div>
              <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight tracking-tight">
                CỬA KÍNH CƯỜNG LỰC, PHÒNG TẮM KÍNH & CẦU THANG KÍNH
              </h2>
              <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed">
                Chuyên thiết kế & lắp đặt trọn gói cho nhà phố, biệt thự, khách sạn, resort tại Đà Nẵng và miền Trung. Thẩm mỹ sang trọng, bền bỉ theo thời gian.
              </p>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs sm:text-sm text-white/95 pt-1">
                <div class="flex items-center gap-2">
                  <span class="w-1.5 h-1.5 rounded-full bg-amber-400 shrink-0"></span>
                  <span>Giá xưởng trực tiếp không qua trung gian</span>
                </div>
                <div class="flex items-center gap-2">
                  <span class="w-1.5 h-1.5 rounded-full bg-amber-400 shrink-0"></span>
                  <span>Đội ngũ thi công chuyên nghiệp 24/7</span>
                </div>
              </div>
              <div class="flex flex-wrap items-center gap-3 pt-2">
                <a href="#cong-trinh" class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow transition">
                  Xem Công Trình Tiêu Biểu
                </a>
                <a href="#danh-muc-san-pham" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                  Khám Phá Danh Mục
                </a>
              </div>
            </div>

            <!-- Hình ảnh nằm gọn bên trong khung banner -->
            <div class="lg:col-span-5">
              <div class="bg-white/10 p-2 rounded-xl border border-white/20 backdrop-blur-sm">
                <div class="aspect-[16/10] w-full overflow-hidden rounded-lg bg-white">
                  <img
                    src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                    alt="Phòng tắm kính và cửa kính cường lực Phúc Minh Quang Window"
                    class="w-full h-full object-cover"
                    data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                    onerror="handleDriveImageError(this, 'Kinh+Cuong+Luc')"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút chuyển slide trái/phải gọn sát mép không đè chữ -->
        <button id="prevSlideBtn" type="button" aria-label="Banner trước" class="hidden sm:flex absolute left-2.5 top-1/2 -translate-y-1/2 z-10 w-9 h-9 rounded-full bg-black/30 hover:bg-black/55 text-white items-center justify-center transition">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button id="nextSlideBtn" type="button" aria-label="Banner sau" class="hidden sm:flex absolute right-2.5 top-1/2 -translate-y-1/2 z-10 w-9 h-9 rounded-full bg-black/30 hover:bg-black/55 text-white items-center justify-center transition">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Chấm chỉ báo 2 slide đặt sát đáy -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
          <button type="button" data-slide-dot="0" aria-label="Slide 1" class="slide-dot w-7 h-2 rounded-full bg-white transition-all"></button>
          <button type="button" data-slide-dot="1" aria-label="Slide 2" class="slide-dot w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/75 transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 4. GIỚI THIỆU CÔNG TY & THỐNG KÊ (FLATSOME ROW / COL) ==================== -->
  <section id="gioi-thieu" class="py-8 sm:py-10 bg-white border-y border-slate-200">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          CÔNG TY CỬA NHÔM XINGFA ĐÀ NẴNG – PHÚC MINH QUANG WINDOW
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
        <!-- Cột trái: Nội dung giới thiệu -->
        <div class="lg:col-span-7 space-y-3 text-sm sm:text-[15px] text-slate-600 leading-relaxed">
          <p>
            <strong class="text-slate-900">Phúc Minh Quang Window</strong> (CÔNG TY TNHH MTV CƠ KHÍ XÂY LẮP PHÚC MINH QUANG) là đơn vị uy tín chuyên thiết kế, gia công sản xuất và thi công lắp đặt các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực miền Trung.
          </p>
          <p>
            Các dòng sản phẩm chủ lực tại <strong class="text-brand-primary">phucminhquang.com</strong> bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính</strong>.
          </p>
          <p>
            Với phương châm <em>“Uy tín tạo thương hiệu – Chất lượng làm nên công trình”</em>, chúng tôi sở hữu xưởng sản xuất trang bị máy cắt 2 đầu, máy ép góc Xingfa hiện đại cùng đội ngũ kỹ thuật lành nghề, cam kết mang lại không gian sống hiện đại, an toàn, cách âm cách nhiệt vượt trội với mức giá tối ưu nhất.
          </p>
        </div>

        <!-- Cột phải: Bảng cam kết dịch vụ (theo mẫu ngochanwindow.com) -->
        <div class="lg:col-span-5 bg-brand-light/70 border border-blue-200/80 rounded-xl p-4 sm:p-5">
          <h3 class="text-sm font-bold text-brand-primary uppercase mb-3 pb-2 border-b border-blue-200">Cam kết từ Phúc Minh Quang Window</h3>
          <div class="space-y-2.5 text-xs sm:text-sm">
            <div class="flex items-center justify-between gap-2 pb-2 border-b border-blue-100">
              <span class="font-semibold text-slate-700">Hotline tư vấn</span>
              <a href="tel:0935955652" class="font-bold text-brand-accent">0935.955.652</a>
            </div>
            <div class="flex items-center justify-between gap-2 pb-2 border-b border-blue-100">
              <span class="font-semibold text-slate-700">Dịch vụ ưu đãi</span>
              <span class="font-semibold text-slate-800 text-right">Khảo sát & lắp đặt miễn phí</span>
            </div>
            <div class="flex items-center justify-between gap-2 pb-2 border-b border-blue-100">
              <span class="font-semibold text-slate-700">Chính sách giá</span>
              <span class="font-semibold text-slate-800 text-right">Ưu đãi chiết khấu đến 17%</span>
            </div>
            <div class="flex items-center justify-between gap-2 pb-2 border-b border-blue-100">
              <span class="font-semibold text-slate-700">Chế độ bảo hành</span>
              <span class="font-semibold text-slate-800 text-right">Bảo hành chính hãng 5 năm</span>
            </div>
            <div class="flex items-center justify-between gap-2">
              <span class="font-semibold text-slate-700">Chất lượng vật tư</span>
              <span class="font-semibold text-brand-primary text-right">100% chính hãng đồng bộ</span>
            </div>
          </div>
        </div>
      </div>

      <!-- 4 Cột con số nổi bật (Flatsome Counter Row) -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4 mt-6">
        <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">150+</div>
          <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Dự án đã hoàn thành</div>
        </div>
        <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">50+</div>
          <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Nhân sự kỹ thuật</div>
        </div>
        <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100+</div>
          <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Mẫu sản phẩm thực tế</div>
        </div>
        <div class="bg-slate-50 border border-slate-200 rounded-xl p-4 text-center">
          <div class="text-2xl sm:text-3xl font-extrabold text-brand-primary">100%</div>
          <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Khách hàng hài lòng</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 5. SẢN PHẨM CỬA NHÔM XINGFA (2 CỘT MOBILE, GIÁ & GIẢM GIÁ % GÓC TRÊN TRÁI) ==================== -->
  <section id="san-pham-xingfa" class="py-8 sm:py-12">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          SẢN PHẨM CỬA NHÔM XINGFA ĐÀ NẴNG
        </h2>
      </div>

      <!-- Bộ lọc nhanh hệ cửa nhôm Xingfa -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
        <button type="button" onclick="filterProducts('all')" data-filter-btn="all" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition">Tất cả (6)</button>
        <button type="button" onclick="filterProducts('1-canh')" data-filter-btn="1-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-primary hover:text-brand-primary transition">Xingfa 1 cánh</button>
        <button type="button" onclick="filterProducts('2-canh')" data-filter-btn="2-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-primary hover:text-brand-primary transition">Xingfa 2 cánh</button>
        <button type="button" onclick="filterProducts('3-canh')" data-filter-btn="3-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-primary hover:text-brand-primary transition">Xingfa 3 cánh</button>
        <button type="button" onclick="filterProducts('4-canh')" data-filter-btn="4-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-primary hover:text-brand-primary transition">Xingfa 4 cánh</button>
        <button type="button" onclick="filterProducts('5-canh')" data-filter-btn="5-canh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-primary hover:text-brand-primary transition">Xingfa 5 cánh / Xếp trượt</button>
      </div>

      <!-- Lưới sản phẩm: 2 cột chuẩn trên điện thoại, 3 cột trên máy tính -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu sản phẩm được render tự động từ JS để hỗ trợ tìm kiếm & lọc mượt mà -->
      </div>
    </div>
  </section>

  <!-- ==================== 6. DANH MỤC SẢN PHẨM NỔI BẬT (THEO MẪU NGOCHANWINDOW.COM) ==================== -->
  <section id="danh-muc-san-pham" class="py-8 sm:py-12 bg-white border-y border-slate-200">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          DANH MỤC SẢN PHẨM NỔI BẬT
        </h2>
      </div>

      <div id="categoryGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- 6 danh mục từ mẫu ngochanwindow.com với đúng ảnh Google Drive người dùng cung cấp -->
      </div>
    </div>
  </section>

  <!-- ==================== 7. BẢNG BÁO GIÁ THAM KHẢO (FLATSOME TABLE BLOCK) ==================== -->
  <section id="bao-gia" class="py-8 sm:py-12">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          BẢNG BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
        </h2>
      </div>

      <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
        <div class="overflow-x-auto">
          <table class="w-full text-left border-collapse min-w-[540px]">
            <thead>
              <tr class="bg-brand-primary text-white text-xs sm:text-sm">
                <th class="py-3 px-4 font-semibold w-14 text-center">STT</th>
                <th class="py-3 px-4 font-semibold">Hạng mục / Quy cách cửa nhôm Xingfa</th>
                <th class="py-3 px-4 font-semibold">Độ dày nhôm</th>
                <th class="py-3 px-4 font-semibold text-right">Đơn giá (VNĐ/m²)</th>
              </tr>
            </thead>
            <tbody class="divide-y divide-slate-200 text-xs sm:text-sm text-slate-700">
              <tr class="hover:bg-brand-light/40">
                <td class="py-3 px-4 text-center font-semibold">01</td>
                <td class="py-3 px-4 font-medium text-slate-900">Cửa sổ mở hất 2 cánh nhôm Xingfa hệ 55</td>
                <td class="py-3 px-4">1.4 mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-accent">1.850.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-light/40">
                <td class="py-3 px-4 text-center font-semibold">02</td>
                <td class="py-3 px-4 font-medium text-slate-900">Cửa đi quay mở 1 cánh nhôm Xingfa hệ 55</td>
                <td class="py-3 px-4">2.0 mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-accent">1.950.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-light/40">
                <td class="py-3 px-4 text-center font-semibold">03</td>
                <td class="py-3 px-4 font-medium text-slate-900">Cửa đi quay mở 2 cánh nhôm Xingfa hệ 55</td>
                <td class="py-3 px-4">2.0 mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-accent">2.050.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-light/40">
                <td class="py-3 px-4 text-center font-semibold">04</td>
                <td class="py-3 px-4 font-medium text-slate-900">Cửa đi quay mở 3 cánh nhôm Xingfa hệ 55</td>
                <td class="py-3 px-4">2.0 mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-accent">2.100.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-light/40">
                <td class="py-3 px-4 text-center font-semibold">05</td>
                <td class="py-3 px-4 font-medium text-slate-900">Cửa đi quay mở 4 cánh nhôm Xingfa hệ 55</td>
                <td class="py-3 px-4">2.0 mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-accent">2.150.000 ₫</td>
              </tr>
              <tr class="hover:bg-brand-light/40">
                <td class="py-3 px-4 text-center font-semibold">06</td>
                <td class="py-3 px-4 font-medium text-slate-900">Cửa đi xếp trượt gấp nhôm Xingfa hệ 63</td>
                <td class="py-3 px-4">2.0 mm</td>
                <td class="py-3 px-4 text-right font-bold text-brand-accent">2.200.000 ₫</td>
              </tr>
            </tbody>
          </table>
        </div>
        <div class="px-4 py-3 bg-slate-50 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
          <span>* Giá đã bao gồm kính an toàn 6.38mm, gioăng kép EPDM, keo ép góc chuyên dụng và lắp đặt tại Đà Nẵng.</span>
          <a href="#form-bao-gia" class="font-bold text-brand-primary hover:underline">Đăng ký nhận báo giá chi tiết theo bản vẽ →</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 8. CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG ==================== -->
  <section id="cong-trinh" class="py-8 sm:py-12 bg-white border-y border-slate-200">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
        </h2>
      </div>

      <!-- Tab lọc dự án chuẩn Flatsome -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
        <button type="button" onclick="filterProjects('all')" data-project-btn="all" class="project-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition">Tất cả dự án</button>
        <button type="button" onclick="filterProjects('khach-san')" data-project-btn="khach-san" class="project-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Dự án Khách sạn</button>
        <button type="button" onclick="filterProjects('resort')" data-project-btn="resort" class="project-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Dự án Resort & Nghỉ dưỡng</button>
      </div>

      <div id="projectGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <!-- 6 dự án Đà Nẵng từ Google Drive được render bằng JS -->
      </div>
    </div>
  </section>

  <!-- ==================== 9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ ==================== -->
  <section id="form-bao-gia" class="py-8 sm:py-12">
    <div class="pmq-container">
      <div class="bg-gradient-to-br from-brand-dark to-brand-primary rounded-2xl p-5 sm:p-8 lg:p-10 text-white shadow-lg">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
          <!-- Thông tin mời gọi -->
          <div class="lg:col-span-5 space-y-3">
            <div class="text-xs font-bold uppercase tracking-widest text-amber-300">TƯ VẤN MIỄN PHÍ 24/7</div>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-tight">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ TRỌN GÓI
            </h2>
            <p class="text-xs sm:text-sm text-blue-100 leading-relaxed">
              Để lại thông tin hạng mục công trình của bạn, kỹ thuật viên Phúc Minh Quang Window sẽ liên hệ khảo sát thực tế, mang mẫu nhôm kính tận nơi và gửi bảng báo giá tối ưu nhất trong vòng 15 phút.
            </p>
            <div class="pt-2 space-y-2 text-xs sm:text-sm text-white/95">
              <div class="flex items-center gap-2.5">
                <svg class="w-4 h-4 text-amber-300 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                <span>Hotline / Zalo: <strong>0935.955.652</strong></span>
              </div>
              <div class="flex items-center gap-2.5">
                <svg class="w-4 h-4 text-amber-300 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                <span>Xưởng & Văn phòng: <strong>378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng</strong></span>
              </div>
            </div>
          </div>

          <!-- Form nhập liệu -->
          <div class="lg:col-span-7 bg-white rounded-xl p-5 sm:p-6 text-slate-800 shadow-md">
            <form id="quoteForm" class="space-y-3.5">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
                </div>
                <div>
                  <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="Ví dụ: 0935.xxx.xxx" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label for="qCategory" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá</label>
                  <select id="qCategory" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                    <option value="Cầu thang kính">Cầu thang kính</option>
                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                    <option value="Trọn gói nhôm kính công trình">Trọn gói nhôm kính công trình</option>
                  </select>
                </div>
                <div>
                  <label for="qAddress" class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình</label>
                  <input id="qAddress" type="text" placeholder="Quận/Huyện tại Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
                </div>
              </div>

              <div>
                <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Ghi chú kích thước hoặc yêu cầu thêm</label>
                <textarea id="qNote" rows="3" placeholder="Ví dụ: Cần làm 1 bộ cửa đi 4 cánh + 3 cửa sổ mở hất, màu xám ghi..." class="w-full px-3.5 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"></textarea>
              </div>

              <button type="submit" class="w-full py-3 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white font-bold text-sm uppercase tracking-wide shadow transition">
                Gửi Yêu Cầu Báo Giá Ngay
              </button>

              <!-- Hộp thông báo phản hồi ngay trong form (KHÔNG dùng alert) -->
              <div id="quoteFeedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200"></div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 10. DANH MỤC CÁC BÀI VIẾT & TIN TỨC NỔI BẬT TRANG CHỦ ==================== -->
  <section id="tin-tuc" class="py-8 sm:py-12 bg-white border-y border-slate-200">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          TIN TỨC & KINH NGHIỆM NHÔM KÍNH
        </h2>
      </div>

      <!-- Danh mục các bài viết trang chủ -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
        <button type="button" onclick="filterArticles('all')" data-article-btn="all" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition">Tất cả bài viết</button>
        <button type="button" onclick="filterArticles('tu-van')" data-article-btn="tu-van" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Tư vấn chọn cửa</button>
        <button type="button" onclick="filterArticles('ky-thuat')" data-article-btn="ky-thuat" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Kỹ thuật & Độ bền</button>
        <button type="button" onclick="filterArticles('bao-gia')" data-article-btn="bao-gia" class="article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition">Báo giá & So sánh</button>
      </div>

      <div id="articleGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <!-- Bài viết render từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== 11. ĐỐI TÁC CỦA CHÚNG TÔI (6 ẢNH ĐỐI TÁC GOOGLE DRIVE) ==================== -->
  <section class="py-8 sm:py-10">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          ĐỐI TÁC CỦA CHÚNG TÔI
        </h2>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-brand-primary/50 hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác Phúc Minh Quang 1" class="max-h-full max-w-full object-contain" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" onerror="handleDriveImageError(this, 'Doi+Tac+1')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-brand-primary/50 hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác Phúc Minh Quang 2" class="max-h-full max-w-full object-contain" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" onerror="handleDriveImageError(this, 'Doi+Tac+2')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-brand-primary/50 hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác Phúc Minh Quang 3" class="max-h-full max-w-full object-contain" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" onerror="handleDriveImageError(this, 'Doi+Tac+3')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-brand-primary/50 hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác Phúc Minh Quang 4" class="max-h-full max-w-full object-contain" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" onerror="handleDriveImageError(this, 'Doi+Tac+4')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-brand-primary/50 hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác Phúc Minh Quang 5" class="max-h-full max-w-full object-contain" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" onerror="handleDriveImageError(this, 'Doi+Tac+5')" />
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-brand-primary/50 hover:shadow-sm transition">
          <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác Phúc Minh Quang 6" class="max-h-full max-w-full object-contain" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" onerror="handleDriveImageError(this, 'Doi+Tac+6')" />
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 12. BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK NGAY TRANG CHỦ ==================== -->
  <section id="lien-he" class="py-8 sm:py-12 bg-white border-t border-slate-200">
    <div class="pmq-container">
      <div class="ux-section-title">
        <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-primary text-center uppercase tracking-tight">
          BẢN ĐỒ CHỈ ĐƯỜNG & FANPAGE FACEBOOK
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6">
        <!-- Cột trái: Google Maps 378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng -->
        <div class="lg:col-span-7 bg-slate-50 border border-slate-200 rounded-xl overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
            <div>
              <h3 class="text-sm font-bold text-slate-900">Bản đồ vị trí Phúc Minh Quang Window</h3>
              <p class="text-xs text-slate-500">378 Âu Cơ, Quận Liên Chiểu, Tp. Đà Nẵng</p>
            </div>
            <a
              href="https://www.google.com/maps/search/?api=1&query=378+%C3%82u+C%C6%A1,+Li%C3%AAn+Chi%E1%BB%83u,+%C4%90%C3%A0+N%E1%BA%B5ng"
              target="_blank"
              rel="noopener noreferrer"
              class="px-3 py-1.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs font-semibold transition"
            >
              Mở Google Maps
            </a>
          </div>
          <div class="w-full h-[320px] sm:h-[360px] flex-1 bg-slate-200">
            <iframe
              title="Bản đồ Phúc Minh Quang Window - 378 Âu Cơ, Liên Chiểu, Đà Nẵng"
              src="https://maps.google.com/maps?q=378%20%C3%82u%20C%C6%A1,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
              allowfullscreen
            ></iframe>
          </div>
        </div>

        <!-- Cột phải: Fanpage Facebook Phúc Minh Quang Window -->
        <div class="lg:col-span-5 bg-slate-50 border border-slate-200 rounded-xl overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-white border-b border-slate-200 flex items-center justify-between gap-2">
            <div class="flex items-center gap-2.5 min-w-0">
              <img
                src="https://lh3.googleusercontent.com/d/1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY"
                alt="Fanpage Phúc Minh Quang Window"
                class="w-9 h-9 rounded-full object-contain border border-slate-200 bg-white p-0.5 shrink-0"
                data-drive-id="1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY"
                onerror="handleDriveImageError(this, 'PMQ')"
              />
              <div class="min-w-0">
                <h3 class="text-sm font-bold text-slate-900 truncate">Phúc Minh Quang Window</h3>
                <p class="text-xs text-slate-500 truncate">Theo dõi công trình thực tế trên Facebook</p>
              </div>
            </div>
            <a
              href="https://www.facebook.com/profile.php?id=100063557834101"
              target="_blank"
              rel="noopener noreferrer"
              class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs font-semibold shrink-0 transition"
            >
              Xem Fanpage
            </a>
          </div>

          <!-- Nhúng khung Fanpage Facebook chuẩn + thẻ dự phòng đẹp mắt -->
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-3">
            <div class="w-full overflow-hidden rounded-lg bg-white border border-slate-200 min-h-[240px] flex items-center justify-center">
              <iframe
                title="Fanpage Facebook Phúc Minh Quang Window"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063557834101&tabs=timeline&width=420&height=260&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                width="100%"
                height="260"
                style="border:none;overflow:hidden;width:100%;"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>

            <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-wrap items-center justify-between gap-2 text-xs">
              <div class="text-slate-600">
                Cập nhật hình ảnh lắp đặt cửa nhôm Xingfa hàng ngày tại Đà Nẵng.
              </div>
              <a
                href="https://www.facebook.com/profile.php?id=100063557834101"
                target="_blank"
                rel="noopener noreferrer"
                class="font-bold text-[#1877F2] hover:underline"
              >
                Nhắn tin qua Facebook →
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== 13. FOOTER (FLATSOME 4 CỘT CHUẨN MẪU NGOCHANWINDOW.COM) ==================== -->
  <footer class="bg-brand-dark text-blue-100 pt-10 pb-6 border-t-4 border-brand-primary">
    <div class="pmq-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/15">
        <!-- Cột 1: Thông tin liên hệ -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <img
              src="https://lh3.googleusercontent.com/d/1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY"
              alt="Logo Phúc Minh Quang Window"
              class="h-10 w-auto object-contain bg-white rounded p-1"
              data-drive-id="1zo6Mbq8MEIVjMg94Eudo1pCMftI67SIY"
              onerror="handleDriveImageError(this, 'PMQ')"
            />
            <div class="font-extrabold text-white text-sm leading-tight">
              PHÚC MINH QUANG<br /><span class="text-xs font-medium text-blue-200">WINDOW ĐÀ NẴNG</span>
            </div>
          </div>
          <p class="text-xs text-blue-100/85 leading-relaxed">
            CÔNG TY TNHH MTV CƠ KHÍ XÂY LẮP PHÚC MINH QUANG — Chuyên thi công cửa nhôm Xingfa, cửa kính cường lực, cửa nhựa lõi thép uy tín tại Đà Nẵng.
          </p>
          <ul class="text-xs space-y-1.5 text-blue-100/95">
            <li><strong>Địa chỉ:</strong> 378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng</li>
            <li><strong>Hotline/Zalo:</strong> <a href="tel:0935955652" class="text-amber-300 font-bold hover:underline">0935.955.652</a></li>
            <li><strong>Website:</strong> <a href="https://phucminhquang.com" class="hover:underline">phucminhquang.com</a></li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-white/15">Cửa nhôm Xingfa</h4>
          <ul class="space-y-2 text-xs text-blue-100/90">
            <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="hover:text-amber-300 transition">Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-white/15">Danh mục dịch vụ</h4>
          <ul class="space-y-2 text-xs text-blue-100/90">
            <li><a href="#san-pham-xingfa" class="hover:text-amber-300 transition">Cửa nhôm xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa nhựa lõi thép Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa kính tự động Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cầu thang kính cường lực</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Kính ốp bếp & Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Hỗ trợ khách hàng -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-1.5 border-b border-white/15">Liên kết nhanh</h4>
          <ul class="space-y-2 text-xs text-blue-100/90">
            <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh" class="hover:text-amber-300 transition">Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">Bảng báo giá mới nhất</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức & Kinh nghiệm</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300 transition">Yêu cầu khảo sát miễn phí</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-blue-200/80 pb-14 sm:pb-0">
        <div>Copyright © 2026 <strong>Phúc Minh Quang Window</strong> (phucminhquang.com). All rights reserved.</div>
        <div>378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng • Hotline: 0935.955.652</div>
      </div>
    </div>
  </footer>

  <!-- ==================== 14. CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI) ==================== -->
  <!-- Dạng cột nổi gọn gàng bên phải trên máy tính & máy tính bảng -->
  <div class="hidden sm:flex fixed right-4 bottom-5 z-50 flex-col items-end gap-2.5">
    <a
      href="https://zalo.me/0935955652"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0056D6] text-white px-3.5 py-2.5 rounded-full shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <a
      href="https://www.facebook.com/profile.php?id=100063557834101"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1261C9] text-white px-3.5 py-2.5 rounded-full shadow-lg transition"
    >
      <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
      <span class="text-xs font-bold pr-1">Facebook</span>
    </a>

    <a
      href="tel:0935955652"
      class="hotline-pulse flex items-center gap-2 bg-brand-accent hover:bg-brand-accentDark text-white px-4 py-2.5 rounded-full shadow-xl transition"
    >
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="text-xs font-extrabold tracking-wide">0935.955.652</span>
    </a>
  </div>

  <!-- Thanh liên hệ cố định đáy màn hình trên Điện Thoại (3 nút cân đối 100%, không tràn viền) -->
  <div class="sm:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_16px_rgba(0,0,0,0.08)] px-2 py-2">
    <div class="grid grid-cols-3 gap-2">
      <a href="tel:0935955652" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-brand-accent text-white text-xs font-bold shadow-sm">
        <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
        <span>Hotline</span>
      </a>
      <a href="https://zalo.me/0935955652" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#0068FF] text-white text-xs font-bold shadow-sm">
        <span class="px-1 rounded bg-white text-[#0068FF] text-[10px] font-extrabold leading-tight">Zalo</span>
        <span>Chat Zalo</span>
      </a>
      <a href="https://www.facebook.com/profile.php?id=100063557834101" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 rounded-lg bg-[#1877F2] text-white text-xs font-bold shadow-sm">
        <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
        <span>Facebook</span>
      </a>
    </div>
  </div>

  <!-- ==================== 15. MODAL XEM CHI TIẾT SẢN PHẨM / DANH MỤC / BÀI VIẾT ==================== -->
  <div id="detailModal" class="fixed inset-0 z-[90] hidden items-center justify-center p-3 sm:p-5 bg-slate-900/65 backdrop-blur-[2px]">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-primary leading-snug">Chi tiết</h3>
        <button id="closeModalBtn" type="button" aria-label="Đóng" class="p-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600 transition shrink-0">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modalBody" class="p-5 text-sm text-slate-700 space-y-4"></div>
    </div>
  </div>

  <!-- ==================== 16. JAVASCRIPT XỬ LÝ TƯƠNG TÁC ==================== -->
  <script>
    /**
     * Hàm dự phòng tải ảnh Google Drive nếu URL đầu gặp sự cố mạng hoặc quyền truy cập
     */
    function handleDriveImageError(imgEl, fallbackText) {
      try {
        const driveId = imgEl.getAttribute('data-drive-id');
        const step = Number(imgEl.getAttribute('data-fallback-step') || '0');

        if (step === 0 && driveId) {
          imgEl.setAttribute('data-fallback-step', '1');
          imgEl.src = `https://drive.google.com/thumbnail?id=${driveId}&sz=w1000`;
          return;
        }
        imgEl.onerror = null;
        imgEl.src = `https://placehold.co/600x420/0B4EA2/FFFFFF?text=${fallbackText || 'Phuc+Minh+Quang'}`;
      } catch (e) {
        imgEl.onerror = null;
      }
    }

    /**
     * DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA CHÍNH HÃNG (ĐÚNG LINK ẢNH GOOGLE DRIVE)
     */
    const PRODUCTS = [
      {
        id: 'xingfa-1-canh',
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        filterKey: '1-canh',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.350.000 ₫',
        price: '1.950.000 ₫',
        discount: '-17%',
        specs: [
          'Thanh nhôm Profile Xingfa hệ 55 nhập khẩu chính hãng',
          'Độ dày nhôm: 2.0 mm tiêu chuẩn chịu lực cao',
          'Màu sắc: Xám ghi, đen tuyền, trắng sứ, nâu cafe, vân gỗ',
          'Kính: Kính an toàn 6.38mm hoặc kính cường lực 8mm - 10mm',
          'Phụ kiện Kinlong đồng bộ, gioăng kép EPDM kín khít',
          'Bảo hành chính hãng 5 năm tại Phúc Minh Quang Window'
        ]
      },
      {
        id: 'xingfa-2-canh',
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        filterKey: '2-canh',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.450.000 ₫',
        price: '2.050.000 ₫',
        discount: '-16%',
        specs: [
          'Thanh nhôm Profile Xingfa hệ 55 dày 2.0 mm',
          'Thiết kế mở quay 2 cánh rộng thoáng cho cửa chính, ban công',
          'Chống thấm nước mưa, cách âm cách nhiệt tối ưu cho nhà phố Đà Nẵng',
          'Phụ kiện Kinlong chính hãng, bản lề 3D chịu tải lớn',
          'Ép góc bằng công nghệ máy hiện đại, keo Soudal chuyên dụng',
          'Bảo hành 5 năm thanh nhôm & 2 năm phụ kiện'
        ]
      },
      {
        id: 'xingfa-3-canh',
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        filterKey: '3-canh',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.500.000 ₫',
        price: '2.100.000 ₫',
        discount: '-16%',
        specs: [
          'Thanh nhôm Profile Xingfa hệ 55 độ dày 2.0 mm',
          'Phù hợp mặt tiền nhà ống, phòng khách rộng, quán cafe',
          'Vận hành êm ái, khóa đa điểm chống cạy phá an toàn',
          'Kính an toàn 6.38mm / 8.38mm hoặc kính hộp cách âm',
          'Màu sơn tĩnh điện bền đẹp trước khí hậu gió biển miền Trung',
          'Bảo hành chính hãng 5 năm'
        ]
      },
      {
        id: 'xingfa-4-canh',
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        filterKey: '4-canh',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.550.000 ₫',
        price: '2.150.000 ₫',
        discount: '-15%',
        specs: [
          'Thanh nhôm Profile Xingfa hệ 55 độ dày 2.0 mm chắc chắn',
          'Mở rộng tối đa 100% diện tích lối đi mặt tiền',
          'Chịu được áp lực gió bão lên đến 1600 Pascal',
          'Ốc vít Inox 304 chống han gỉ tuyệt đối',
          'Khảo sát đo đạc và thiết kế kích thước chuẩn phong thủy',
          'Bảo hành 5 năm, hỗ trợ bảo trì trọn đời'
        ]
      },
      {
        id: 'xingfa-xep-truot',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        filterKey: '5-canh',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.650.000 ₫',
        price: '2.200.000 ₫',
        discount: '-17%',
        specs: [
          'Thanh nhôm Profile Xingfa hệ 63 chuyên dụng xếp trượt (4, 5, 6 cánh)',
          'Ray trượt treo chịu lực nhẹ nhàng, xếp gọn sang một hoặc hai bên',
          'Lý tưởng cho biệt thự sân vườn, khách sạn, showroom, mặt tiền lớn',
          'Kính cường lực 8mm - 10mm tăng độ sáng và tầm nhìn không gian',
          'Phụ kiện xếp trượt đồng bộ cao cấp chống kẹt ray',
          'Bảo hành chính hãng 5 năm'
        ]
      },
      {
        id: 'xingfa-so-mo-hat',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        filterKey: '2-canh',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.200.000 ₫',
        price: '1.850.000 ₫',
        discount: '-16%',
        specs: [
          'Thanh nhôm Profile Xingfa hệ 55 độ dày 1.4 mm',
          'Mở hất góc 45 độ giúp thông gió ngay cả khi trời mưa nhỏ',
          'Thanh định vị chống va đập khi có gió mạnh',
          'Gioăng kép EPDM ngăn nước mưa và giảm tiếng ồn hiệu quả',
          'Tương thích nhiều loại kính: kính mờ, kính phản quang, kính hộp',
          'Bảo hành chính hãng 5 năm'
        ]
      }
    ];

    /**
     * DỮ LIỆU 6 DANH MỤC SẢN PHẨM NỔI BẬT (THEO MẪU NGOCHANWINDOW.COM & LINK GOOGLE DRIVE)
     */
    const CATEGORIES = [
      {
        key: 'cua-nhom-xingfa',
        title: 'Cửa nhôm xingfa',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        desc: 'Cửa đi mở quay 1-4 cánh, cửa xếp trượt, cửa sổ mở hất, mở lùa sử dụng nhôm Xingfa nhập khẩu tem đỏ, phụ kiện Kinlong đồng bộ.'
      },
      {
        key: 'cua-nhua-loi-thep',
        title: 'Cửa nhựa lõi thép',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        desc: 'Cửa nhựa uPVC lõi thép gia cường cách âm, cách nhiệt tốt, chống cong vênh mối mọt, chi phí đầu tư tiết kiệm cho nhà ở và văn phòng.'
      },
      {
        key: 'cua-tu-dong',
        title: 'Cửa kính tự động',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        desc: 'Hệ thống cửa kính trượt tự động cảm biến mắt thần thông minh, vận hành êm ái cho khách sạn, showroom, siêu thị, tòa nhà thương mại.'
      },
      {
        key: 'cau-thang-kinh',
        title: 'Cầu thang kính',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        desc: 'Lan can cầu thang kính cường lực 10mm - 12mm kết hợp tay vịn gỗ hoặc inox 304, mở rộng không gian và tăng nét sang trọng hiện đại.'
      },
      {
        key: 'kinh-op-bep',
        title: 'Kính ốp bếp',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        desc: 'Kính cường lực sơn màu chịu nhiệt đa dạng gam màu hiện đại, bề mặt phẳng mịn chống bám dầu mỡ, cực kỳ dễ lau chùi cho gian bếp.'
      },
      {
        key: 'phong-tam-kinh',
        title: 'Phòng tắm kính',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        desc: 'Vách tắm kính cường lực 10mm phụ kiện inox 304 chống gỉ (mở quay 90°, 135°, cửa lùa), ngăn nước tuyệt đối, giữ phòng tắm khô ráo.'
      }
    ];

    /**
     * DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (ĐÚNG LINK ẢNH GOOGLE DRIVE)
     */
    const PROJECTS = [
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        category: 'resort',
        location: 'Quảng Nam - Đà Nẵng',
        scope: 'Thi công hệ thống cửa nhôm Xingfa & vách kính mặt dựng khu nghỉ dưỡng',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        category: 'khach-san',
        location: 'Tp. Đà Nẵng',
        scope: 'Cung cấp lắp đặt cửa nhôm kính Xingfa & phòng tắm kính cường lực',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy'
      },
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        category: 'khach-san',
        location: 'Tp. Đà Nẵng',
        scope: 'Thi công trọn gói cửa nhôm Xingfa cách âm & lan can kính ban công',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        category: 'khach-san',
        location: 'Ven biển Mỹ Khê, Đà Nẵng',
        scope: 'Hệ cửa nhôm kính chịu gió biển, cửa kính tự động sảnh lễ tân',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        category: 'khach-san',
        location: 'Tp. Đà Nẵng',
        scope: 'Thi công cửa đi nhôm Xingfa, vách kính ngăn phòng và phòng tắm kính',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        category: 'khach-san',
        location: 'Tp. Đà Nẵng',
        scope: 'Thi công đồng bộ cửa sổ nhôm Xingfa, cửa kính cường lực & vách mặt tiền',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt'
      }
    ];

    /**
     * DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ
     */
    const ARTICLES = [
      {
        id: 'art-1',
        category: 'tu-van',
        categoryLabel: 'Tư vấn chọn cửa',
        date: '15/11/2026',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu miền Trung - Đà Nẵng không?',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        excerpt: 'Khí hậu ven biển Đà Nẵng nhiều nắng gió và mưa bão đòi hỏi hệ cửa có kết cấu vững chắc, sơn tĩnh điện bền màu và kín nước tuyệt đối.',
        content: 'Nhôm Xingfa nhập khẩu sở hữu cấu trúc thanh Profile khoang rỗng kết hợp các đường gân gia cường giúp chịu áp lực gió lên đến 1600 Pascal. Bề mặt phủ sơn tĩnh điện ngoài trời cao cấp chống oxy hóa từ hơi muối biển, kết hợp hệ gioăng EPDM kép và rãnh thoát nước thông minh ngăn nước mưa tràn vào nhà hiệu quả.'
      },
      {
        id: 'art-2',
        category: 'ky-thuat',
        categoryLabel: 'Kỹ thuật & Độ bền',
        date: '10/11/2026',
        title: 'Cửa nhôm Xingfa có tiết kiệm năng lượng và cách âm tốt không?',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        excerpt: 'Tìm hiểu cơ chế cách âm, cách nhiệt của thanh nhôm Xingfa kết hợp kính hộp và gioăng cao su kép giúp giảm chi phí điện điều hòa.',
        content: 'Nhờ công nghệ ép góc toàn khối chuẩn xác cùng gioăng EPDM đàn hồi cao, cửa nhôm Xingfa tạo nên độ kín khít gần như tuyệt đối. Điều này ngăn thất thoát hơi lạnh điều hòa ra bên ngoài, tiết kiệm đáng kể điện năng đồng thời giảm tiếng ồn xe cộ ở các tuyến đường lớn.'
      },
      {
        id: 'art-3',
        category: 'bao-gia',
        categoryLabel: 'Báo giá & So sánh',
        date: '05/11/2026',
        title: 'So sánh cửa nhôm Xingfa và cửa nhựa lõi thép: Nên chọn loại nào?',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        excerpt: 'Phân tích chi tiết ưu nhược điểm về độ bền, tính thẩm mỹ, khả năng chịu lực và mức giá thi công của hai dòng cửa phổ biến nhất.',
        content: 'Cửa nhôm Xingfa nổi bật với khung thanh mảnh, chịu lực gió bão vượt trội và đa dạng màu sắc hiện đại (xám ghi, đen, vân gỗ). Trong khi đó, cửa nhựa lõi thép uPVC có thế mạnh về cách âm tốt và giá thành mềm hơn. Phúc Minh Quang Window luôn tư vấn kết hợp hợp lý theo từng vị trí cửa trong công trình.'
      },
      {
        id: 'art-4',
        category: 'ky-thuat',
        categoryLabel: 'Kỹ thuật & Độ bền',
        date: '28/10/2026',
        title: 'Cửa nhôm Xingfa có chống trộm an toàn cho nhà phố không?',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        excerpt: 'Hệ khóa đa điểm Kinlong kết hợp kính dán an toàn 2 lớp hoặc kính cường lực mang lại lớp bảo vệ vững chắc cho ngôi nhà.',
        content: 'Khi được gia công đúng kỹ thuật với thanh nhôm dày 2.0mm, khóa đa điểm chốt âm và kính an toàn 6.38mm/8.38mm, cửa nhôm Xingfa có khả năng chống cạy phá rất cao. Chủ nhà có thể lắp thêm cảm biến báo động hoặc khung bảo vệ tăng cường an ninh.'
      },
      {
        id: 'art-5',
        category: 'tu-van',
        categoryLabel: 'Tư vấn chọn cửa',
        date: '20/10/2026',
        title: 'Kinh nghiệm lắp đặt phòng tắm kính & cầu thang kính bền đẹp',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        excerpt: 'Những tiêu chuẩn quan trọng về độ dày kính cường lực, phụ kiện inox 304 chống gỉ và kỹ thuật đi keo silicon chống thấm.',
        content: 'Đối với phòng tắm kính và cầu thang kính, nên ưu tiên kính cường lực chuẩn 10mm - 12mm cùng bộ phụ kiện inox 304 chính hãng để tránh han gỉ trong môi trường ẩm ướt. Quá trình đo đạc thực tế chính xác từng milimet sẽ giúp cánh cửa vận hành êm nhẹ và kín nước.'
      },
      {
        id: 'art-6',
        category: 'bao-gia',
        categoryLabel: 'Báo giá & So sánh',
        date: '12/10/2026',
        title: 'Kinh nghiệm chọn đơn vị gia công cửa nhôm kính uy tín tại Đà Nẵng',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        excerpt: '5 tiêu chí giúp chủ đầu tư nhận biết xưởng sản xuất trực tiếp uy tín, báo giá minh bạch và chế độ bảo hành rõ ràng.',
        content: 'Để sở hữu bộ cửa bền đẹp hàng chục năm, khách hàng nên kiểm tra trực tiếp xưởng sản xuất, nguồn gốc thanh nhôm Xingfa, phụ kiện đồng bộ, ốc vít inox và hợp đồng bảo hành. Phúc Minh Quang Window tại 378 Âu Cơ, Liên Chiểu luôn sẵn sàng đón khách tham quan mẫu thực tế.'
      }
    ];

    /* ==================== RENDER SẢN PHẨM ==================== */
    function renderProducts(list) {
      const grid = document.getElementById('productGrid');
      if (!grid) return;

      if (!list.length) {
        grid.innerHTML = `<div class="col-span-2 md:col-span-3 bg-white rounded-xl border border-slate-200 p-8 text-center text-sm text-slate-500">Không tìm thấy sản phẩm phù hợp. Vui lòng thử từ khóa khác hoặc bấm "Tất cả".</div>`;
        return;
      }

      grid.innerHTML = list.map((p) => `
        <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary/40 transition flex flex-col">
          <!-- Khung ảnh sản phẩm + Giảm giá % góc trên bên trái -->
          <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductDetail('${p.id}')">
            <span class="absolute top-2 left-2 z-10 px-2 py-0.5 rounded bg-brand-accent text-white text-[11px] font-bold shadow">
              ${p.discount}
            </span>
            <img
              src="https://lh3.googleusercontent.com/d/${p.driveId}"
              alt="${p.name}"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              data-drive-id="${p.driveId}"
              onerror="handleDriveImageError(this, 'San+Pham')"
              loading="lazy"
            />
          </div>

          <!-- Nội dung thẻ sản phẩm: Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ trên mobile 2 cột -->
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col">
            <h3
              onclick="openProductDetail('${p.id}')"
              class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-primary leading-snug break-words cursor-pointer mb-2"
            >
              ${p.name}
            </h3>

            <div class="mt-auto space-y-2.5">
              <!-- Giá bán & giá gốc -->
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-sm sm:text-base font-extrabold text-brand-accent">${p.price}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.oldPrice}</span>
              </div>

              <div class="grid grid-cols-2 gap-1.5">
                <button
                  type="button"
                  onclick="openProductDetail('${p.id}')"
                  class="py-1.5 sm:py-2 px-2 rounded-lg bg-brand-light hover:bg-blue-100 text-brand-primary text-[11px] sm:text-xs font-semibold transition"
                >
                  Chi tiết
                </button>
                <button
                  type="button"
                  onclick="requestQuoteFor('${p.name.replace(/'/g, "\\'")}')"
                  class="py-1.5 sm:py-2 px-2 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-[11px] sm:text-xs font-semibold transition"
                >
                  Báo giá
                </button>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterProducts(key) {
      document.querySelectorAll('.product-filter-btn').forEach((btn) => {
        const isActive = btn.getAttribute('data-filter-btn') === key;
        btn.className = isActive
          ? 'product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition'
          : 'product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-primary hover:text-brand-primary transition';
      });
      if (key === 'all') {
        renderProducts(PRODUCTS);
      } else {
        renderProducts(PRODUCTS.filter((p) => p.filterKey === key));
      }
    }

    /* ==================== RENDER DANH MỤC SẢN PHẨM NỔI BẬT ==================== */
    function renderCategories() {
      const grid = document.getElementById('categoryGrid');
      if (!grid) return;

      grid.innerHTML = CATEGORIES.map((c) => `
        <div
          onclick="openCategoryDetail('${c.key}')"
          class="group bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary/50 transition cursor-pointer flex flex-col"
        >
          <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
            <img
              src="https://lh3.googleusercontent.com/d/${c.driveId}"
              alt="${c.title}"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              data-drive-id="${c.driveId}"
              onerror="handleDriveImageError(this, '${encodeURIComponent(c.title)}')"
              loading="lazy"
            />
          </div>
          <div class="p-3 sm:p-4 bg-white flex-1 flex flex-col justify-between text-center">
            <h3 class="text-xs sm:text-sm font-extrabold text-brand-primary uppercase tracking-wide group-hover:text-brand-dark">
              ${c.title}
            </h3>
            <p class="hidden sm:block text-xs text-slate-500 mt-1.5 leading-relaxed">${c.desc}</p>
          </div>
        </div>
      `).join('');
    }

    /* ==================== RENDER DỰ ÁN TIÊU BIỂU ==================== */
    function renderProjects(list) {
      const grid = document.getElementById('projectGrid');
      if (!grid) return;

      grid.innerHTML = list.map((proj) => `
        <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
            <img
              src="https://lh3.googleusercontent.com/d/${proj.driveId}"
              alt="${proj.title}"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              data-drive-id="${proj.driveId}"
              onerror="handleDriveImageError(this, 'Du+An+Da+Nang')"
              loading="lazy"
            />
          </div>
          <div class="p-4 bg-white flex-1 flex flex-col">
            <div class="text-[11px] font-semibold text-brand-primary mb-1">${proj.location}</div>
            <h3 class="text-xs sm:text-sm font-bold text-slate-900 leading-snug mb-2">
              ${proj.title}
            </h3>
            <p class="text-xs text-slate-500 leading-relaxed mt-auto">${proj.scope}</p>
          </div>
        </article>
      `).join('');
    }

    function filterProjects(cat) {
      document.querySelectorAll('.project-filter-btn').forEach((btn) => {
        const isActive = btn.getAttribute('data-project-btn') === cat;
        btn.className = isActive
          ? 'project-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition'
          : 'project-filter-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition';
      });
      if (cat === 'all') {
        renderProjects(PROJECTS);
      } else {
        renderProjects(PROJECTS.filter((p) => p.category === cat));
      }
    }

    /* ==================== RENDER BÀI VIẾT TIN TỨC ==================== */
    function renderArticles(list) {
      const grid = document.getElementById('articleGrid');
      if (!grid) return;

      grid.innerHTML = list.map((art) => `
        <article
          onclick="openArticleDetail('${art.id}')"
          class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary/40 transition cursor-pointer flex flex-col"
        >
          <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
            <img
              src="https://lh3.googleusercontent.com/d/${art.driveId}"
              alt="${art.title}"
              class="w-full h-full object-cover hover:scale-105 transition duration-300"
              data-drive-id="${art.driveId}"
              onerror="handleDriveImageError(this, 'Tin+Tuc')"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col">
            <div class="flex items-center justify-between text-[11px] text-slate-500 mb-1.5">
              <span class="font-semibold text-brand-primary">${art.categoryLabel}</span>
              <span>${art.date}</span>
            </div>
            <h3 class="text-sm font-bold text-slate-900 leading-snug mb-2 hover:text-brand-primary">
              ${art.title}
            </h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-3 flex-1">${art.excerpt}</p>
            <span class="text-xs font-bold text-brand-primary">Đọc tiếp →</span>
          </div>
        </article>
      `).join('');
    }

    function filterArticles(cat) {
      document.querySelectorAll('.article-filter-btn').forEach((btn) => {
        const isActive = btn.getAttribute('data-article-btn') === cat;
        btn.className = isActive
          ? 'article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white transition'
          : 'article-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-primary transition';
      });
      if (cat === 'all') {
        renderArticles(ARTICLES);
      } else {
        renderArticles(ARTICLES.filter((a) => a.category === cat));
      }
    }

    /* ==================== MODAL CHI TIẾT ==================== */
    const modalEl = document.getElementById('detailModal');
    const modalTitleEl = document.getElementById('modalTitle');
    const modalBodyEl = document.getElementById('modalBody');

    function openModal(title, htmlContent) {
      modalTitleEl.textContent = title;
      modalBodyEl.innerHTML = htmlContent;
      modalEl.classList.remove('hidden');
      modalEl.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeModal() {
      modalEl.classList.add('hidden');
      modalEl.classList.remove('flex');
      document.body.style.overflow = '';
    }

    document.getElementById('closeModalBtn').addEventListener('click', closeModal);
    modalEl.addEventListener('click', (e) => {
      if (e.target === modalEl) closeModal();
    });

    function openProductDetail(id) {
      const p = PRODUCTS.find((item) => item.id === id);
      if (!p) return;
      openModal(p.name, `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 items-start">
          <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
            <span class="absolute top-2 left-2 px-2.5 py-0.5 rounded bg-brand-accent text-white text-xs font-bold">${p.discount}</span>
            <img src="https://lh3.googleusercontent.com/d/${p.driveId}" alt="${p.name}" class="w-full h-56 object-cover" data-drive-id="${p.driveId}" onerror="handleDriveImageError(this, 'San+Pham')" />
          </div>
          <div class="space-y-3">
            <div>
              <div class="text-xs text-slate-500">Giá thi công hoàn thiện tham khảo:</div>
              <div class="flex items-baseline gap-2 mt-0.5">
                <span class="text-xl font-extrabold text-brand-accent">${p.price}/m²</span>
                <span class="text-xs text-slate-400 line-through">${p.oldPrice}</span>
              </div>
            </div>
            <ul class="space-y-1.5 text-xs sm:text-sm text-slate-700 list-disc pl-4">
              ${p.specs.map((s) => `<li>${s}</li>`).join('')}
            </ul>
          </div>
        </div>
        <div class="pt-3 border-t border-slate-200 flex flex-wrap gap-2.5 justify-end">
          <a href="tel:0935955652" class="px-4 py-2 rounded-lg bg-brand-accent text-white text-xs sm:text-sm font-bold hover:bg-brand-accentDark transition">Gọi 0935.955.652</a>
          <button type="button" onclick="closeModal(); requestQuoteFor('${p.name.replace(/'/g, "\\'")}')" class="px-4 py-2 rounded-lg bg-brand-primary text-white text-xs sm:text-sm font-bold hover:bg-brand-dark transition">Đăng ký báo giá mẫu này</button>
        </div>
      `);
    }

    function openCategoryDetail(key) {
      const c = CATEGORIES.find((item) => item.key === key);
      if (!c) return;
      openModal(`Danh mục: ${c.title}`, `
        <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
          <img src="https://lh3.googleusercontent.com/d/${c.driveId}" alt="${c.title}" class="w-full h-60 object-cover" data-drive-id="${c.driveId}" onerror="handleDriveImageError(this, 'Danh+Muc')" />
        </div>
        <p class="text-sm text-slate-700 leading-relaxed">${c.desc}</p>
        <div class="bg-brand-light rounded-xl p-3.5 text-xs text-slate-700 space-y-1">
          <div class="font-bold text-brand-primary">Ưu đãi thi công tại Phúc Minh Quang Window:</div>
          <div>• Miễn phí đo đạc, tư vấn mẫu thực tế tại Đà Nẵng.</div>
          <div>• Báo giá minh bạch, bảo hành dài hạn, hỗ trợ kỹ thuật nhanh chóng.</div>
        </div>
        <div class="flex flex-wrap gap-2.5 justify-end pt-2">
          <a href="https://zalo.me/0935955652" target="_blank" rel="noopener noreferrer" class="px-4 py-2 rounded-lg bg-[#0068FF] text-white text-xs sm:text-sm font-bold">Tư vấn qua Zalo</a>
          <button type="button" onclick="closeModal(); requestQuoteFor('${c.title.replace(/'/g, "\\'")}')" class="px-4 py-2 rounded-lg bg-brand-primary text-white text-xs sm:text-sm font-bold">Nhận báo giá ${c.title}</button>
        </div>
      `);
    }

    function openArticleDetail(id) {
      const a = ARTICLES.find((item) => item.id === id);
      if (!a) return;
      openModal(a.title, `
        <div class="flex items-center gap-3 text-xs text-slate-500">
          <span class="font-bold text-brand-primary">${a.categoryLabel}</span>
          <span>•</span>
          <span>Ngày đăng: ${a.date}</span>
        </div>
        <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
          <img src="https://lh3.googleusercontent.com/d/${a.driveId}" alt="${a.title}" class="w-full h-60 object-cover" data-drive-id="${a.driveId}" onerror="handleDriveImageError(this, 'Bai+Viet')" />
        </div>
        <p class="text-sm font-medium text-slate-800 leading-relaxed">${a.excerpt}</p>
        <p class="text-sm text-slate-700 leading-relaxed">${a.content}</p>
        <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-xs text-slate-600">
          Cần tư vấn trực tiếp cho công trình tại Đà Nẵng? Liên hệ <strong>Phúc Minh Quang Window</strong> qua Hotline/Zalo <a href="tel:0935955652" class="text-brand-accent font-bold">0935.955.652</a> hoặc ghé xưởng 378 Âu Cơ, Liên Chiểu, Tp.Đà Nẵng.
        </div>
      `);
    }

    /* ==================== ĐIỀN SẴN FORM BÁO GIÁ ==================== */
    function requestQuoteFor(itemName) {
      const noteEl = document.getElementById('qNote');
      const formSection = document.getElementById('form-bao-gia');
      if (noteEl) {
        noteEl.value = `Tôi muốn nhận báo giá chi tiết cho hạng mục: ${itemName}`;
      }
      if (formSection) {
        formSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    }

    /* ==================== XỬ LÝ SLIDER 2 BANNER TỰ TRƯỢT + VUỐT CẢM ỨNG ==================== */
    let currentSlide = 0;
    let sliderTimer = null;
    const slides = document.querySelectorAll('#heroSlider .hero-slide');
    const dots = document.querySelectorAll('#heroSlider .slide-dot');

    function showSlide(index) {
      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((s, i) => {
        s.classList.toggle('is-active', i === currentSlide);
      });
      dots.forEach((d, i) => {
        if (i === currentSlide) {
          d.classList.add('w-7', 'bg-white');
          d.classList.remove('w-2.5', 'bg-white/45');
        } else {
          d.classList.remove('w-7', 'bg-white');
          d.classList.add('w-2.5', 'bg-white/45');
        }
      });
    }

    function startAutoSlide() {
      clearInterval(sliderTimer);
      sliderTimer = setInterval(() => showSlide(currentSlide + 1), 5000);
    }

    document.getElementById('prevSlideBtn').addEventListener('click', () => {
      showSlide(currentSlide - 1);
      startAutoSlide();
    });

    document.getElementById('nextSlideBtn').addEventListener('click', () => {
      showSlide(currentSlide + 1);
      startAutoSlide();
    });

    dots.forEach((dot) => {
      dot.addEventListener('click', () => {
        showSlide(Number(dot.getAttribute('data-slide-dot')));
        startAutoSlide();
      });
    });

    // Hỗ trợ vuốt trái/phải banner trên điện thoại
    let touchStartX = 0;
    const heroSliderEl = document.getElementById('heroSlider');
    heroSliderEl.addEventListener('touchstart', (e) => {
      touchStartX = e.changedTouches[0].screenX;
    }, { passive: true });
    heroSliderEl.addEventListener('touchend', (e) => {
      const diff = e.changedTouches[0].screenX - touchStartX;
      if (Math.abs(diff) > 40) {
        showSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
        startAutoSlide();
      }
    }, { passive: true });

    /* ==================== MOBILE DRAWER MENU & ACCORDION ==================== */
    const mobileDrawer = document.getElementById('mobileDrawer');
    const mobileBackdrop = document.getElementById('mobileDrawerBackdrop');

    function openMobileMenu() {
      mobileDrawer.classList.remove('-translate-x-full');
      mobileBackdrop.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeMobileMenu() {
      mobileDrawer.classList.add('-translate-x-full');
      mobileBackdrop.classList.add('hidden');
      document.body.style.overflow = '';
    }

    document.getElementById('mobileMenuBtn').addEventListener('click', openMobileMenu);
    document.getElementById('closeMobileMenuBtn').addEventListener('click', closeMobileMenu);
    mobileBackdrop.addEventListener('click', closeMobileMenu);

    document.querySelectorAll('.mobile-nav-link').forEach((link) => {
      link.addEventListener('click', closeMobileMenu);
    });

    document.querySelectorAll('.mobile-accordion-btn').forEach((btn) => {
      btn.addEventListener('click', () => {
        const panel = btn.nextElementSibling;
        const icon = btn.querySelector('svg');
        if (panel) panel.classList.toggle('hidden');
        if (icon) icon.classList.toggle('rotate-180');
      });
    });

    /* ==================== TÌM KIẾM SẢN PHẨM ==================== */
    function handleProductSearch(keyword) {
      const q = (keyword || '').trim().toLowerCase();
      const filtered = q
        ? PRODUCTS.filter((p) => p.name.toLowerCase().includes(q))
        : PRODUCTS;
      renderProducts(filtered);
      const section = document.getElementById('san-pham-xingfa');
      if (section) section.scrollIntoView({ behavior: 'smooth', block: 'start' });
    }

    document.getElementById('headerSearchForm').addEventListener('submit', (e) => {
      e.preventDefault();
      handleProductSearch(document.getElementById('headerSearchInput').value);
    });

    document.getElementById('mobileSearchForm').addEventListener('submit', (e) => {
      e.preventDefault();
      closeMobileMenu();
      handleProductSearch(document.getElementById('mobileSearchInput').value);
    });

    /* ==================== FORM YÊU CẦU BÁO GIÁ ==================== */
    document.getElementById('quoteForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const cat = document.getElementById('qCategory').value;
      const feedbackEl = document.getElementById('quoteFeedback');

      feedbackEl.textContent = `Cảm ơn ${name}! Phúc Minh Quang Window đã tiếp nhận yêu cầu báo giá "${cat}" qua số ${phone}. Kỹ thuật viên sẽ liên hệ tư vấn trong ít phút (Hotline: 0935.955.652).`;
      feedbackEl.classList.remove('hidden');
      e.target.reset();
    });

    /* ==================== KHỞI CHẠY TRANG ==================== */
    window.addEventListener('DOMContentLoaded', () => {
      renderProducts(PRODUCTS);
      renderCategories();
      renderProjects(PROJECTS);
      renderArticles(ARTICLES);
      startAutoSlide();
    });
  </script>
</body>
</html>
