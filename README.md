<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186 | dienmay186.com</title>
  <meta name="description" content="CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186 chuyên cung cấp bếp điện đôi, bếp từ, máy hút mùi, máy lọc nước, máy rửa bát, thiết bị nhà bếp thông minh chính hãng tại Đà Nẵng. Hotline: 0366.479.999">
  
  <!-- Meta Open Graph Thumbnail là Logo trang web khi chia sẻ link -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://dienmay186.com/">
  <meta property="og:title" content="CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186 - dienmay186.com">
  <meta property="og:description" content="Thiết bị nhà bếp thông minh & Điện máy chính hãng. Địa chỉ: 155/61 Trần Đình Nam, Phường An Khê, TP. Đà Nẵng. Hotline: 0366.479.999">
  <meta property="og:image" content="https://placehold.co/600x315/0a4275/ffffff?text=DIEN+MAY+THIET+BI+BEP+186">
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='18' fill='%230a4275'/%3E%3Cpath d='M25 32h50v8H25zm8 18h34v6H33zm-8 16h50v8H25z' fill='%23e31837'/%3E%3Ctext x='50' y='62' font-family='Arial' font-weight='900' font-size='28' fill='%23ffffff' text-anchor='middle'%3E186%3C/text%3E%3C/svg%3E">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Inter & Font Awesome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              DEFAULT: '#0a4275', // Màu xanh đậm chủ đạo theo logo
              light: '#125a9c',
              dark: '#062c4f',
              accent: '#e31837', // Màu đỏ điểm nhấn theo logo & giảm giá Flatsome
              bg: '#f4f6f8'
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif']
          },
          maxWidth: {
            'site': '1500px'
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
      background-color: #f4f6f8;
      color: #1f2937;
      scroll-behavior: smooth;
    }

    /* Khung chuẩn 1500px theo yêu cầu cho UX Builder Flatsome */
    .container-1500 {
      width: 100%;
      max-width: 1500px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .container-1500 {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng không xuống dòng nội bộ */
    .desktop-cat-link {
      white-space: nowrap;
      font-size: 12.5px;
      line-height: 1.2;
      padding: 8px 10px;
      transition: all 0.2s ease;
    }
    .desktop-cat-link:hover {
      background-color: rgba(255, 255, 255, 0.15);
      border-radius: 4px;
    }

    /* Chuẩn thẻ sản phẩm Flatsome */
    .flatsome-product-box {
      background: #ffffff;
      border: 1px solid #e5e7eb;
      border-radius: 6px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      display: flex;
      flex-direction: column;
      height: 100%;
      position: relative;
      overflow: hidden;
    }
    .flatsome-product-box:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 20px -4px rgba(10, 66, 117, 0.12);
      border-color: #0a4275;
    }

    /* Badge giảm giá chuẩn Flatsome góc trên bên trái */
    .flatsome-Discount-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #e31837;
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
      line-height: 1;
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ (...) hay tràn ra ngoài */
    .product-title-full {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.38;
    }

    /* Tiêu đề Section chuẩn Flatsome */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #0a4275;
      margin-bottom: 16px;
      background: #ffffff;
      border-radius: 6px 6px 0 0;
    }
    .flatsome-section-title h2 {
      background-color: #0a4275;
      color: #ffffff;
      font-weight: 700;
      padding: 10px 18px;
      margin: 0;
      font-size: 15px;
      text-transform: uppercase;
      border-radius: 6px 6px 0 0;
      position: relative;
    }

    /* Hiệu ứng rung nhẹ cho nút nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(227, 24, 55, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(227, 24, 55, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(227, 24, 55, 0); }
    }
    .floating-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- =========================================================
       TOP BAR (Đơn giản chuẩn Flatsome)
       ========================================================= -->
  <div class="bg-brand-dark text-white text-xs py-1.5 border-b border-white/10">
    <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-4 truncate">
        <span><i class="fa-solid fa-building mr-1.5 text-amber-400"></i>CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186</span>
        <span class="hidden md:inline-block text-white/40">|</span>
        <span class="hidden md:inline-block truncate"><i class="fa-solid fa-location-dot mr-1.5 text-red-400"></i>155/61 Trần Đình Nam, Phường An Khê, TP. Đà Nẵng</span>
      </div>
      <div class="flex items-center gap-4 ml-auto">
        <a href="#form-bao-gia" class="hover:text-amber-300 transition"><i class="fa-solid fa-file-invoice mr-1"></i>Nhận báo giá</a>
        <span class="text-white/40">|</span>
        <a href="#tin-tuc" class="hover:text-amber-300 transition"><i class="fa-solid fa-newspaper mr-1"></i>Tin tức</a>
        <span class="text-white/40">|</span>
        <a href="#lien-he-map" class="hover:text-amber-300 transition"><i class="fa-solid fa-map-location-dot mr-1"></i>Bản đồ</a>
      </div>
    </div>
  </div>

  <!-- =========================================================
       HEADER CHÍNH (Logo gọn nhỏ, Không để nút Gọi ngay tránh tràn viền)
       ========================================================= -->
  <header class="bg-white shadow-sm sticky top-0 z-40">
    <div class="container-1500 py-2.5">
      <div class="flex items-center justify-between gap-3">
        
        <!-- Nút mở Menu danh mục trên Điện thoại -->
        <button id="mobileMenuBtn" onclick="toggleMobileDrawer(true)" aria-label="Mở danh mục" class="lg:hidden flex items-center justify-center w-9 h-9 rounded bg-brand text-white shrink-0">
          <i class="fa-solid fa-bars text-base"></i>
        </button>

        <!-- LOGO MỚI: Thiết kế chỉnh gọn nhỏ lại, sắc nét theo tông màu chủ đạo -->
        <a href="#" class="flex items-center gap-2 shrink-0 group" title="CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186">
          <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0 rounded-lg shadow-sm" viewBox="0 0 120 120" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="120" height="120" rx="20" fill="#0a4275"/>
            <rect x="6" y="6" width="108" height="108" rx="16" stroke="#ffffff" stroke-opacity="0.2" stroke-width="2"/>
            <!-- Biểu tượng ngọn lửa / vòng nhiệt bếp từ cách điệu -->
            <path d="M32 32H88" stroke="#e31837" stroke-width="7" stroke-linecap="round"/>
            <circle cx="44" cy="32" r="3.5" fill="#ffffff"/>
            <circle cx="76" cy="32" r="3.5" fill="#ffffff"/>
            <!-- Số 186 nổi bật -->
            <text x="60" y="75" font-family="Inter, Arial, sans-serif" font-weight="900" font-size="38" fill="#ffffff" text-anchor="middle" letter-spacing="-1">186</text>
            <!-- Dải đỏ chân logo -->
            <rect x="22" y="88" width="76" height="14" rx="4" fill="#e31837"/>
            <text x="60" y="98" font-family="Inter, Arial, sans-serif" font-weight="700" font-size="8.5" fill="#ffffff" text-anchor="middle" letter-spacing="0.8">ĐIỆN MÁY - BẾP</text>
          </svg>
          <div class="leading-tight">
            <div class="text-xs sm:text-sm font-extrabold text-brand tracking-tight uppercase">ĐIỆN MÁY - BẾP 186</div>
            <div class="text-[10px] sm:text-[11px] font-semibold text-brand-accent tracking-wide">dienmay186.com</div>
          </div>
        </a>

        <!-- Thanh tìm kiếm sản phẩm (Trên máy tính) -->
        <div class="hidden md:flex flex-1 max-w-xl mx-4">
          <div class="relative flex w-full">
            <input id="desktopSearchInput" type="text" placeholder="Tìm bếp điện đôi, máy hút mùi, máy lọc nước, máy rửa bát..." 
              class="w-full pl-3.5 pr-10 py-2 text-xs sm:text-sm border border-gray-300 rounded-l-md focus:outline-none focus:border-brand"
              oninput="filterProductsBySearch(this.value)">
            <button onclick="filterProductsBySearch(document.getElementById('desktopSearchInput').value)" class="bg-brand hover:bg-brand-light text-white px-4 py-2 rounded-r-md text-sm font-medium transition">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </div>
        </div>

        <!-- Khu vực tiện ích bên phải (Không đặt nút gọi ngay để tránh tràn viền) -->
        <div class="flex items-center gap-2 sm:gap-3 shrink-0">
          <a href="#san-pham-chinh" class="hidden xl:flex items-center gap-1.5 text-xs font-semibold text-gray-700 hover:text-brand px-2.5 py-1.5 rounded bg-gray-100">
            <i class="fa-solid fa-table-cells-large text-brand"></i>
            <span>Sản phẩm</span>
          </a>
          <a href="#form-bao-gia" class="flex items-center gap-1.5 text-xs font-semibold text-white bg-brand hover:bg-brand-light px-2.5 sm:px-3 py-2 rounded transition">
            <i class="fa-solid fa-paper-plane text-[11px]"></i>
            <span>Báo giá</span>
          </a>
        </div>

      </div>

      <!-- Thanh tìm kiếm gọn trên điện thoại -->
      <div class="mt-2 md:hidden">
        <div class="relative flex w-full">
          <input id="mobileSearchInput" type="text" placeholder="Tìm tên sản phẩm, mã bếp, máy hút mùi..." 
            class="w-full pl-3 pr-9 py-1.5 text-xs border border-gray-300 rounded-l focus:outline-none focus:border-brand"
            oninput="filterProductsBySearch(this.value)">
          <button onclick="filterProductsBySearch(document.getElementById('mobileSearchInput').value)" class="bg-brand text-white px-3 py-1.5 rounded-r text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- =========================================================
         THANH DANH MỤC TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền 1 hàng, không đứt dòng tên danh mục)
         ========================================================= -->
    <nav class="hidden lg:block bg-brand text-white border-t border-brand-light">
      <div class="container-1500">
        <ul class="flex flex-wrap items-center justify-start gap-x-1 gap-y-0.5 py-1">
          <li>
            <a href="#san-pham-chinh" onclick="selectCategory('all'); return false;" class="desktop-cat-link inline-flex items-center gap-1.5 font-bold bg-brand-accent text-white rounded">
              <i class="fa-solid fa-house text-[11px]"></i><span>TRANG CHỦ</span>
            </a>
          </li>
          <li><a href="#cat-bep-doi" class="desktop-cat-link inline-block font-medium">BẾP ĐIỆN ĐÔI</a></li>
          <li><a href="#cat-bep-don" class="desktop-cat-link inline-block font-medium">BẾP ĐIỆN ĐƠN</a></li>
          <li><a href="#cat-hut-mui" class="desktop-cat-link inline-block font-medium">MÁY HÚT MÙI</a></li>
          <li><a href="#cat-loc-nuoc" class="desktop-cat-link inline-block font-medium">MÁY LỌC NƯỚC</a></li>
          <li><a href="#cat-bo-noi" class="desktop-cat-link inline-block font-medium">BỘ NỒI CAO CẤP</a></li>
          <li><a href="#cat-loc-khi" class="desktop-cat-link inline-block font-medium">MÁY LỌC KHÔNG KHÍ</a></li>
          <li><a href="#cat-sua-hat" class="desktop-cat-link inline-block font-medium">MÁY LÀM SỮA HẠT</a></li>
          <li><a href="#cat-noi-chien" class="desktop-cat-link inline-block font-medium">NỒI CHIÊN KHÔNG DẦU</a></li>
          <li><a href="#cat-rua-bat" class="desktop-cat-link inline-block font-medium">MÁY RỬA BÁT</a></li>
          <li><a href="#cat-hut-am" class="desktop-cat-link inline-block font-medium">MÁY HÚT ẨM</a></li>
          <li><a href="#cat-may-giat" class="desktop-cat-link inline-block font-medium">MÁY GIẶT</a></li>
          <li><a href="#doi-tac" class="desktop-cat-link inline-block font-medium text-amber-300">ĐỐI TÁC</a></li>
          <li><a href="#tin-tuc" class="desktop-cat-link inline-block font-medium text-amber-300">TIN TỨC</a></li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- =========================================================
       DRAWER DANH MỤC TRÊN ĐIỆN THOẠI
       ========================================================= -->
  <div id="mobileDrawerOverlay" onclick="toggleMobileDrawer(false)" class="fixed inset-0 bg-black/50 z-50 hidden transition-opacity"></div>
  <aside id="mobileDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[82vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-xl">
    <div class="bg-brand text-white p-3.5 flex items-center justify-between">
      <span class="font-bold text-xs uppercase tracking-wider"><i class="fa-solid fa-list-ul mr-1.5"></i>Danh Mục Sản Phẩm</span>
      <button onclick="toggleMobileDrawer(false)" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center text-white">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
    <div class="flex-1 overflow-y-auto divide-y divide-gray-100 text-xs font-semibold text-gray-700">
      <a href="#cat-bep-doi" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Bếp Điện Đôi</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-bep-don" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Bếp Điện Đơn</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-hut-mui" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Máy Hút Mùi</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-loc-nuoc" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Máy Lọc Nước</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-bo-noi" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Bộ Nồi Cao Cấp</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-loc-khi" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Máy Lọc Không Khí</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-sua-hat" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Máy Làm Sữa Hạt</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-noi-chien" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Nồi Chiên Không Dầu</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-rua-bat" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Máy Rửa Bát</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-hut-am" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Máy Hút Ẩm</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#cat-may-giat" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-gray-50"><span>Máy Giặt</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a>
      <a href="#form-bao-gia" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 text-brand font-bold"><span>Yêu Cầu Báo Giá</span><i class="fa-solid fa-file-signature text-brand"></i></a>
      <a href="#lien-he-map" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 text-brand-accent font-bold"><span>Bản Đồ & Liên Hệ</span><i class="fa-solid fa-location-dot"></i></a>
    </div>
    <div class="p-3 bg-gray-50 border-t text-xs text-gray-600">
      <div class="font-bold text-brand">CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186</div>
      <div class="mt-1">Hotline: <strong class="text-brand-accent">0366.479.999</strong></div>
    </div>
  </aside>

  <!-- =========================================================
       2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       (Banner Điện thoại thiết kế riêng khác với Máy tính, chữ nhỏ gọn nằm trọn bên trong, không tràn viền)
       ========================================================= -->
  <section class="py-3">
    <div class="container-1500">
      <div class="relative rounded-lg overflow-hidden shadow-sm bg-brand-dark">

        <!-- ================= BANNER DÀNH RIÊNG CHO MÁY TÍNH (Desktop >= 768px) ================= -->
        <div class="hidden md:block relative w-full h-[340px] lg:h-[380px]">
          
          <!-- Slide 1 Desktop -->
          <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-100 flex items-center bg-gradient-to-r from-[#062c4f] via-[#0a4275] to-[#125a9c]">
            <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-16 gap-6">
              <div class="col-span-7 text-white space-y-3 pr-4">
                <div class="inline-block bg-brand-accent text-white text-xs font-bold px-3 py-1 rounded uppercase tracking-wider">
                  CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186
                </div>
                <h1 class="text-xl lg:text-3xl font-extrabold leading-snug text-white">
                  BẾP TỪ ĐÔI & THIẾT BỊ NHÀ BẾP THÔNG MINH NHẬP KHẨU CHÍNH HÃNG
                </h1>
                <p class="text-xs lg:text-sm text-blue-100 leading-relaxed max-w-xl">
                  Mặt kính Schott Ceran vát cạnh sang trọng, công nghệ Inverter tiết kiệm điện năng, bảo hành điện tử chính hãng toàn quốc. Giao lắp tận nơi tại Đà Nẵng.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-4 text-xs font-semibold text-amber-300">
                  <span><i class="fa-solid fa-Location-dot mr-1"></i>155/61 Trần Đình Nam, P. An Khê, TP. Đà Nẵng</span>
                  <span><i class="fa-solid fa-phone-volume mr-1"></i>Hotline: 0366.479.999</span>
                </div>
              </div>
              <div class="col-span-5 flex items-center justify-center">
                <div class="bg-white/10 backdrop-blur-sm p-3 rounded-xl border border-white/20 w-full max-w-[360px] h-[250px] flex items-center justify-center overflow-hidden">
                  <img src="https://drive.google.com/thumbnail?id=1R22fBiJwZJL7e20SWajbnMUVTexH0bo9&sz=w800"
                       onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R22fBiJwZJL7e20SWajbnMUVTexH0bo9=w800';"
                       alt="Bếp điện từ đôi cao cấp" class="max-h-full max-w-full object-contain rounded-lg">
                </div>
              </div>
            </div>
          </div>

          <!-- Slide 2 Desktop (Kích thước bằng đúng Slide 1) -->
          <div class="banner-slide-desktop absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none flex items-center bg-gradient-to-r from-[#083358] via-[#0d4a80] to-[#163a5f]">
            <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-16 gap-6">
              <div class="col-span-7 text-white space-y-3 pr-4">
                <div class="inline-block bg-amber-500 text-gray-900 text-xs font-bold px-3 py-1 rounded uppercase tracking-wider">
                  GIẢI PHÁP ĐỒNG BỘ CHO CĂN BẾP HIỆN ĐẠI - DIENMAY186.COM
                </div>
                <h2 class="text-xl lg:text-3xl font-extrabold leading-snug text-white">
                  MÁY HÚT MÙI - MÁY LỌC NƯỚC ION KIỀM - MÁY RỬA BÁT CAO CẤP
                </h2>
                <p class="text-xs lg:text-sm text-blue-100 leading-relaxed max-w-xl">
                  Phân phối sỉ & lẻ thiết bị nhà bếp, bộ nồi inox cao cấp, máy lọc không khí, máy hút ẩm chính hãng với chiết khấu ưu đãi lên đến 35%.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-4 text-xs font-semibold text-amber-300">
                  <span><i class="fa-solid fa-globe mr-1"></i>Website: dienmay186.com</span>
                  <span><i class="fa-solid fa-headset mr-1"></i>Tư vấn 24/7: 0366.479.999</span>
                </div>
              </div>
              <div class="col-span-5 flex items-center justify-center">
                <div class="bg-white/10 backdrop-blur-sm p-3 rounded-xl border border-white/20 w-full max-w-[360px] h-[250px] flex items-center justify-center overflow-hidden">
                  <img src="https://drive.google.com/thumbnail?id=17OMbRD9y4rq9S8_jtC-yW_b6qFOqdOqF&sz=w800"
                       onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17OMbRD9y4rq9S8_jtC-yW_b6qFOqdOqF=w800';"
                       alt="Máy hút mùi và máy lọc nước" class="max-h-full max-w-full object-contain rounded-lg">
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- ================= BANNER THIẾT KẾ MỚI RIÊNG CHO ĐIỆN THOẠI (Mobile < 768px) ================= -->
        <!-- Chữ chỉnh nhỏ gọn nằm hết bên trong ảnh banner, khoảng cách lề an toàn không tràn viền -->
        <div class="block md:hidden relative w-full h-[205px]">
          
          <!-- Slide 1 Mobile -->
          <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-100 bg-gradient-to-br from-[#062c4f] via-[#0a4275] to-[#125a9c] px-4 py-3.5 flex items-center">
            <div class="w-full grid grid-cols-12 items-center gap-2.5">
              <div class="col-span-7 text-white space-y-1.5">
                <span class="inline-block bg-brand-accent text-white text-[10px] font-bold px-2 py-0.5 rounded">
                  ĐIỆN MÁY - BẾP 186
                </span>
                <h2 class="text-[13px] font-extrabold leading-snug text-white">
                  BẾP TỪ ĐÔI & THIẾT BỊ BẾP THÔNG MINH CHÍNH HÃNG
                </h2>
                <p class="text-[10.5px] text-blue-100 leading-tight">
                  155/61 Trần Đình Nam, P. An Khê, Đà Nẵng
                </p>
                <div class="text-[11px] font-bold text-amber-300">
                  Hotline: 0366.479.999
                </div>
              </div>
              <div class="col-span-5 flex justify-center">
                <div class="bg-white/10 p-1.5 rounded-lg border border-white/20 w-full h-[135px] flex items-center justify-center overflow-hidden">
                  <img src="https://drive.google.com/thumbnail?id=1R22fBiJwZJL7e20SWajbnMUVTexH0bo9&sz=w600"
                       onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R22fBiJwZJL7e20SWajbnMUVTexH0bo9=w600';"
                       alt="Bếp từ đôi chính hãng" class="max-h-full max-w-full object-contain rounded">
                </div>
              </div>
            </div>
          </div>

          <!-- Slide 2 Mobile (Kích thước bằng đúng Slide 1 Mobile) -->
          <div class="banner-slide-mobile absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none bg-gradient-to-br from-[#083358] via-[#0d4a80] to-[#163a5f] px-4 py-3.5 flex items-center">
            <div class="w-full grid grid-cols-12 items-center gap-2.5">
              <div class="col-span-7 text-white space-y-1.5">
                <span class="inline-block bg-amber-400 text-gray-900 text-[10px] font-bold px-2 py-0.5 rounded">
                  DIENMAY186.COM
                </span>
                <h2 class="text-[13px] font-extrabold leading-snug text-white">
                  MÁY HÚT MÙI - MÁY LỌC NƯỚC - MÁY RỬA BÁT
                </h2>
                <p class="text-[10.5px] text-blue-100 leading-tight">
                  Ưu đãi giảm giá đến 35% - Bảo hành toàn quốc
                </p>
                <div class="text-[11px] font-bold text-amber-300">
                  SĐT/Zalo: 0366.479.999
                </div>
              </div>
              <div class="col-span-5 flex justify-center">
                <div class="bg-white/10 p-1.5 rounded-lg border border-white/20 w-full h-[135px] flex items-center justify-center overflow-hidden">
                  <img src="https://drive.google.com/thumbnail?id=17OMbRD9y4rq9S8_jtC-yW_b6qFOqdOqF&sz=w600"
                       onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17OMbRD9y4rq9S8_jtC-yW_b6qFOqdOqF=w600';"
                       alt="Máy hút mùi chính hãng" class="max-h-full max-w-full object-contain rounded">
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng Slide (2 chấm tròn) -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button onclick="setBannerSlide(0)" id="bannerDot0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
          <button onclick="setBannerSlide(1)" id="bannerDot1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =========================================================
       DANH MỤC SẢN PHẨM TRANG CHỦ (Thiết kế đẹp trên máy tính & điện thoại, chữ nhỏ gọn, không tràn viền)
       ========================================================= -->
  <section id="san-pham-chinh" class="py-3">
    <div class="container-1500">
      <div class="bg-white rounded-lg p-3 sm:p-4 shadow-sm border border-gray-200">
        <div class="flex items-center justify-between mb-3 pb-2 border-b border-gray-100">
          <h2 class="text-xs sm:text-sm font-extrabold text-brand uppercase tracking-wide">
            <i class="fa-solid fa-layer-group mr-1.5 text-brand-accent"></i>Danh Mục Sản Phẩm
          </h2>
          <button onclick="selectCategory('all')" class="text-xs font-semibold text-brand hover:text-brand-accent">
            Xem tất cả <i class="fa-solid fa-angle-right ml-0.5"></i>
          </button>
        </div>

        <!-- Grid Danh mục chữ nhỏ gọn, viết liền không vỡ dòng -->
        <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 lg:grid-cols-11 gap-2">
          <button onclick="selectCategory('BẾP ĐIỆN ĐÔI')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-fire-burner text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Bếp Điện Đôi</span>
          </button>

          <button onclick="selectCategory('BẾP ĐIỆN ĐƠN')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-bullseye text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Bếp Điện Đơn</span>
          </button>

          <button onclick="selectCategory('MÁY HÚT MÙI')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-fan text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Máy Hút Mùi</span>
          </button>

          <button onclick="selectCategory('MÁY LỌC NƯỚC')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-droplet text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Máy Lọc Nước</span>
          </button>

          <button onclick="selectCategory('BỘ NỒI CAO CẤP')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-kitchen-set text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Bộ Nồi Cao Cấp</span>
          </button>

          <button onclick="selectCategory('MÁY LỌC KHÔNG KHÍ')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-wind text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Lọc Không Khí</span>
          </button>

          <button onclick="selectCategory('MÁY LÀM SỮA HẠT')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-blender text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Máy Sữa Hạt</span>
          </button>

          <button onclick="selectCategory('NỒI CHIÊN KHÔNG DẦU')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-temperature-high text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Nồi Chiên</span>
          </button>

          <button onclick="selectCategory('MÁY RỬA BÁT')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-soap text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Máy Rửa Bát</span>
          </button>

          <button onclick="selectCategory('MÁY HÚT ẨM')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-water text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Máy Hút Ẩm</span>
          </button>

          <button onclick="selectCategory('MÁY GIẶT')" class="cat-pill group flex flex-col items-center justify-center p-2 rounded-md border border-gray-200 hover:border-brand hover:bg-blue-50/50 transition text-center">
            <div class="w-8 h-8 rounded-full bg-blue-50 text-brand flex items-center justify-center mb-1.5 group-hover:bg-brand group-hover:text-white transition">
              <i class="fa-solid fa-shirt text-xs"></i>
            </div>
            <span class="text-[11px] font-semibold text-gray-800 whitespace-nowrap">Máy Giặt</span>
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================
       KHU VỰC HIỂN THỊ KẾT QUẢ LỌC NHANH (Khi người dùng bấm tìm kiếm / lọc)
       ========================================================= -->
  <section id="filterResultSection" class="py-2 hidden">
    <div class="container-1500">
      <div class="bg-white rounded-lg p-3 sm:p-4 shadow-sm border border-brand">
        <div class="flex items-center justify-between mb-3">
          <h3 id="filterResultTitle" class="text-sm font-bold text-brand uppercase">Kết quả lọc sản phẩm</h3>
          <button onclick="selectCategory('all')" class="text-xs font-semibold text-brand-accent hover:underline">
            <i class="fa-solid fa-rotate-left mr-1"></i>Hiển thị lại tất cả danh mục
          </button>
        </div>
        <div id="filterResultGrid" class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
      </div>
    </div>
  </section>

  <!-- =========================================================
       CÁC SECTION SẢN PHẨM TRANG CHỦ CHUẨN FLATSOME (2 cột trên điện thoại, 5 cột trên máy tính)
       Sử dụng toàn bộ ảnh thực tế từ Google Drive khách cung cấp
       Chỉ có % giảm giá góc trên bên trái chuẩn Flatsome, không gắn nhãn dán phụ
       ========================================================= -->
  <main id="allCategoriesContainer" class="space-y-6 py-2">
    <!-- Được render tự động bằng JavaScript từ dữ liệu thực tế để cấu trúc đồng nhất cho UX Builder -->
  </main>

  <!-- =========================================================
       FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ
       ========================================================= -->
  <section id="form-bao-gia" class="py-6">
    <div class="container-1500">
      <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
        <div class="grid grid-cols-1 lg:grid-cols-12">
          
          <!-- Cột thông tin hỗ trợ báo giá -->
          <div class="lg:col-span-5 bg-brand text-white p-5 sm:p-7 flex flex-col justify-between">
            <div>
              <h2 class="text-lg sm:text-xl font-extrabold uppercase tracking-tight">
                ĐĂNG KÝ NHẬN BÁO GIÁ & TƯ VẤN KỸ THUẬT
              </h2>
              <p class="text-xs sm:text-sm text-blue-100 mt-2 leading-relaxed">
                Quý khách hàng, đại lý hoặc công trình cần báo giá sỉ & lẻ thiết bị bếp từ, máy hút mùi, máy lọc nước, máy rửa bát vui lòng để lại thông tin. Bộ phận kinh doanh của <strong>ĐIỆN MÁY - THIẾT BỊ BẾP 186</strong> sẽ liên hệ ngay.
              </p>
              <div class="mt-5 space-y-3 text-xs sm:text-sm">
                <div class="flex items-start gap-2.5">
                  <i class="fa-solid fa-building mt-1 text-amber-400"></i>
                  <span><strong>Đơn vị:</strong> CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186</span>
                </div>
                <div class="flex items-start gap-2.5">
                  <i class="fa-solid fa-location-dot mt-1 text-amber-400"></i>
                  <span><strong>Địa chỉ:</strong> 155/61 Trần Đình Nam, Phường An Khê, Thành phố Đà Nẵng</span>
                </div>
                <div class="flex items-start gap-2.5">
                  <i class="fa-solid fa-phone-volume mt-1 text-amber-400"></i>
                  <span><strong>Hotline / Zalo:</strong> <a href="tel:0366479999" class="text-amber-300 font-bold">0366.479.999</a></span>
                </div>
                <div class="flex items-start gap-2.5">
                  <i class="fa-solid fa-globe mt-1 text-amber-400"></i>
                  <span><strong>Website:</strong> dienmay186.com</span>
                </div>
              </div>
            </div>
            <div class="mt-6 pt-4 border-t border-white/15 text-xs text-blue-200">
              Cam kết sản phẩm chính hãng - Bảo hành điện tử toàn quốc - Lắp đặt tận nơi.
            </div>
          </div>

          <!-- Cột Form nhập thông tin -->
          <div class="lg:col-span-7 p-5 sm:p-7">
            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-4">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Họ và tên quý khách *</label>
                  <input type="text" id="quoteName" required placeholder="Nhập họ và tên..."
                    class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded focus:outline-none focus:border-brand">
                </div>
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Số điện thoại liên hệ *</label>
                  <input type="tel" id="quotePhone" required placeholder="Ví dụ: 0366479999"
                    class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded focus:outline-none focus:border-brand">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Danh mục sản phẩm quan tâm</label>
                  <select id="quoteCategory" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded focus:outline-none focus:border-brand bg-white">
                    <option value="Bếp Điện Đôi / Bếp Từ">Bếp Điện Đôi / Bếp Từ</option>
                    <option value="Bếp Điện Đơn / Hồng Ngoại">Bếp Điện Đơn / Hồng Ngoại</option>
                    <option value="Máy Hút Mùi Nhà Bếp">Máy Hút Mùi Nhà Bếp</option>
                    <option value="Máy Lọc Nước RO / Ion Kiềm">Máy Lọc Nước RO / Ion Kiềm</option>
                    <option value="Bộ Nồi Inox Cao Cấp">Bộ Nồi Inox Cao Cấp</option>
                    <option value="Máy Rửa Bát / Máy Sữa Hạt / Nồi Chiên">Máy Rửa Bát / Máy Sữa Hạt / Nồi Chiên</option>
                    <option value="Máy Lọc Không Khí / Máy Hút Ẩm / Máy Giặt">Máy Lọc Không Khí / Máy Hút Ẩm / Máy Giặt</option>
                    <option value="Đăng ký làm Đại lý / Báo giá sỉ">Đăng ký làm Đại lý / Báo giá sỉ</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Địa chỉ nhận hàng / Lắp đặt</label>
                  <input type="text" id="quoteAddress" placeholder="Quận/Huyện, Tỉnh/Thành phố..."
                    class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded focus:outline-none focus:border-brand">
                </div>
              </div>

              <div>
                <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Nội dung yêu cầu chi tiết</label>
                <textarea id="quoteNote" rows="3" placeholder="Nhập mã sản phẩm cần báo giá hoặc yêu cầu tư vấn lắp đặt..."
                  class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded focus:outline-none focus:border-brand"></textarea>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                <button type="submit" class="bg-brand-accent hover:bg-red-700 text-white font-bold text-sm px-6 py-3 rounded transition shadow-sm">
                  <i class="fa-solid fa-paper-plane mr-2"></i>GỬI YÊU CẦU BÁO GIÁ NGAY
                </button>
                <span class="text-xs text-gray-500">Hoặc gọi trực tiếp: <strong class="text-brand">0366.479.999</strong></span>
              </div>

              <div id="quoteSuccessBox" class="hidden p-3.5 rounded bg-green-50 border border-green-300 text-green-800 text-xs sm:text-sm font-medium"></div>
            </form>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================
       DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG NHÀ BẾP)
       ========================================================= -->
  <section id="tin-tuc" class="py-4">
    <div class="container-1500">
      <div class="flatsome-section-title">
        <h2><i class="fa-solid fa-newspaper mr-2"></i>TIN TỨC & CẨM NANG MUA SẮM</h2>
        <span class="text-xs font-semibold text-brand pr-4 hidden sm:inline">Kinh nghiệm sử dụng thiết bị bếp bền đẹp</span>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <!-- Bài viết 1 -->
        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 bg-gray-100 overflow-hidden flex items-center justify-center p-2">
            <img src="https://drive.google.com/thumbnail?id=1R22fBiJwZJL7e20SWajbnMUVTexH0bo9&sz=w600"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R22fBiJwZJL7e20SWajbnMUVTexH0bo9=w600';"
                 alt="Hướng dẫn vệ sinh bếp điện từ đôi" class="w-full h-full object-contain">
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-gray-400 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Cẩm nang nhà bếp</div>
              <h3 class="text-sm font-bold text-gray-800 hover:text-brand leading-snug">
                Cách vệ sinh bếp điện từ đôi FC-T68 & F99 Plus giúp mặt kính Schott Ceran luôn sáng bóng
              </h3>
              <p class="text-xs text-gray-600 mt-2 leading-relaxed">
                Hướng dẫn chi tiết mẹo làm sạch mặt kính bếp từ sau khi nấu ăn nhanh chóng, bảo vệ linh kiện và nâng cao tuổi thọ bếp.
              </p>
            </div>
            <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand hover:text-brand-accent">Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 bg-gray-100 overflow-hidden flex items-center justify-center p-2">
            <img src="https://drive.google.com/thumbnail?id=19LfSwIxF5oRnjX_Xcmq-_02cWUc9deWw&sz=w600"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19LfSwIxF5oRnjX_Xcmq-_02cWUc9deWw=w600';"
                 alt="Mẹo chọn máy lọc nước" class="w-full h-full object-contain">
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-gray-400 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Tư vấn mua sắm</div>
              <h3 class="text-sm font-bold text-gray-800 hover:text-brand leading-snug">
                Lợi ích của máy lọc nước Ion Kiềm Hydrogen đối với sức khỏe gia đình Việt
              </h3>
              <p class="text-xs text-gray-600 mt-2 leading-relaxed">
                Tìm hiểu công nghệ lọc RO 9-10 cấp kết hợp lõi tạo nước kiềm Hydrogen giúp trung hòa axit dư thừa và bổ sung khoáng chất.
              </p>
            </div>
            <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand hover:text-brand-accent">Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 bg-gray-100 overflow-hidden flex items-center justify-center p-2">
            <img src="https://drive.google.com/thumbnail?id=17OMbRD9y4rq9S8_jtC-yW_b6qFOqdOqF&sz=w600"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17OMbRD9y4rq9S8_jtC-yW_b6qFOqdOqF=w600';"
                 alt="Kinh nghiệm lắp máy hút mùi" class="w-full h-full object-contain">
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-gray-400 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Kỹ thuật lắp đặt</div>
              <h3 class="text-sm font-bold text-gray-800 hover:text-brand leading-snug">
                Kinh nghiệm chọn máy hút mùi kính cong công suất lớn, êm ái cho không gian bếp kín
              </h3>
              <p class="text-xs text-gray-600 mt-2 leading-relaxed">
                Cách tính khoảng cách lắp đặt máy hút mùi chuẩn kỹ thuật giúp khử sạch 99% mùi thức ăn mà vẫn giữ độ ồn thấp.
              </p>
            </div>
            <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand hover:text-brand-accent">Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 bg-gray-100 overflow-hidden flex items-center justify-center p-2">
            <img src="https://drive.google.com/thumbnail?id=1t-g86Nm1CxFej6904moCd0i2MsFmIWQy&sz=w600"
                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1t-g86Nm1CxFej6904moCd0i2MsFmIWQy=w600';"
                 alt="Hướng dẫn bảo hành điện tử" class="w-full h-full object-contain">
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-gray-400 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Chính sách bảo hành</div>
              <h3 class="text-sm font-bold text-gray-800 hover:text-brand leading-snug">
                Hướng dẫn kích hoạt bảo hành điện tử chính hãng tại Điện Máy - Thiết Bị Bếp 186
              </h3>
              <p class="text-xs text-gray-600 mt-2 leading-relaxed">
                Quy trình kích hoạt và tra cứu bảo hành nhanh chóng qua số điện thoại giúp bảo vệ tối đa quyền lợi của quý khách hàng.
              </p>
            </div>
            <a href="#form-bao-gia" class="mt-3 inline-block text-xs font-bold text-brand hover:text-brand-accent">Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- =========================================================
       DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC
       ========================================================= -->
  <section id="doi-tac" class="py-4">
    <div class="container-1500">
      <div class="bg-white rounded-lg p-4 sm:p-5 border border-gray-200 shadow-sm">
        <div class="flex items-center justify-between mb-4 border-b border-gray-100 pb-2">
          <h2 class="text-xs sm:text-sm font-extrabold text-brand uppercase tracking-wide">
            <i class="fa-solid fa-handshake mr-1.5 text-brand-accent"></i>Đối Tác & Thương Hiệu Đồng Hành
          </h2>
          <span class="text-xs text-gray-500">Hợp tác phân phối chính hãng</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-3">
          <div class="border border-gray-200 rounded-md p-3 flex flex-col items-center justify-center bg-gray-50 hover:border-brand transition">
            <span class="font-black text-base text-brand tracking-wider">FORCI</span>
            <span class="text-[10px] text-gray-500 uppercase">Germany Standard</span>
          </div>
          <div class="border border-gray-200 rounded-md p-3 flex flex-col items-center justify-center bg-gray-50 hover:border-brand transition">
            <span class="font-black text-base text-gray-800 tracking-wider">SCHOTT CERAN</span>
            <span class="text-[10px] text-gray-500 uppercase">Made in Germany</span>
          </div>
          <div class="border border-gray-200 rounded-md p-3 flex flex-col items-center justify-center bg-gray-50 hover:border-brand transition">
            <span class="font-black text-base text-brand-accent tracking-wider">E.G.O</span>
            <span class="text-[10px] text-gray-500 uppercase">Linh kiện nhiệt Đức</span>
          </div>
          <div class="border border-gray-200 rounded-md p-3 flex flex-col items-center justify-center bg-gray-50 hover:border-brand transition">
            <span class="font-black text-base text-blue-800 tracking-wider">EUROKERA</span>
            <span class="text-[10px] text-gray-500 uppercase">K+ France Glass</span>
          </div>
          <div class="border border-gray-200 rounded-md p-3 flex flex-col items-center justify-center bg-gray-50 hover:border-brand transition">
            <span class="font-black text-base text-emerald-700 tracking-wider">PERFECT</span>
            <span class="text-[10px] text-gray-500 uppercase">Gia dụng thông minh</span>
          </div>
          <div class="border border-gray-200 rounded-md p-3 flex flex-col items-center justify-center bg-gray-50 hover:border-brand transition">
            <span class="font-black text-base text-brand tracking-wider">BẾP 186</span>
            <span class="text-[10px] text-gray-500 uppercase">Đà Nẵng - Việt Nam</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================
       GOOGLE MAP & FANPAGE ĐƯA RA NGOÀI TRANG CHỦ
       ========================================================= -->
  <section id="lien-he-map" class="py-4">
    <div class="container-1500">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
        
        <!-- Cột Bản đồ Google Map ngoài trang chủ (7 cột) -->
        <div class="lg:col-span-7 bg-white rounded-lg border border-gray-200 shadow-sm p-4 flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 mb-3 pb-2 border-b border-gray-100">
              <h2 class="text-xs sm:text-sm font-extrabold text-brand uppercase">
                <i class="fa-solid fa-map-location-dot mr-1.5 text-brand-accent"></i>Bản Đồ Đường Đi - Điện Máy & Thiết Bị Bếp 186
              </h2>
              <a href="https://www.google.com/maps/search/?api=1&query=155%2F61+Tr%E1%BA%A7n+%C4%90%C3%ACnh+Nam%2C+Ph%C6%B0%E1%BB%9Dng+An+Kh%C3%AA%2C+%C4%90%C3%A0+N%E1%BA%B5ng" 
                 target="_blank" rel="noopener" class="text-xs font-bold text-white bg-brand px-3 py-1 rounded hover:bg-brand-light">
                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Google Maps lớn
              </a>
            </div>
            <p class="text-xs text-gray-600 mb-3">
              <strong>Địa chỉ:</strong> 155/61 Trần Đình Nam, Phường An Khê, Thành phố Đà Nẵng — <strong>Điện thoại:</strong> <a href="tel:0366479999" class="text-brand-accent font-bold">0366.479.999</a>
            </p>
          </div>

          <div class="w-full h-64 sm:h-72 rounded-md overflow-hidden border border-gray-200 relative bg-gray-100">
            <iframe 
              title="Bản đồ Công Ty TNHH Điện Máy - Thiết Bị Bếp 186 tại 155/61 Trần Đình Nam, Phường An Khê, Đà Nẵng"
              src="https://www.google.com/maps?q=155/61+Tr%E1%BA%A7n+%C4%90%C3%ACnh+Nam,+An+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>

        <!-- Cột Fanpage chính thức đưa ra ngoài trang chủ (5 cột) -->
        <div class="lg:col-span-5 bg-white rounded-lg border border-gray-200 shadow-sm p-4 flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between mb-3 pb-2 border-b border-gray-100">
              <h2 class="text-xs sm:text-sm font-extrabold text-brand uppercase">
                <i class="fa-brands fa-facebook mr-1.5 text-[#1877F2]"></i>Fanpage Kết Nối Trực Tuyến
              </h2>
              <span class="text-[11px] text-green-600 font-semibold"><i class="fa-solid fa-circle text-[8px] mr-1"></i>Đang trực tuyến</span>
            </div>

            <!-- Khung Fanpage trực quan ngoài trang chủ -->
            <div class="border border-gray-200 rounded-lg overflow-hidden bg-gray-50">
              <div class="bg-gradient-to-r from-[#062c4f] via-[#0a4275] to-[#1877F2] p-4 text-white relative">
                <div class="flex items-center gap-3">
                  <div class="w-12 h-12 rounded-lg bg-white p-1 shrink-0 shadow flex items-center justify-center">
                    <span class="font-black text-brand text-sm">186</span>
                  </div>
                  <div class="min-w-0">
                    <h3 class="font-bold text-sm truncate">Công Ty TNHH Điện Máy - Thiết Bị Bếp 186</h3>
                    <p class="text-xs text-blue-100">Thiết bị nhà bếp & Điện máy chính hãng Đà Nẵng</p>
                  </div>
                </div>
                <div class="mt-3 flex flex-wrap gap-2">
                  <a href="https://facebook.com" target="_blank" rel="noopener" class="bg-white text-[#1877F2] text-xs font-bold px-3 py-1.5 rounded shadow-sm hover:bg-blue-50">
                    <i class="fa-brands fa-facebook mr-1"></i>Theo dõi Trang
                  </a>
                  <a href="https://zalo.me/0366479999" target="_blank" rel="noopener" class="bg-[#0068ff] text-white text-xs font-bold px-3 py-1.5 rounded shadow-sm hover:opacity-95">
                    <i class="fa-solid fa-comment-dots mr-1"></i>Nhắn tin tư vấn
                  </a>
                </div>
              </div>

              <div class="p-3.5 space-y-2.5 text-xs text-gray-700 bg-white">
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-circle-check text-[#1877F2]"></i>
                  <span>Cập nhật khuyến mãi bếp từ, máy hút mùi, máy lọc nước mỗi ngày.</span>
                </div>
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-location-dot text-brand-accent"></i>
                  <span>155/61 Trần Đình Nam, Phường An Khê, TP. Đà Nẵng</span>
                </div>
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-phone text-green-600"></i>
                  <span>Hotline hỗ trợ nhanh: <strong>0366.479.999</strong></span>
                </div>
                <div class="grid grid-cols-3 gap-2 pt-2">
                  <img src="https://drive.google.com/thumbnail?id=1R22fBiJwZJL7e20SWajbnMUVTexH0bo9&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R22fBiJwZJL7e20SWajbnMUVTexH0bo9=w300';" alt="Sản phẩm 1" class="h-16 w-full object-contain bg-gray-50 rounded border p-1">
                  <img src="https://drive.google.com/thumbnail?id=17U5CtmRr5DadlZAhbexq6KhEPZQZUNr-&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/17U5CtmRr5DadlZAhbexq6KhEPZQZUNr-=w300';" alt="Sản phẩm 2" class="h-16 w-full object-contain bg-gray-50 rounded border p-1">
                  <img src="https://drive.google.com/thumbnail?id=1nKZeC4zjmc3f2xz9uzpL-1s6SiWWOw10&sz=w300" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1nKZeC4zjmc3f2xz9uzpL-1s6SiWWOw10=w300';" alt="Sản phẩm 3" class="h-16 w-full object-contain bg-gray-50 rounded border p-1">
                </div>
              </div>
            </div>
          </div>

          <div class="mt-3 pt-2 border-t border-gray-100 flex items-center justify-between text-xs text-gray-500">
            <span>Website: <strong>dienmay186.com</strong></span>
            <span>Tư vấn 24/7</span>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =========================================================
       FOOTER CHUẨN MẪU FORCI.VN & FLATSOME
       ========================================================= -->
  <footer class="bg-brand-dark text-white mt-6 pt-8 pb-20 md:pb-8 border-t-4 border-brand-accent">
    <div class="container-1500">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-8 border-b border-white/10">
        
        <!-- Thông tin công ty (5 cột) -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded bg-brand-accent flex items-center justify-center font-black text-white text-sm">186</div>
            <div>
              <h3 class="font-extrabold text-sm sm:text-base uppercase text-white">CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186</h3>
              <p class="text-xs text-amber-300">Website: www.dienmay186.com</p>
            </div>
          </div>
          <p class="text-xs text-blue-100 leading-relaxed pt-1">
            Chuyên nhập khẩu và phân phối bếp từ đôi, bếp điện hồng ngoại, máy hút mùi, máy lọc nước RO - Ion kiềm, bộ nồi inox cao cấp, máy rửa bát và thiết bị gia dụng thông minh.
          </p>
          <ul class="text-xs space-y-1.5 text-blue-100 pt-1">
            <li><i class="fa-solid fa-id-card mr-2 text-amber-400"></i><strong>Mã số thuế:</strong> 0402347202</li>
            <li><i class="fa-solid fa-location-dot mr-2 text-amber-400"></i><strong>Địa chỉ:</strong> 155/61 Trần Đình Nam, Phường An Khê, Thành phố Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume mr-2 text-amber-400"></i><strong>Hotline:</strong> <a href="tel:0366479999" class="text-amber-300 font-bold">0366.479.999</a></li>
            <li><i class="fa-solid fa-globe mr-2 text-amber-400"></i><strong>Website:</strong> dienmay186.com</li>
          </ul>
        </div>

        <!-- Chính sách khách hàng (3 cột) -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">Chính Sách & Quy Định</h4>
          <ul class="text-xs space-y-2 text-blue-100">
            <li><a href="#form-bao-gia" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5"></i>Quy định kích hoạt bảo hành điện tử</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5"></i>Chính sách bảo hành chính hãng</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5"></i>Chính sách vận chuyển & lắp đặt</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5"></i>Phương thức thanh toán linh hoạt</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1.5"></i>Chính sách đại lý & chiết khấu</a></li>
          </ul>
        </div>

        <!-- Danh mục chủ lực (4 cột) -->
        <div class="lg:col-span-4 space-y-2">
          <h4 class="font-bold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">Danh Mục Sản Phẩm Chính</h4>
          <div class="grid grid-cols-2 gap-2 text-xs text-blue-100">
            <a href="#cat-bep-doi" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Bếp Điện Đôi</a>
            <a href="#cat-bep-don" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Bếp Điện Đơn</a>
            <a href="#cat-hut-mui" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Máy Hút Mùi</a>
            <a href="#cat-loc-nuoc" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Máy Lọc Nước</a>
            <a href="#cat-bo-noi" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Bộ Nồi Cao Cấp</a>
            <a href="#cat-rua-bat" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Máy Rửa Bát</a>
            <a href="#cat-loc-khi" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Máy Lọc Không Khí</a>
            <a href="#cat-hut-am" class="hover:text-white"><i class="fa-solid fa-angle-right mr-1"></i>Máy Hút Ẩm</a>
          </div>
          <div class="pt-3">
            <div class="bg-white/10 rounded p-2.5 text-xs">
              <div>Chăm sóc khách hàng 24/7:</div>
              <a href="tel:0366479999" class="text-base font-extrabold text-amber-300">0366.479.999</a>
            </div>
          </div>
        </div>

      </div>

      <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-xs text-blue-200">
        <div>© 2026 CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186 (dienmay186.com).</div>
        <div>Địa chỉ: 155/61 Trần Đình Nam, Phường An Khê, TP. Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- =========================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       Tương thích cả trên máy tính và điện thoại, không gây tràn viền
       ========================================================= -->
  <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo -->
    <a href="https://zalo.me/0366479999" target="_blank" rel="noopener"
       class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full shadow-lg px-3 py-2 sm:px-3.5 sm:py-2.5 transition transform hover:scale-105">
      <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-black text-xs flex items-center justify-center shrink-0">Z</span>
      <span class="text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a href="https://facebook.com" target="_blank" rel="noopener"
       class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full shadow-lg px-3 py-2 sm:px-3.5 sm:py-2.5 transition transform hover:scale-105">
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] text-xs flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f"></i>
      </span>
      <span class="text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Hotline -->
    <a href="tel:0366479999"
       class="floating-pulse flex items-center gap-2 bg-brand-accent hover:bg-red-700 text-white rounded-full shadow-lg px-3 py-2 sm:px-4 sm:py-2.5 transition">
      <span class="w-6 h-6 rounded-full bg-white text-brand-accent text-xs flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume"></i>
      </span>
      <span class="text-xs font-extrabold pr-1">0366.479.999</span>
    </a>
  </div>

  <!-- =========================================================
       MODAL CHI TIẾT SẢN PHẨM & ĐẶT MUA NHANH (Không dùng alert)
       ========================================================= -->
  <div id="productDetailModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-2xl w-full overflow-hidden shadow-2xl border border-gray-200 max-h-[90vh] flex flex-col">
      <div class="bg-brand text-white px-4 py-3 flex items-center justify-between">
        <h3 id="modalProductCategory" class="text-xs sm:text-sm font-bold uppercase">Chi tiết sản phẩm</h3>
        <button onclick="closeProductModal()" class="w-7 h-7 rounded bg-white/15 flex items-center justify-center text-white hover:bg-white/25">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-6 overflow-y-auto grid grid-cols-1 sm:grid-cols-12 gap-4 items-center">
        <div class="sm:col-span-5 bg-gray-50 border rounded-lg p-3 flex items-center justify-center h-56">
          <img id="modalProductImg" src="" alt="Ảnh sản phẩm" class="max-h-full max-w-full object-contain">
        </div>
        <div class="sm:col-span-7 space-y-2.5">
          <h4 id="modalProductName" class="text-base sm:text-lg font-extrabold text-gray-800 leading-snug"></h4>
          <div class="flex items-baseline gap-2.5">
            <span id="modalProductSalePrice" class="text-lg sm:text-xl font-extrabold text-brand-accent"></span>
            <span id="modalProductOldPrice" class="text-xs sm:text-sm text-gray-400 line-through"></span>
            <span id="modalProductBadge" class="bg-brand-accent text-white text-xs font-bold px-2 py-0.5 rounded"></span>
          </div>
          <p id="modalProductDesc" class="text-xs sm:text-sm text-gray-600 leading-relaxed"></p>
          <div class="bg-blue-50 p-3 rounded text-xs text-gray-700 space-y-1">
            <div><i class="fa-solid fa-check text-green-600 mr-1.5"></i>Phân phối chính hãng bởi <strong>ĐIỆN MÁY - THIẾT BỊ BẾP 186</strong></div>
            <div><i class="fa-solid fa-location-dot text-brand mr-1.5"></i>155/61 Trần Đình Nam, Phường An Khê, TP. Đà Nẵng</div>
            <div><i class="fa-solid fa-phone text-brand-accent mr-1.5"></i>Hotline tư vấn & đặt hàng: <strong>0366.479.999</strong></div>
          </div>
          <div class="pt-2 flex flex-wrap gap-2">
            <a href="tel:0366479999" class="bg-brand-accent text-white text-xs font-bold px-4 py-2.5 rounded hover:bg-red-700">
              <i class="fa-solid fa-phone mr-1.5"></i>Gọi mua: 0366.479.999
            </a>
            <button onclick="prefillQuoteFromModal()" class="bg-brand text-white text-xs font-bold px-4 py-2.5 rounded hover:bg-brand-light">
              <i class="fa-solid fa-file-invoice mr-1.5"></i>Nhận báo giá sỉ/lẻ
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- =========================================================
       JAVASCRIPT: DỮ LIỆU SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE & FORCI.VN
       ========================================================= -->
  <script>
    // Danh sách 10 ID ảnh sản phẩm thực tế từ Google Drive khách hàng cung cấp
    const DRIVE_IDS = [
      '1R22fBiJwZJL7e20SWajbnMUVTexH0bo9', // File 1
      '19LfSwIxF5oRnjX_Xcmq-_02cWUc9deWw', // File 2
      '17OMbRD9y4rq9S8_jtC-yW_b6qFOqdOqF', // File 3
      '17U5CtmRr5DadlZAhbexq6KhEPZQZUNr-', // File 4
      '1nKZeC4zjmc3f2xz9uzpL-1s6SiWWOw10', // File 5
      '1gv38VaymClKljbyBaZ6yYcKur_qE_903', // File 6
      '1bIcoVS0vTMRuenqWgVAuiWa4OXR9tUu0', // File 7
      '1SVfhR9JHPIPh23mPiRu3sw1-nnzIS2Rv', // File 8
      '1t-g86Nm1CxFej6904moCd0i2MsFmIWQy', // File 9
      '1Nf_DjQcnPQ2UAmbg4_aOsC48O46rn91G'  // File 10
    ];

    function getDriveImg(id) {
      return `https://drive.google.com/thumbnail?id=${id}&sz=w800`;
    }
    function getDriveFallback(id) {
      return `https://lh3.googleusercontent.com/d/${id}=w800`;
    }

    // Danh mục và Sản phẩm lấy chuẩn theo web mẫu forci.vn/home kết hợp ảnh thực tế Google Drive
    const CATALOG_SECTIONS = [
      {
        id: 'cat-bep-doi',
        categoryKey: 'BẾP ĐIỆN ĐÔI',
        title: 'BẾP ĐIỆN ĐÔI - BẾP TỪ ĐÔI NHẬP KHẨU',
        products: [
          {
            name: 'BẾP TỪ ĐÔI FORCI FC-F66 NEW',
            salePrice: '16.100.000 ₫',
            oldPrice: '21.500.000 ₫',
            discount: '-25%',
            driveId: DRIVE_IDS[0],
            desc: 'Bếp từ đôi mặt kính Schott Ceran vát cạnh, công nghệ Inverter tiết kiệm điện, tính năng nấu nhanh Booster 3000W.'
          },
          {
            name: 'BẾP ĐIỆN ĐÔI FORCI FC-F99 PLUS',
            salePrice: '20.200.000 ₫',
            oldPrice: '28.890.000 ₫',
            discount: '-30%',
            driveId: DRIVE_IDS[3],
            desc: 'Bếp điện đôi cao cấp linh kiện Đức, bảng điều khiển cảm ứng trượt siêu nhạy, hẹn giờ độc lập 99 phút.'
          },
          {
            name: 'BẾP ĐIỆN ĐÔI FORCI FC-T68',
            salePrice: '11.600.000 ₫',
            oldPrice: '15.500.000 ₫',
            discount: '-25%',
            driveId: DRIVE_IDS[4],
            desc: 'Bếp điện từ đôi sang trọng, tự động nhận diện vùng nấu, khóa an toàn trẻ em và chống tràn thông minh.'
          },
          {
            name: 'BẾP ĐIỆN ĐÔI FORCI FC-T69',
            salePrice: '12.600.000 ₫',
            oldPrice: '16.800.000 ₫',
            discount: '-25%',
            driveId: DRIVE_IDS[5],
            desc: 'Dòng bếp điện đôi bền bỉ, tản nhiệt êm ái, mặt kính chịu lực chịu nhiệt cao cấp.'
          },
          {
            name: 'BẾP ĐIỆN ĐÔI F10S NHẬP KHẨU',
            salePrice: '15.590.000 ₫',
            oldPrice: '19.500.000 ₫',
            discount: '-20%',
            driveId: DRIVE_IDS[6],
            desc: 'Thiết kế bo viền hợp kim sang trọng, công suất mạnh mẽ, bảo hành điện tử chính hãng.'
          },
          {
            name: 'BẾP ĐIỆN TỪ ĐÔI FC-TL268 NEW',
            salePrice: '16.890.000 ₫',
            oldPrice: '22.000.000 ₫',
            discount: '-23%',
            driveId: DRIVE_IDS[7],
            desc: 'Sự kết hợp hoàn hảo giữa vùng nấu từ và hồng ngoại, không kén nồi, tiện lợi cho mọi gia đình.'
          },
          {
            name: 'BẾP TỪ ĐÔI ITALY FC-F866',
            salePrice: '22.590.000 ₫',
            oldPrice: '28.900.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[8],
            desc: 'Bếp từ đôi tiêu chuẩn Châu Âu, kiểm soát nhiệt độ chính xác, tiết kiệm 35% điện năng.'
          },
          {
            name: 'BẾP TỪ ĐÔI FORCI F86KR',
            salePrice: '20.500.000 ₫',
            oldPrice: '25.600.000 ₫',
            discount: '-20%',
            driveId: DRIVE_IDS[9],
            desc: 'Kiểu dáng hiện đại, tích hợp chế độ hâm nóng, rã đông và chiên xào chuẩn nhiệt.'
          },
          {
            name: 'BẾP ĐIỆN MỘT TỪ MỘT HỒNG NGOẠI FC-TL1126',
            salePrice: '17.890.000 ₫',
            oldPrice: '22.900.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[1],
            desc: 'Bếp điện từ kết hợp hồng ngoại nhập khẩu Thái Lan, mặt kính chống trầy xước vượt trội.'
          },
          {
            name: 'BẾP TỪ BA FORCI F99 PLUS',
            salePrice: '25.590.000 ₫',
            oldPrice: '32.890.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[2],
            desc: 'Bếp từ 3 vùng nấu tổng công suất 6800W, đáp ứng nhu cầu nấu nướng nhanh cho gia đình đông người.'
          }
        ]
      },
      {
        id: 'cat-bep-don',
        categoryKey: 'BẾP ĐIỆN ĐƠN',
        title: 'BẾP ĐIỆN ĐƠN - BẾP TỪ & HỒNG NGOẠI ĐƠN',
        products: [
          {
            name: 'BẾP TỪ ĐƠN FORCI FC-M8',
            salePrice: '2.290.000 ₫',
            oldPrice: '2.990.000 ₫',
            discount: '-23%',
            driveId: DRIVE_IDS[3],
            desc: 'Bếp từ đơn nhỏ gọn, mặt kính cường lực siêu bền, kèm nồi lẩu tiện dụng cho gia đình.'
          },
          {
            name: 'BẾP HỒNG NGOẠI ĐƠN FORCI FC-M5',
            salePrice: '2.290.000 ₫',
            oldPrice: '2.890.000 ₫',
            discount: '-21%',
            driveId: DRIVE_IDS[4],
            desc: 'Bếp hồng ngoại đơn sử dụng được mọi loại nồi, nướng trực tiếp trên mặt bếp tiện lợi.'
          }
        ]
      },
      {
        id: 'cat-hut-mui',
        categoryKey: 'MÁY HÚT MÙI',
        title: 'MÁY HÚT MÙI NHÀ BẾP CHÍNH HÃNG',
        products: [
          {
            name: 'MÁY HÚT MÙI FORCI HM-1068',
            salePrice: '11.900.000 ₫',
            oldPrice: '15.200.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[2],
            desc: 'Máy hút mùi cảm ứng vẫy tay thông minh, lưới lọc Inox Baffle dễ vệ sinh, lực hút mạnh mẽ.'
          },
          {
            name: 'MÁY HÚT MÙI FORCI HM-1088A',
            salePrice: '15.190.000 ₫',
            oldPrice: '19.500.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[5],
            desc: 'Thiết kế chữ T sang trọng, động cơ Tuabin đôi siêu êm, khử mùi bằng than hoạt tính thế hệ mới.'
          },
          {
            name: 'MÁY HÚT MÙI KÍNH CONG FORCI HM08',
            salePrice: '8.900.000 ₫',
            oldPrice: '11.500.000 ₫',
            discount: '-23%',
            driveId: DRIVE_IDS[6],
            desc: 'Máy hút mùi kính cong cường lực, đèn LED chiếu sáng vùng nấu tiết kiệm điện.'
          },
          {
            name: 'MÁY HÚT MÙI FORCI HM-2616',
            salePrice: '7.890.000 ₫',
            oldPrice: '9.900.000 ₫',
            discount: '-20%',
            driveId: DRIVE_IDS[7],
            desc: 'Kiểu dáng gọn đẹp phù hợp mọi tủ bếp, 3 tốc độ hút linh hoạt, độ ồn thấp.'
          },
          {
            name: 'MÁY HÚT MÙI HM-CD86',
            salePrice: '7.200.000 ₫',
            oldPrice: '9.200.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[8],
            desc: 'Vỏ sơn tĩnh điện cao cấp chống bám vân tay, dễ dàng lau chùi dầu mỡ.'
          }
        ]
      },
      {
        id: 'cat-loc-nuoc',
        categoryKey: 'MÁY LỌC NƯỚC',
        title: 'MÁY LỌC NƯỚC RO & ION KIỀM HYDROGEN',
        products: [
          {
            name: 'MÁY LỌC NƯỚC FORCI FC109 NÓNG - LẠNH - KIỀM',
            salePrice: '13.600.000 ₫',
            oldPrice: '17.500.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[1],
            desc: 'Tích hợp 3 chế độ Nước Nóng - Lạnh - Kiềm tiện lợi, hệ thống 10 cấp lọc chuẩn tinh khiết.'
          },
          {
            name: 'MÁY LỌC NƯỚC FORCI FC110 NÓNG - LẠNH - NGUỘI - KIỀM',
            salePrice: '16.000.000 ₫',
            oldPrice: '20.500.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[9],
            desc: 'Máy lọc nước đa năng thế hệ mới, bổ sung khoáng chất và Hydrogen có lợi cho cơ thể.'
          },
          {
            name: 'MÁY LỌC NƯỚC 3 CHỨC NĂNG FC-T09 HYDROGEN',
            salePrice: '18.000.000 ₫',
            oldPrice: '23.000.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[0],
            desc: 'Thiết kế tủ kính tràn viền sang trọng, tạo nước Hydrogen giàu kiềm tốt cho sức khỏe.'
          },
          {
            name: 'MÁY LỌC NƯỚC NÓNG KIỀM FORCI FC-108',
            salePrice: '8.880.000 ₫',
            oldPrice: '11.500.000 ₫',
            discount: '-23%',
            driveId: DRIVE_IDS[2],
            desc: 'Màng lọc RO nhập khẩu, công suất lọc 15-20 lít/giờ đáp ứng nhu cầu cả gia đình.'
          },
          {
            name: 'LÕI TẠO NƯỚC ION KIỀM - HYDROGEN NHẬP KHẨU',
            salePrice: '580.000 ₫',
            oldPrice: '1.060.000 ₫',
            discount: '-45%',
            driveId: DRIVE_IDS[4],
            desc: 'Lõi lọc nâng cấp tạo nước Ion kiềm giàu Hydrogen chống oxy hóa hiệu quả.'
          }
        ]
      },
      {
        id: 'cat-bo-noi',
        categoryKey: 'BỘ NỒI CAO CẤP',
        title: 'BỘ NỒI INOX CAO CẤP DÙNG CHO BẾP TỪ',
        products: [
          {
            name: 'BỘ NỒI FORCI CAO CẤP 3 MÓN INOX 304',
            salePrice: '2.250.000 ₫',
            oldPrice: '3.100.000 ₫',
            discount: '-27%',
            driveId: DRIVE_IDS[5],
            desc: 'Bộ nồi Inox 304 đáy 5 lớp truyền nhiệt đều, vung kính cường lực chịu nhiệt, dùng tốt trên mọi bếp từ.'
          },
          {
            name: 'BỘ NỒI CAO CẤP FORCI 4 MÓN ĐÁY TỪ',
            salePrice: '2.850.000 ₫',
            oldPrice: '3.900.000 ₫',
            discount: '-27%',
            driveId: DRIVE_IDS[6],
            desc: 'Bộ 4 nồi inox cao cấp sáng bóng, an toàn sức khỏe, giữ nhiệt lâu và tiết kiệm điện năng.'
          }
        ]
      },
      {
        id: 'cat-rua-bat',
        categoryKey: 'MÁY RỬA BÁT',
        title: 'MÁY RỬA BÁT - MÁY SỮA HẠT - NỒI CHIÊN KHÔNG DẦU',
        products: [
          {
            name: 'MÁY RỬA BÁT FORCI RB-183 THÔNG MINH',
            salePrice: '29.800.000 ₫',
            oldPrice: '36.500.000 ₫',
            discount: '-18%',
            driveId: DRIVE_IDS[7],
            desc: 'Máy rửa bát dung tích lớn 14 bộ bát đĩa Châu Âu, sấy khô khí nóng và khử khuẩn tia UV.'
          },
          {
            name: 'MÁY RỬA BÁT CAO CẤP RB-2388',
            salePrice: '32.900.000 ₫',
            oldPrice: '39.900.000 ₫',
            discount: '-18%',
            driveId: DRIVE_IDS[8],
            desc: 'Vận hành êm ái, tiết kiệm nước với 8 chương trình rửa chuyên sâu cho gia đình Việt.'
          },
          {
            name: 'MÁY LÀM SỮA HẠT ĐA NĂNG FORCI FCB-A68',
            salePrice: '5.500.000 ₫',
            oldPrice: '7.200.000 ₫',
            discount: '-24%',
            driveId: DRIVE_IDS[9],
            desc: 'Xay nấu sữa hạt siêu mịn không cần lọc, cối thủy tinh Borosilicate dày 5 lớp chịu nhiệt.'
          },
          {
            name: 'NỒI CHIÊN KHÔNG DẦU FORCI DUNG TÍCH LỚN',
            salePrice: '4.500.000 ₫',
            oldPrice: '5.900.000 ₫',
            discount: '-24%',
            driveId: DRIVE_IDS[0],
            desc: 'Công nghệ Rapid Air giảm 85% lượng mỡ thừa, mặt kính quan sát thực phẩm tiện lợi.'
          }
        ]
      },
      {
        id: 'cat-hut-am',
        categoryKey: 'MÁY HÚT ẨM',
        title: 'MÁY LỌC KHÔNG KHÍ - MÁY HÚT ẨM - MÁY GIẶT',
        products: [
          {
            name: 'MÁY LỌC KHÔNG KHÍ FORCI FC-K06',
            salePrice: '12.890.000 ₫',
            oldPrice: '16.500.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[1],
            desc: 'Màng lọc HEPA H13 lọc sạch bụi mịn PM2.5, khử mùi và tạo Ion âm làm sạch không khí.'
          },
          {
            name: 'MÁY HÚT ẨM DÂN DỤNG FORCI FC-HA22',
            salePrice: '7.200.000 ₫',
            oldPrice: '9.200.000 ₫',
            discount: '-22%',
            driveId: DRIVE_IDS[2],
            desc: 'Kiểm soát độ ẩm tự động, sấy khô quần áo nhanh chóng trong mùa mưa nồm ẩm.'
          },
          {
            name: 'MÁY HÚT ẨM CÔNG SUẤT LỚN FC HA-50L',
            salePrice: '9.600.000 ₫',
            oldPrice: '12.500.000 ₫',
            discount: '-23%',
            driveId: DRIVE_IDS[3],
            desc: 'Hút ẩm 50 lít/ngày phù hợp phòng khách rộng, văn phòng và kho bảo quản.'
          },
          {
            name: 'MÁY GIẶT THÔNG MINH FORCI MG-1258',
            salePrice: '7.200.000 ₫',
            oldPrice: '9.100.000 ₫',
            discount: '-21%',
            driveId: DRIVE_IDS[4],
            desc: '10 chương trình giặt thông minh, vắt khô 90%, tiết kiệm điện nước tối ưu.'
          }
        ]
      }
    ];

    // Hàm tạo HTML chuẩn Flatsome cho từng thẻ sản phẩm
    // Chỉ hiển thị % giảm giá ở góc trên bên trái chuẩn Flatsome, không gắn nhãn dán phụ
    // Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ hay tràn ra ngoài
    function createProductCardHTML(product, categoryTitle) {
      const primarySrc = getDriveImg(product.driveId);
      const fallbackSrc = getDriveFallback(product.driveId);
      const safeData = encodeURIComponent(JSON.stringify({ ...product, categoryTitle }));

      return `
        <div class="flatsome-product-box group cursor-pointer" onclick="openProductModal('${safeData}')">
          <!-- Góc trên bên trái: % giảm giá chuẩn Flatsome -->
          <div class="flatsome-Discount-badge">${product.discount}</div>

          <!-- Khung ảnh sản phẩm thực tế -->
          <div class="relative w-full pt-3 px-3 pb-2 bg-white flex items-center justify-center h-40 sm:h-48 overflow-hidden border-b border-gray-100">
            <img src="${primarySrc}"
                 onerror="this.onerror=null;this.src='${fallbackSrc}';"
                 alt="${product.name}"
                 loading="lazy"
                 class="max-h-full max-w-full object-contain group-hover:scale-105 transition-transform duration-300">
          </div>

          <!-- Khung thông tin sản phẩm -->
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between bg-white">
            <div>
              <h3 class="product-title-full text-xs sm:text-[13.5px] font-bold text-gray-800 group-hover:text-brand mb-1.5">
                ${product.name}
              </h3>
            </div>

            <div class="pt-1.5 border-t border-gray-100">
              <!-- Giá gốc gạch ngang và Giá giảm nổi bật -->
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-xs sm:text-sm font-extrabold text-brand-accent">${product.salePrice}</span>
                <span class="text-[11px] text-gray-400 line-through">${product.oldPrice}</span>
              </div>
              <div class="mt-2">
                <span class="block w-full text-center bg-brand group-hover:bg-brand-accent text-white text-[11px] sm:text-xs font-semibold py-1.5 rounded transition">
                  Xem chi tiết
                </span>
              </div>
            </div>
          </div>
        </div>
      `;
    }

    // Render toàn bộ các danh mục sản phẩm ra trang chủ (2 cột trên điện thoại, 5 cột trên máy tính)
    function renderAllCategories() {
      const container = document.getElementById('allCategoriesContainer');
      let html = '';

      // Thêm anchor ẩn cho các danh mục gộp để thanh menu cuộn mượt
      CATALOG_SECTIONS.forEach(sec => {
        let extraAnchors = '';
        if (sec.id === 'cat-rua-bat') {
          extraAnchors = '<span id="cat-sua-hat"></span><span id="cat-noi-chien"></span>';
        }
        if (sec.id === 'cat-hut-am') {
          extraAnchors = '<span id="cat-loc-khi"></span><span id="cat-may-giat"></span>';
        }

        const cardsHTML = sec.products.map(p => createProductCardHTML(p, sec.title)).join('');
        html += `
          <section id="${sec.id}" class="scroll-mt-28">
            ${extraAnchors}
            <div class="container-1500">
              <div class="flatsome-section-title">
                <h2>${sec.title}</h2>
                <a href="#form-bao-gia" class="text-xs font-semibold text-brand hover:text-brand-accent pr-3 whitespace-nowrap">
                  Nhận báo giá <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
              </div>
              <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột tablet, 5 cột máy tính -->
              <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-4">
                ${cardsHTML}
              </div>
            </div>
          </section>
        `;
      });

      container.innerHTML = html;
    }

    // Lọc sản phẩm theo danh mục khi bấm nút Danh mục
    function selectCategory(catName) {
      const filterSection = document.getElementById('filterResultSection');
      const filterGrid = document.getElementById('filterResultGrid');
      const filterTitle = document.getElementById('filterResultTitle');

      if (catName === 'all') {
        filterSection.classList.add('hidden');
        document.getElementById('desktopSearchInput').value = '';
        document.getElementById('mobileSearchInput').value = '';
        return;
      }

      const matchedProducts = [];
      CATALOG_SECTIONS.forEach(sec => {
        sec.products.forEach(p => {
          if (
            sec.categoryKey.includes(catName) ||
            sec.title.includes(catName) ||
            p.name.toUpperCase().includes(catName.toUpperCase())
          ) {
            matchedProducts.push({ product: p, categoryTitle: sec.title });
          }
        });
      });

      filterTitle.textContent = `DANH MỤC: ${catName} (${matchedProducts.length} SẢN PHẨM)`;
      filterGrid.innerHTML = matchedProducts.map(item => createProductCardHTML(item.product, item.categoryTitle)).join('');
      filterSection.classList.remove('hidden');
      filterSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
    }

    // Tìm kiếm sản phẩm theo từ khóa
    function filterProductsBySearch(keyword) {
      const q = (keyword || '').trim().toUpperCase();
      const filterSection = document.getElementById('filterResultSection');
      const filterGrid = document.getElementById('filterResultGrid');
      const filterTitle = document.getElementById('filterResultTitle');

      if (!q) {
        filterSection.classList.add('hidden');
        return;
      }

      const matched = [];
      CATALOG_SECTIONS.forEach(sec => {
        sec.products.forEach(p => {
          if (p.name.toUpperCase().includes(q) || p.desc.toUpperCase().includes(q) || sec.title.toUpperCase().includes(q)) {
            matched.push({ product: p, categoryTitle: sec.title });
          }
        });
      });

      filterTitle.textContent = `KẾT QUẢ TÌM KIẾM "${keyword}" (${matched.length} SẢN PHẨM)`;
      if (matched.length === 0) {
        filterGrid.innerHTML = `<div class="col-span-full py-6 text-center text-xs sm:text-sm text-gray-500">Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng gọi <strong>0366.479.999</strong> để được tư vấn mã sản phẩm tương đương.</div>`;
      } else {
        filterGrid.innerHTML = matched.map(item => createProductCardHTML(item.product, item.categoryTitle)).join('');
      }
      filterSection.classList.remove('hidden');
    }

    // Điều khiển Modal xem chi tiết sản phẩm
    let currentModalProductName = '';
    function openProductModal(encodedProduct) {
      const data = JSON.parse(decodeURIComponent(encodedProduct));
      currentModalProductName = data.name;
      document.getElementById('modalProductCategory').textContent = data.categoryTitle;
      document.getElementById('modalProductName').textContent = data.name;
      document.getElementById('modalProductSalePrice').textContent = data.salePrice;
      document.getElementById('modalProductOldPrice').textContent = data.oldPrice;
      document.getElementById('modalProductBadge').textContent = `Giảm ${data.discount}`;
      document.getElementById('modalProductDesc').textContent = data.desc;

      const imgEl = document.getElementById('modalProductImg');
      imgEl.src = getDriveImg(data.driveId);
      imgEl.onerror = function() {
        this.onerror = null;
        this.src = getDriveFallback(data.driveId);
      };

      const modal = document.getElementById('productDetailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeProductModal() {
      const modal = document.getElementById('productDetailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function prefillQuoteFromModal() {
      closeProductModal();
      const noteEl = document.getElementById('quoteNote');
      noteEl.value = `Tôi cần tư vấn và báo giá sản phẩm: ${currentModalProductName}`;
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
      document.getElementById('quoteName').focus();
    }

    // Xử lý gửi Form Báo Giá (Không dùng alert)
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('quoteName').value.trim();
      const phone = document.getElementById('quotePhone').value.trim();
      const cat = document.getElementById('quoteCategory').value;
      const box = document.getElementById('quoteSuccessBox');

      box.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5 text-green-600"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá mục <strong>${cat}</strong> đã được ghi nhận. Bộ phận kinh doanh <strong>CÔNG TY TNHH ĐIỆN MÁY - THIẾT BỊ BẾP 186</strong> sẽ liên hệ với quý khách ngay qua số <strong>0366.479.999</strong>.`;
      box.classList.remove('hidden');
      e.target.reset();
    }

    // Đóng mở menu danh mục trên điện thoại
    function toggleMobileDrawer(show) {
      const drawer = document.getElementById('mobileDrawer');
      const overlay = document.getElementById('mobileDrawerOverlay');
      if (show) {
        overlay.classList.remove('hidden');
        drawer.classList.remove('-translate-x-full');
      } else {
        overlay.classList.add('hidden');
        drawer.classList.add('-translate-x-full');
      }
    }

    // Tự động trượt 2 Banner trên cả máy tính và điện thoại
    let currentBannerIndex = 0;
    function setBannerSlide(index) {
      currentBannerIndex = index;
      const desktopSlides = document.querySelectorAll('.banner-slide-desktop');
      const mobileSlides = document.querySelectorAll('.banner-slide-mobile');
      const dot0 = document.getElementById('bannerDot0');
      const dot1 = document.getElementById('bannerDot1');

      desktopSlides.forEach((slide, i) => {
        if (i === index) {
          slide.classList.remove('opacity-0', 'pointer-events-none');
          slide.classList.add('opacity-100');
        } else {
          slide.classList.remove('opacity-100');
          slide.classList.add('opacity-0', 'pointer-events-none');
        }
      });

      mobileSlides.forEach((slide, i) => {
        if (i === index) {
          slide.classList.remove('opacity-0', 'pointer-events-none');
          slide.classList.add('opacity-100');
        } else {
          slide.classList.remove('opacity-100');
          slide.classList.add('opacity-0', 'pointer-events-none');
        }
      });

      if (index === 0) {
        dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
        dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
      } else {
        dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
        dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
      }
    }

    window.addEventListener('DOMContentLoaded', () => {
      renderAllCategories();
      setInterval(() => {
        setBannerSlide((currentBannerIndex + 1) % 2);
      }, 4500);
    });
  </script>
</body>
</html>
