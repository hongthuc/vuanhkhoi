<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI | vuanhkhoi.com</title>

  <!-- Meta SEO & Thumbnail chia sẻ link (Open Graph / Zalo / Facebook) sử dụng Logo Công ty -->
  <meta name="description" content="CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI (vuanhkhoi.com) - Chuyên Thiết kế Kiến trúc, Nội thất, Thi công phần thô, Hoàn thiện và Xây nhà trọn gói tại Đà Nẵng. Hotline: 0919 316 101 - 0906 467 764." />
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="VŨ ANH KHÔI - Kiến Trúc & Xây Dựng" />
  <meta property="og:url" content="https://vuanhkhoi.com/" />
  <meta property="og:title" content="CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI | vuanhkhoi.com" />
  <meta property="og:description" content="Thiết kế Kiến trúc - Thi công phần thô - Hoàn thiện - Xây nhà trọn gói uy tín tại Đà Nẵng. Địa chỉ: 01 Trần Phước Thành, Phường Cẩm Lệ, TP Đà Nẵng." />
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im&sz=w1000" />
  <meta property="og:image:width" content="1000" />
  <meta property="og:image:height" content="1000" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI" />
  <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng - Hotline: 0919 316 101 - 0906 467 764." />
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im&sz=w1000" />
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im&sz=w256" />

  <!-- Google Font Inter & Font Awesome Icons -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: 'var(--brand-primary)',
              primaryDark: 'var(--brand-primary-dark)',
              accent: 'var(--brand-accent)',
              accentHover: 'var(--brand-accent-hover)',
              surface: 'var(--brand-surface)',
            }
          }
        }
      }
    };
  </script>

  <!-- Bảng màu theo nhận diện logo Kiến trúc & Xây dựng (dễ dàng tinh chỉnh đồng bộ Flatsome) -->
  <style>
    :root {
      --brand-primary: #0F2B4C;       /* Xanh Navy đậm kiến trúc chủ đạo */
      --brand-primary-dark: #091B31;  /* Xanh đậm footer & topbar */
      --brand-accent: #C9962D;        /* Vàng đồng sang trọng đồng bộ logo */
      --brand-accent-hover: #B0801F;  /* Vàng đồng đậm khi hover */
      --brand-surface: #F6F8FB;       /* Nền xám sáng thanh lịch */
    }

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
      font-family: 'Inter', sans-serif;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      color: #1E293B;
      background-color: #FFFFFF;
    }

    /* Chiều ngang chuẩn 95% trên máy tính, cân giữa tuyệt đối không lệch phải */
    .vak-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .vak-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu dropdown kiểu Flatsome gọn gàng */
    .nav-item:hover .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
    }

    /* Banner trượt mượt, 2 ảnh bằng kích thước nhau */
    .banner-track {
      display: flex;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
      width: 100%;
    }

    .banner-slide {
      flex: 0 0 100%;
      width: 100%;
      min-width: 100%;
    }

    /* Hiệu ứng phóng nhẹ ảnh khi rê chuột (Flatsome zoom hover) */
    .fl-img-zoom img {
      transition: transform 0.45s ease;
    }
    .fl-img-zoom:hover img {
      transform: scale(1.05);
    }

    /* Hiệu ứng vòng sóng nhẹ cho nút liên hệ nổi bật */
    @keyframes pulseRing {
      0% { transform: scale(0.95); opacity: 0.75; }
      70% { transform: scale(1.22); opacity: 0; }
      100% { transform: scale(1.25); opacity: 0; }
    }
    .contact-pulse::before {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background: inherit;
      z-index: -1;
      animation: pulseRing 2.1s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 pb-16 lg:pb-0">

  <!-- ======================================================================= -->
  <!-- FLATSOME TOP BAR (Thông tin liên hệ gọn trên cùng)                       -->
  <!-- ======================================================================= -->
  <div class="w-full bg-[var(--brand-primary-dark)] text-slate-200 text-[11px] sm:text-xs py-2 border-b border-white/10">
    <div class="vak-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-[var(--brand-accent)]"></i>
          <span>01 Trần Phước Thành, Phường Cẩm Lệ, TP Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-[var(--brand-accent)]"></i>
          <span>vuanhkhoi.com</span>
        </span>
      </div>
      <div class="flex items-center gap-3 font-medium">
        <a href="tel:0919316101" class="inline-flex items-center gap-1.5 hover:text-[var(--brand-accent)] transition-colors whitespace-nowrap">
          <i class="fa-solid fa-phone text-[var(--brand-accent)]"></i>
          <span>0919 316 101</span>
        </a>
        <span class="text-white/30">|</span>
        <a href="tel:0906467764" class="inline-flex items-center gap-1.5 hover:text-[var(--brand-accent)] transition-colors whitespace-nowrap">
          <span>0906 467 764</span>
        </a>
      </div>
    </div>
  </div>

  <!-- ======================================================================= -->
  <!-- FLATSOME HEADER (Logo gọn nhỏ + Menu 1 hàng liền mạch, không nút gọi)   -->
  <!-- ======================================================================= -->
  <header id="site-header" class="sticky top-0 z-40 w-full bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="vak-container flex items-center justify-between gap-3 py-2.5 lg:py-3">
      <!-- Logo gọn nhỏ bên trái -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 max-w-[75%] lg:max-w-none">
        <img
          src="https://drive.google.com/thumbnail?id=11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im&sz=w400"
          alt="Logo Công ty TNHH Kiến Trúc và Xây Dựng Vũ Anh Khôi"
          class="h-10 sm:h-11 lg:h-12 w-auto object-contain rounded-md shrink-0"
          onerror="handleImgError(this, '11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im', 'VAK')"
        />
        <div class="leading-tight min-w-0">
          <span class="block text-[12px] sm:text-[13px] xl:text-[14px] font-extrabold text-[var(--brand-primary)] tracking-tight truncate">
            VŨ ANH KHÔI
          </span>
          <span class="block text-[10px] sm:text-[11px] font-semibold text-[var(--brand-accent)] tracking-wide truncate">
            KIẾN TRÚC &amp; XÂY DỰNG
          </span>
        </div>
      </a>

      <!-- Menu máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng tên danh mục -->
      <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end gap-3 xl:gap-5 flex-1 min-w-0">
        <a href="#trang-chu" class="whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-[var(--brand-primary)] hover:text-[var(--brand-accent)] py-2 transition-colors">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
          Giới thiệu
        </a>

        <!-- Dropdown Lĩnh vực hoạt động (theo web mẫu tintruongthinh.com) -->
        <div class="relative nav-item">
          <a href="#linh-vuc" class="inline-flex items-center gap-1 whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
            <span>Lĩnh vực hoạt động</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full w-60 bg-white border border-slate-200 rounded-xl shadow-lg py-2 z-50">
            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Thiết kế Kiến trúc – Nội thất</a>
            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Thi công phần thô</a>
            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Thi công hoàn thiện</a>
            <a href="#linh-vuc" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Thi công trọn gói &amp; Nội thất</a>
          </div>
        </div>

        <!-- Dropdown Công trình thực tế -->
        <div class="relative nav-item">
          <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1 whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
            <span>Công trình thực tế</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full w-60 bg-white border border-slate-200 rounded-xl shadow-lg py-2 z-50">
            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('all')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Tất cả công trình</a>
            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('phan-tho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Thi công phần thô</a>
            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('hoan-thien')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Thi công hoàn thiện</a>
            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Nhà phố – Biệt thự</a>
            <a href="#cong-trinh-thuc-te" onclick="filterConstruction('can-ho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Khách sạn – Căn hộ – Văn phòng</a>
          </div>
        </div>

        <a href="#du-an-da-nang" class="whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
          Dự án Đà Nẵng
        </a>

        <!-- Dropdown Báo giá -->
        <div class="relative nav-item">
          <a href="#bao-gia" class="inline-flex items-center gap-1 whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
            <span>Báo giá</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown absolute right-0 top-full w-60 bg-white border border-slate-200 rounded-xl shadow-lg py-2 z-50">
            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Báo giá thiết kế kiến trúc</a>
            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Báo giá thi công phần thô</a>
            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Báo giá thi công hoàn thiện</a>
            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-slate-50 hover:text-[var(--brand-accent)]">Báo giá thi công trọn gói</a>
          </div>
        </div>

        <a href="#doi-tac" class="whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
          Đối tác
        </a>
        <a href="#tin-tuc" class="whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
          Tin tức
        </a>
        <a href="#lien-he" class="whitespace-nowrap text-[11.5px] xl:text-[12.5px] font-bold uppercase text-slate-700 hover:text-[var(--brand-accent)] py-2 transition-colors">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở menu trên điện thoại & máy tính bảng -->
      <button
        id="mobile-menu-btn"
        type="button"
        aria-label="Mở menu điều hướng"
        class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-[var(--brand-primary)] hover:bg-slate-50 shrink-0"
      >
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>

    <!-- Menu trượt cho điện thoại -->
    <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="vak-container py-3 flex flex-col divide-y divide-slate-100">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 text-sm font-semibold text-[var(--brand-primary)]">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Giới thiệu</a>
        <a href="#linh-vuc" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Lĩnh vực hoạt động &amp; Dịch vụ</a>
        <a href="#cong-trinh-thuc-te" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Công trình thi công thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Dự án tiêu biểu tại Đà Nẵng</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Đối tác chiến lược</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Yêu cầu &amp; Báo giá</a>
        <a href="#tin-tuc" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Tin tức &amp; Kinh nghiệm</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 text-sm font-semibold text-slate-700">Bản đồ &amp; Liên hệ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU -->
    <!-- Hình ảnh và chữ nằm trọn bên trong, cách xa viền, không mất chữ        -->
    <!-- ===================================================================== -->
    <section aria-label="Banner nổi bật" class="w-full bg-[var(--brand-primary-dark)] pt-3 pb-4 lg:pt-4 lg:pb-6">
      <div class="vak-container">
        <div
          id="hero-slider"
          class="relative w-full overflow-hidden rounded-2xl shadow-lg bg-[var(--brand-primary)]"
        >
          <!-- Track chứa đúng 2 banner kích thước bằng nhau tuyệt đối -->
          <div id="banner-track" class="banner-track">

            <!-- BANNER 1 -->
            <div class="banner-slide relative h-[390px] sm:h-[430px] md:h-[470px] lg:h-[520px] flex items-center">
              <!-- Ảnh nền thực tế thi công phủ đều trong khung banner -->
              <img
                src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                alt="Thiết kế và thi công xây dựng trọn gói Vũ Anh Khôi"
                class="absolute inset-0 w-full h-full object-cover object-center"
                onerror="handleImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'VU ANH KHOI CONSTRUCTION')"
              />
              <!-- Lớp phủ tối tạo độ tương phản chữ sắc nét -->
              <div class="absolute inset-0 bg-gradient-to-r from-[#091B31]/90 via-[#0F2B4C]/75 to-[#091B31]/45"></div>

              <!-- Khối nội dung cách xa viền ảnh banner, đảm bảo không mất chữ trên mọi màn hình -->
              <div class="relative z-10 w-full h-full flex items-center px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-12">
                <div class="max-w-2xl text-white">
                  <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.16em] text-[var(--brand-accent)] mb-2 sm:mb-3">
                    CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI
                  </p>
                  <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-tight mb-3 sm:mb-4">
                    Kiến Tạo Không Gian Sống Bền Vững &amp; Chuẩn Mực Tại Đà Nẵng
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                    Chuyên Thiết kế Kiến trúc – Thi công phần thô – Hoàn thiện nội thất &amp; Xây nhà trọn gói cho Nhà phố, Biệt thự, Căn hộ và Khách sạn.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a
                      href="#bao-gia"
                      class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-xs sm:text-sm font-bold transition-colors shadow-md"
                    >
                      Nhận báo giá miễn phí
                    </a>
                    <a
                      href="#du-an-da-nang"
                      class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition-colors"
                    >
                      Xem dự án Đà Nẵng
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2 (Cùng kích thước chiều cao h-[390px] -> lg:h-[520px] chính xác với Banner 1) -->
            <div class="banner-slide relative h-[390px] sm:h-[430px] md:h-[470px] lg:h-[520px] flex items-center">
              <img
                src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                alt="Thi công thực tế chất lượng chuẩn kỹ thuật Vũ Anh Khôi"
                class="absolute inset-0 w-full h-full object-cover object-center"
                onerror="handleImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'THI CONG CHUAN KY THUAT')"
              />
              <div class="absolute inset-0 bg-gradient-to-r from-[#091B31]/90 via-[#0F2B4C]/75 to-[#091B31]/45"></div>

              <!-- Khối nội dung cách xa viền ảnh banner -->
              <div class="relative z-10 w-full h-full flex items-center px-11 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-12">
                <div class="max-w-2xl text-white">
                  <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.16em] text-[var(--brand-accent)] mb-2 sm:mb-3">
                    VAK CONSTRUCTION • AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ
                  </p>
                  <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-tight mb-3 sm:mb-4">
                    Thi Công Chuẩn Kỹ Thuật – Minh Bạch Vật Tư – Bảo Hành Dài Lâu
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                    Cam kết đúng tiến độ, không phát sinh chi phí, giám sát kỹ sư trực tiếp tại công trình và đồng hành tận tâm cùng gia chủ từ bản vẽ đến bàn giao.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a
                      href="#cong-trinh-thuc-te"
                      class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-xs sm:text-sm font-bold transition-colors shadow-md"
                    >
                      Xem ảnh thi công thực tế
                    </a>
                    <a
                      href="#lien-he"
                      class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition-colors"
                    >
                      Liên hệ tư vấn 24/7
                    </a>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển trái / phải gọn gàng sát mép nhưng không chạm chữ -->
          <button
            type="button"
            onclick="prevBanner()"
            aria-label="Banner trước"
            class="absolute left-2 sm:left-3.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[var(--brand-accent)] text-white flex items-center justify-center transition-colors"
          >
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
          </button>
          <button
            type="button"
            onclick="nextBanner()"
            aria-label="Banner kế tiếp"
            class="absolute right-2 sm:right-3.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-[var(--brand-accent)] text-white flex items-center justify-center transition-colors"
          >
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
          </button>

          <!-- Chấm chỉ báo 2 banner -->
          <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" onclick="goToBanner(0)" id="dot-0" aria-label="Chuyển tới banner 1" class="w-7 h-2 rounded-full bg-[var(--brand-accent)] transition-all"></button>
            <button type="button" onclick="goToBanner(1)" id="dot-1" aria-label="Chuyển tới banner 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white/80 transition-all"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 2: 3 DỊCH VỤ TIÊU BIỂU (Giống bố cục tintruongthinh)  -->
    <!-- ===================================================================== -->
    <section class="w-full py-10 lg:py-14 bg-white">
      <div class="vak-container">
        <div class="text-center max-w-3xl mx-auto mb-8">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] uppercase tracking-tight">
            Dịch Vụ Tiêu Biểu
          </h2>
          <div class="w-16 h-1 bg-[var(--brand-accent)] mx-auto mt-3 rounded-full"></div>
        </div>

        <!-- 3 khối dịch vụ trụ cột giống mẫu Flatsome: Thiết kế - Thi công - Nội thất -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 lg:gap-6">
          <a href="#linh-vuc" class="group relative rounded-2xl overflow-hidden h-56 sm:h-64 shadow-sm border border-slate-200 fl-img-zoom block">
            <img
              src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1000"
              alt="Thiết kế kiến trúc Vũ Anh Khôi"
              class="w-full h-full object-cover"
              onerror="handleImgError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'THIET KE KIEN TRUC')"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#091B31]/90 via-[#091B31]/40 to-transparent flex flex-col justify-end p-5 sm:p-6">
              <h3 class="text-lg sm:text-xl font-extrabold text-white uppercase tracking-wide group-hover:text-[var(--brand-accent)] transition-colors">
                THIẾT KẾ
              </h3>
              <p class="text-xs sm:text-sm text-slate-200 mt-1">
                Kiến trúc nhà phố, biệt thự, căn hộ, khách sạn &amp; hồ sơ kỹ thuật thi công chi tiết.
              </p>
            </div>
          </a>

          <a href="#cong-trinh-thuc-te" class="group relative rounded-2xl overflow-hidden h-56 sm:h-64 shadow-sm border border-slate-200 fl-img-zoom block">
            <img
              src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
              alt="Thi công xây dựng Vũ Anh Khôi"
              class="w-full h-full object-cover"
              onerror="handleImgError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'THI CONG XAY DUNG')"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#091B31]/90 via-[#091B31]/40 to-transparent flex flex-col justify-end p-5 sm:p-6">
              <h3 class="text-lg sm:text-xl font-extrabold text-white uppercase tracking-wide group-hover:text-[var(--brand-accent)] transition-colors">
                THI CÔNG
              </h3>
              <p class="text-xs sm:text-sm text-slate-200 mt-1">
                Thi công phần thô, hoàn thiện &amp; xây nhà trọn gói chìa khóa trao tay chuẩn kết cấu.
              </p>
            </div>
          </a>

          <a href="#du-an-da-nang" class="group relative rounded-2xl overflow-hidden h-56 sm:h-64 shadow-sm border border-slate-200 fl-img-zoom block">
            <img
              src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1000"
              alt="Thi công nội thất Vũ Anh Khôi"
              class="w-full h-full object-cover"
              onerror="handleImgError(this, '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz', 'NOI THAT HOAN THIEN')"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-[#091B31]/90 via-[#091B31]/40 to-transparent flex flex-col justify-end p-5 sm:p-6">
              <h3 class="text-lg sm:text-xl font-extrabold text-white uppercase tracking-wide group-hover:text-[var(--brand-accent)] transition-colors">
                NỘI THẤT
              </h3>
              <p class="text-xs sm:text-sm text-slate-200 mt-1">
                Thiết kế &amp; sản xuất lắp đặt nội thất đồng bộ, tối ưu công năng và thẩm mỹ hiện đại.
              </p>
            </div>
          </a>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 3: GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI        -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="w-full py-12 lg:py-16 bg-[var(--brand-surface)] border-y border-slate-200/80">
      <div class="vak-container">
        <!-- Giới thiệu công ty (Row 2 cột dễ dựng lại trên UX Builder) -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center mb-12">
          <div class="lg:col-span-6">
            <p class="text-xs font-bold uppercase tracking-widest text-[var(--brand-accent)] mb-2">
              VỀ CHÚNG TÔI
            </p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] leading-snug mb-4">
              CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI
            </h2>
            <p class="text-sm sm:text-base text-slate-600 leading-relaxed mb-4">
              <strong>Vũ Anh Khôi (VAK Construction)</strong> là đơn vị chuyên sâu trong lĩnh vực Tư vấn – Thiết kế Kiến trúc – Thi công phần thô, Hoàn thiện và Nội thất cho các công trình Nhà phố, Biệt thự, Căn hộ cho thuê, Khách sạn và Văn phòng tại khu vực Đà Nẵng và miền Trung.
            </p>
            <p class="text-sm sm:text-base text-slate-600 leading-relaxed mb-6">
              Với phương châm <strong>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</strong>, chúng tôi đặt chữ <strong>TÂM</strong> lên hàng đầu trong từng hạng mục thi công để mỗi công trình bàn giao đều đạt trọn vẹn 4 giá trị: <strong>An toàn – Chất lượng – Tiến độ – Sự hài lòng bền vững</strong>.
            </p>
            <div class="grid grid-cols-3 gap-3 sm:gap-4 pt-2 border-t border-slate-200">
              <div class="bg-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80">
                <div class="text-xl sm:text-2xl font-extrabold text-[var(--brand-primary)]">100%</div>
                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5 font-medium">Vật tư chuẩn cam kết</div>
              </div>
              <div class="bg-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80">
                <div class="text-xl sm:text-2xl font-extrabold text-[var(--brand-accent)]">5 Năm</div>
                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5 font-medium">Bảo hành kết cấu</div>
              </div>
              <div class="bg-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80">
                <div class="text-xl sm:text-2xl font-extrabold text-[var(--brand-primary)]">24/7</div>
                <div class="text-[11px] sm:text-xs text-slate-500 mt-0.5 font-medium">Hỗ trợ &amp; giám sát</div>
              </div>
            </div>
          </div>

          <div class="lg:col-span-6">
            <div class="grid grid-cols-2 gap-3 sm:gap-4">
              <div class="rounded-2xl overflow-hidden shadow-sm border border-slate-200 h-44 sm:h-60 fl-img-zoom">
                <img
                  src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w900"
                  alt="Đội ngũ kỹ sư thi công thực tế Vũ Anh Khôi"
                  class="w-full h-full object-cover"
                  onerror="handleImgError(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv', 'THI CONG THUC TE')"
                />
              </div>
              <div class="rounded-2xl overflow-hidden shadow-sm border border-slate-200 h-44 sm:h-60 fl-img-zoom">
                <img
                  src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w900"
                  alt="Công trình kiến trúc hoàn thiện tại Đà Nẵng"
                  class="w-full h-full object-cover"
                  onerror="handleImgError(this, '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k', 'DU AN DA NANG')"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- Thế mạnh của chúng tôi (6 Icon Boxes chuẩn Flatsome) -->
        <div class="text-center max-w-3xl mx-auto mb-8">
          <h3 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-[var(--brand-primary)] uppercase">
            Thế Mạnh Của Chúng Tôi
          </h3>
          <div class="w-14 h-1 bg-[var(--brand-accent)] mx-auto mt-2.5 rounded-full"></div>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 lg:gap-5">
          <div class="bg-white rounded-2xl p-5 border border-slate-200/90 shadow-sm flex items-start gap-4">
            <div class="w-11 h-11 rounded-xl bg-[var(--brand-primary)] text-[var(--brand-accent)] flex items-center justify-center shrink-0 text-lg">
              <i class="fa-solid fa-helmet-safety"></i>
            </div>
            <div>
              <h4 class="text-sm sm:text-base font-bold text-[var(--brand-primary)] mb-1">Đội ngũ KTS &amp; kỹ sư chuyên nghiệp</h4>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng kỹ sư giàu kinh nghiệm và đội thợ tay nghề cao trực tiếp thi công.</p>
            </div>
          </div>

          <div class="bg-white rounded-2xl p-5 border border-slate-200/90 shadow-sm flex items-start gap-4">
            <div class="w-11 h-11 rounded-xl bg-[var(--brand-primary)] text-[var(--brand-accent)] flex items-center justify-center shrink-0 text-lg">
              <i class="fa-solid fa-compass-drafting"></i>
            </div>
            <div>
              <h4 class="text-sm sm:text-base font-bold text-[var(--brand-primary)] mb-1">Cập nhật xu hướng kiến trúc mới</h4>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Ứng dụng giải pháp thiết kế hiện đại, tối ưu thông gió, ánh sáng tự nhiên và vật liệu bền đẹp.</p>
            </div>
          </div>

          <div class="bg-white rounded-2xl p-5 border border-slate-200/90 shadow-sm flex items-start gap-4">
            <div class="w-11 h-11 rounded-xl bg-[var(--brand-primary)] text-[var(--brand-accent)] flex items-center justify-center shrink-0 text-lg">
              <i class="fa-solid fa-calendar-check"></i>
            </div>
            <div>
              <h4 class="text-sm sm:text-base font-bold text-[var(--brand-primary)] mb-1">Giám sát tiến độ chuẩn xác</h4>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Báo cáo tiến độ và hình ảnh công trường thường xuyên để gia chủ dễ dàng theo dõi mọi lúc mọi nơi.</p>
            </div>
          </div>

          <div class="bg-white rounded-2xl p-5 border border-slate-200/90 shadow-sm flex items-start gap-4">
            <div class="w-11 h-11 rounded-xl bg-[var(--brand-primary)] text-[var(--brand-accent)] flex items-center justify-center shrink-0 text-lg">
              <i class="fa-solid fa-shield-halved"></i>
            </div>
            <div>
              <h4 class="text-sm sm:text-base font-bold text-[var(--brand-primary)] mb-1">Bảo hành công trình lâu dài</h4>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Chế độ bảo hành kết cấu và chống thấm rõ ràng, hỗ trợ nhanh chóng sau khi bàn giao nhà.</p>
            </div>
          </div>

          <div class="bg-white rounded-2xl p-5 border border-slate-200/90 shadow-sm flex items-start gap-4">
            <div class="w-11 h-11 rounded-xl bg-[var(--brand-primary)] text-[var(--brand-accent)] flex items-center justify-center shrink-0 text-lg">
              <i class="fa-solid fa-file-invoice-dollar"></i>
            </div>
            <div>
              <h4 class="text-sm sm:text-base font-bold text-[var(--brand-primary)] mb-1">Chi phí minh bạch &amp; hợp lý</h4>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục, chủng loại vật tư rõ ràng và cam kết không phát sinh vô lý.</p>
            </div>
          </div>

          <div class="bg-white rounded-2xl p-5 border border-slate-200/90 shadow-sm flex items-start gap-4">
            <div class="w-11 h-11 rounded-xl bg-[var(--brand-primary)] text-[var(--brand-accent)] flex items-center justify-center shrink-0 text-lg">
              <i class="fa-solid fa-headset"></i>
            </div>
            <div>
              <h4 class="text-sm sm:text-base font-bold text-[var(--brand-primary)] mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
              <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Khảo sát mặt bằng tận nơi tại Đà Nẵng, tư vấn phương án công năng và khái toán chi phí miễn phí.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 4: DANH MỤC SẢN PHẨM & DỊCH VỤ (Từ web mẫu)          -->
    <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính, không nhãn dán       -->
    <!-- ===================================================================== -->
    <section id="linh-vuc" class="w-full py-12 lg:py-16 bg-white">
      <div class="vak-container">
        <div class="text-center max-w-3xl mx-auto mb-6">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] uppercase tracking-tight">
            Danh Mục Sản Phẩm &amp; Dịch Vụ
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Giải pháp kiến trúc &amp; xây dựng đồng bộ từ thiết kế bản vẽ đến thi công hoàn thiện chìa khóa trao tay
          </p>
          <div class="w-16 h-1 bg-[var(--brand-accent)] mx-auto mt-3 rounded-full"></div>
        </div>

        <!-- Grid 2 cột trên điện thoại, 4 cột trên máy tính; tên sản phẩm trọn vẹn không mất chữ -->
        <div id="services-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4 lg:gap-5">
          <!-- Render tự động bằng JS để đồng bộ dữ liệu & modal xem chi tiết -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 5: CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ảnh thực tế Drive) -->
    <!-- ===================================================================== -->
    <section id="cong-trinh-thuc-te" class="w-full py-12 lg:py-16 bg-[var(--brand-surface)] border-y border-slate-200/80">
      <div class="vak-container">
        <div class="text-center max-w-3xl mx-auto mb-5">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] uppercase tracking-tight">
            Công Trình Thi Công Thực Tế
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Hình ảnh ghi nhận trực tiếp tại các công trường do Vũ Anh Khôi trực tiếp triển khai thi công
          </p>
          <div class="w-16 h-1 bg-[var(--brand-accent)] mx-auto mt-3 rounded-full"></div>
        </div>

        <!-- Thanh lọc danh mục nhỏ gọn, viết liền không xuống dòng trong từng tên danh mục -->
        <div id="construction-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
          <button type="button" onclick="filterConstruction('all')" data-cat="all" class="construction-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-[var(--brand-primary)] text-white">
            Tất cả
          </button>
          <button type="button" onclick="filterConstruction('phan-tho')" data-cat="phan-tho" class="construction-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-white text-slate-700 border border-slate-200 hover:border-[var(--brand-accent)]">
            Thi công phần thô
          </button>
          <button type="button" onclick="filterConstruction('hoan-thien')" data-cat="hoan-thien" class="construction-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-white text-slate-700 border border-slate-200 hover:border-[var(--brand-accent)]">
            Thi công hoàn thiện
          </button>
          <button type="button" onclick="filterConstruction('nha-pho')" data-cat="nha-pho" class="construction-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-white text-slate-700 border border-slate-200 hover:border-[var(--brand-accent)]">
            Nhà phố – Biệt thự
          </button>
          <button type="button" onclick="filterConstruction('can-ho')" data-cat="can-ho" class="construction-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-white text-slate-700 border border-slate-200 hover:border-[var(--brand-accent)]">
            Căn hộ – Văn phòng
          </button>
        </div>

        <!-- Lưới 2 cột trên điện thoại, 3 cột tablet/desktop -->
        <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-2.5 sm:gap-4 lg:gap-5">
          <!-- Render 9 ảnh thi công thực tế bằng JS -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 6: DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ảnh dự án Drive)  -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="w-full py-12 lg:py-16 bg-white">
      <div class="vak-container">
        <div class="text-center max-w-3xl mx-auto mb-5">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] uppercase tracking-tight">
            Các Dự Án Tiêu Biểu Tại Đà Nẵng
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Bộ sưu tập công trình thiết kế và thi công nổi bật do Vũ Anh Khôi thực hiện khắp các quận tại TP Đà Nẵng
          </p>
          <div class="w-16 h-1 bg-[var(--brand-accent)] mx-auto mt-3 rounded-full"></div>
        </div>

        <!-- Danh mục lọc khu vực Đà Nẵng nhỏ gọn -->
        <div id="danang-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
          <button type="button" onclick="filterDaNang('all')" data-cat="all" class="danang-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-[var(--brand-primary)] text-white">
            Tất cả dự án
          </button>
          <button type="button" onclick="filterDaNang('cam-le')" data-cat="cam-le" class="danang-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-slate-100 text-slate-700 hover:bg-slate-200">
            Cẩm Lệ – Hòa Xuân
          </button>
          <button type="button" onclick="filterDaNang('hai-chau')" data-cat="hai-chau" class="danang-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-slate-100 text-slate-700 hover:bg-slate-200">
            Hải Châu – Thanh Khê
          </button>
          <button type="button" onclick="filterDaNang('son-tra')" data-cat="son-tra" class="danang-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-slate-100 text-slate-700 hover:bg-slate-200">
            Sơn Trà – Ngũ Hành Sơn
          </button>
          <button type="button" onclick="filterDaNang('lien-chieu')" data-cat="lien-chieu" class="danang-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-slate-100 text-slate-700 hover:bg-slate-200">
            Liên Chiểu – Hòa Vang
          </button>
        </div>

        <!-- Lưới 2 cột trên điện thoại, 5 cột (2 hàng x 5 ảnh) trên desktop lớn / 4 cột laptop -->
        <div id="danang-grid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4">
          <!-- Render 10 dự án Đà Nẵng bằng JS -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 7: DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC                   -->
    <!-- ===================================================================== -->
    <section id="doi-tac" class="w-full py-10 lg:py-14 bg-[var(--brand-surface)] border-y border-slate-200/80">
      <div class="vak-container">
        <div class="text-center max-w-3xl mx-auto mb-7">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] uppercase tracking-tight">
            Đối Tác &amp; Nhà Cung Cấp Vật Tư
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Hợp tác cùng các thương hiệu vật liệu xây dựng hàng đầu đảm bảo độ bền vững cho từng công trình
          </p>
          <div class="w-16 h-1 bg-[var(--brand-accent)] mx-auto mt-3 rounded-full"></div>
        </div>

        <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
        <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-4">
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#005BAA]">HÒA PHÁT</span>
            <span class="text-[11px] text-slate-500 mt-1">Thép xây dựng tiêu chuẩn</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#C62828]">SÔNG GIANH</span>
            <span class="text-[11px] text-slate-500 mt-1">Xi măng công trình miền Trung</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#1565C0]">DULUX</span>
            <span class="text-[11px] text-slate-500 mt-1">Sơn nội ngoại thất cao cấp</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#0D47A1]">JOTUN</span>
            <span class="text-[11px] text-slate-500 mt-1">Sơn chống thấm bảo vệ bền màu</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#1E293B]">TOTO</span>
            <span class="text-[11px] text-slate-500 mt-1">Thiết bị vệ sinh chính hãng</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#B45309]">AN CƯỜNG</span>
            <span class="text-[11px] text-slate-500 mt-1">Gỗ công nghiệp nội thất</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#B91C1C]">CADIVI</span>
            <span class="text-[11px] text-slate-500 mt-1">Dây cáp điện an toàn PCCC</span>
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col items-center justify-center text-center shadow-sm hover:border-[var(--brand-accent)] transition-colors">
            <span class="text-base sm:text-lg font-extrabold tracking-wider text-[#0F766E]">XINGFA</span>
            <span class="text-[11px] text-slate-500 mt-1">Hệ cửa nhôm kính nhập khẩu</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 8: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (Trang chủ)         -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="w-full py-12 lg:py-16 bg-[var(--brand-primary)] text-white">
      <div class="vak-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <!-- Thông tin cam kết báo giá bên trái -->
          <div class="lg:col-span-5">
            <p class="text-xs font-bold uppercase tracking-widest text-[var(--brand-accent)] mb-2">
              MIỄN PHÍ TƯ VẤN &amp; KHẢO SÁT
            </p>
            <h2 class="text-2xl sm:text-3xl font-extrabold leading-snug mb-4">
              Đăng Ký Yêu Cầu Tư Vấn &amp; Báo Giá Xây Dựng
            </h2>
            <p class="text-sm text-slate-200 leading-relaxed mb-6">
              Để lại thông tin công trình dự kiến của quý khách, đội ngũ kiến trúc sư và kỹ sư dự toán của <strong>Vũ Anh Khôi</strong> sẽ liên hệ tư vấn phương án tối ưu chi phí trong vòng 30 phút.
            </p>
            <div class="space-y-3 text-sm">
              <div class="flex items-center gap-3">
                <span class="w-9 h-9 rounded-lg bg-white/10 text-[var(--brand-accent)] flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-phone-volume"></i>
                </span>
                <div>
                  <div class="text-xs text-slate-300">Hotline tư vấn trực tiếp</div>
                  <div class="font-bold">0919 316 101 – 0906 467 764</div>
                </div>
              </div>
              <div class="flex items-center gap-3">
                <span class="w-9 h-9 rounded-lg bg-white/10 text-[var(--brand-accent)] flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-location-dot"></i>
                </span>
                <div>
                  <div class="text-xs text-slate-300">Văn phòng giao dịch</div>
                  <div class="font-bold">01 Trần Phước Thành, Phường Cẩm Lệ, TP Đà Nẵng</div>
                </div>
              </div>
              <div class="flex items-center gap-3">
                <span class="w-9 h-9 rounded-lg bg-white/10 text-[var(--brand-accent)] flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-globe"></i>
                </span>
                <div>
                  <div class="text-xs text-slate-300">Website chính thức</div>
                  <div class="font-bold">vuanhkhoi.com</div>
                </div>
              </div>
            </div>
          </div>

          <!-- Form đăng ký giống mẫu tintruongthinh.com -->
          <div class="lg:col-span-7">
            <form id="quote-form" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="q-name" class="block text-xs font-bold text-slate-700 mb-1.5">Họ và tên *</label>
                  <input id="q-name" type="text" required placeholder="Nhập họ tên quý khách" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-accent)] focus:ring-2 focus:ring-[var(--brand-accent)]/20" />
                </div>
                <div>
                  <label for="q-phone" class="block text-xs font-bold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                  <input id="q-phone" type="tel" required placeholder="VD: 0919 316 101" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-accent)] focus:ring-2 focus:ring-[var(--brand-accent)]/20" />
                </div>
                <div>
                  <label for="q-type" class="block text-xs font-bold text-slate-700 mb-1.5">Loại công trình</label>
                  <select id="q-type" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm bg-white focus:outline-none focus:border-[var(--brand-accent)]">
                    <option value="Nhà phố">Nhà phố hiện đại</option>
                    <option value="Biệt thự">Biệt thự / Villa</option>
                    <option value="Khách sạn – Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                    <option value="Văn phòng">Văn phòng / Showroom</option>
                    <option value="Thiết kế & Thi công nội thất">Thiết kế &amp; Thi công nội thất</option>
                    <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa nhà trọn gói</option>
                  </select>
                </div>
                <div>
                  <label for="q-budget" class="block text-xs font-bold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                  <select id="q-budget" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm bg-white focus:outline-none focus:border-[var(--brand-accent)]">
                    <option value="Chưa xác định">Chưa xác định</option>
                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                    <option value="500 triệu – 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 – 2 tỷ">1 – 2 tỷ</option>
                    <option value="2 – 3 tỷ">2 – 3 tỷ</option>
                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  </select>
                </div>
                <div class="sm:col-span-2">
                  <label for="q-email" class="block text-xs font-bold text-slate-700 mb-1.5">Email (không bắt buộc)</label>
                  <input id="q-email" type="email" placeholder="Nhập email nhận bảng dự toán chi tiết" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-accent)] focus:ring-2 focus:ring-[var(--brand-accent)]/20" />
                </div>
                <div class="sm:col-span-2">
                  <label for="q-note" class="block text-xs font-bold text-slate-700 mb-1.5">Mô tả diện tích đất, số tầng &amp; yêu cầu báo giá</label>
                  <textarea id="q-note" rows="3" placeholder="VD: Diện tích 5x20m tại Hòa Xuân, dự kiến xây 3 tầng trọn gói..." class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-[var(--brand-accent)] focus:ring-2 focus:ring-[var(--brand-accent)]/20"></textarea>
                </div>
              </div>
              <button
                type="submit"
                class="mt-5 w-full py-3 rounded-xl bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-sm font-bold uppercase tracking-wide shadow-md transition-colors"
              >
                Gửi Yêu Cầu Báo Giá Ngay
              </button>
              <div id="quote-feedback" class="hidden mt-4 p-3.5 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 9: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức)         -->
    <!-- ===================================================================== -->
    <section id="tin-tuc" class="w-full py-12 lg:py-16 bg-white">
      <div class="vak-container">
        <div class="text-center max-w-3xl mx-auto mb-7">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] uppercase tracking-tight">
            Tin Tức &amp; Kinh Nghiệm Xây Dựng
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2">
            Kiến thức chuyên môn về thiết kế kiến trúc, kỹ thuật thi công và kinh nghiệm xây nhà thực tế tại Đà Nẵng
          </p>
          <div class="w-16 h-1 bg-[var(--brand-accent)] mx-auto mt-3 rounded-full"></div>
        </div>

        <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
        <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4 lg:gap-5">
          <!-- Render danh sách bài viết bằng JS -->
        </div>
      </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FLATSOME SECTION 10: GOOGLE MAP & FANPAGE FACEBOOK NGAY TRANG CHỦ     -->
    <!-- ===================================================================== -->
    <section id="lien-he" class="w-full py-12 lg:py-16 bg-[var(--brand-surface)] border-t border-slate-200/80">
      <div class="vak-container">
        <div class="text-center max-w-3xl mx-auto mb-8">
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-[var(--brand-primary)] uppercase tracking-tight">
            Kết Nối &amp; Chỉ Đường Đến Vũ Anh Khôi
          </h2>
          <div class="w-16 h-1 bg-[var(--brand-accent)] mx-auto mt-3 rounded-full"></div>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-6 items-stretch">
          <!-- Cột trái: Bản đồ Google Maps địa chỉ 01 Trần Phước Thành, Phường Cẩm Lệ, TP Đà Nẵng -->
          <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
            <div class="px-5 py-3.5 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-map-location-dot text-[var(--brand-accent)] text-lg"></i>
                <h3 class="text-sm sm:text-base font-bold text-[var(--brand-primary)]">
                  Bản Đồ Google Map – Văn Phòng Đà Nẵng
                </h3>
              </div>
              <a
                href="https://www.google.com/maps/search/?api=1&query=01+Tr%E1%BA%A7n+Ph%C6%B0%E1%BB%9Bc+Th%C3%A0nh,+Ph%C6%B0%E1%BB%9Dng+C%E1%BA%A9m+L%E1%BB%87,+TP+%C4%90%C3%A0+N%E1%BA%B5ng"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold text-[var(--brand-accent)] hover:underline whitespace-nowrap"
              >
                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-[10px]"></i>
              </a>
            </div>
            <div class="w-full h-[320px] sm:h-[360px] flex-1 bg-slate-100">
              <iframe
                title="Bản đồ Công ty TNHH Kiến Trúc và Xây Dựng Vũ Anh Khôi - 01 Trần Phước Thành, Cẩm Lệ, Đà Nẵng"
                src="https://maps.google.com/maps?q=01%20Tr%E1%BA%A7n%20Ph%C6%B0%E1%BB%9Bc%20Th%C3%A0nh,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
                allowfullscreen
              ></iframe>
            </div>
            <div class="px-5 py-3 bg-slate-50 border-t border-slate-100 text-xs text-slate-600 flex flex-wrap items-center justify-between gap-2">
              <span><strong class="text-[var(--brand-primary)]">Địa chỉ:</strong> 01 Trần Phước Thành, Phường Cẩm Lệ, TP Đà Nẵng</span>
              <span><strong class="text-[var(--brand-primary)]">Hotline:</strong> 0919 316 101 – 0906 467 764</span>
            </div>
          </div>

          <!-- Cột phải: Fanpage Facebook chính thức hiển thị ngay ngoài trang chủ -->
          <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
            <div class="px-5 py-3.5 border-b border-slate-100 flex items-center justify-between gap-2">
              <div class="flex items-center gap-2">
                <i class="fa-brands fa-facebook text-[#1877F2] text-lg"></i>
                <h3 class="text-sm sm:text-base font-bold text-[var(--brand-primary)]">
                  Fanpage Chính Thức
                </h3>
              </div>
              <a
                href="https://www.facebook.com/search/top?q=C%C3%B4ng%20ty%20TNHH%20Ki%E1%BA%BFn%20Tr%C3%BAc%20v%C3%A0%20X%C3%A2y%20D%E1%BB%B1ng%20V%C5%A9%20Anh%20Kh%C3%B4i"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold text-[#1877F2] hover:underline whitespace-nowrap"
              >
                Theo dõi Fanpage
              </a>
            </div>

            <!-- Khung Fanpage Facebook trực quan (dễ dàng dán mã nhúng Facebook Page Plugin khi đưa lên Flatsome) -->
            <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between">
              <div>
                <!-- Ảnh bìa Fanpage -->
                <div class="relative h-36 sm:h-40 rounded-xl overflow-hidden border border-slate-200">
                  <img
                    src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w900"
                    alt="Ảnh bìa Fanpage Kiến Trúc & Xây Dựng Vũ Anh Khôi"
                    class="w-full h-full object-cover"
                    onerror="handleImgError(this, '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N', 'FANPAGE VU ANH KHOI')"
                  />
                  <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                  <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-white p-1 shadow-md shrink-0 flex items-center justify-center">
                      <img
                        src="https://drive.google.com/thumbnail?id=11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im&sz=w200"
                        alt="Avatar Fanpage Vũ Anh Khôi"
                        class="w-full h-full object-contain rounded-lg"
                        onerror="handleImgError(this, '11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im', 'VAK')"
                      />
                    </div>
                    <div class="min-w-0 text-white">
                      <div class="text-sm font-bold leading-snug truncate">Kiến Trúc &amp; Xây Dựng Vũ Anh Khôi</div>
                      <div class="text-[11px] text-slate-200 truncate">Công ty Kiến trúc &amp; Xây dựng tại Đà Nẵng</div>
                    </div>
                  </div>
                </div>

                <!-- Bài đăng nổi bật trên Fanpage -->
                <div class="mt-4 space-y-2.5">
                  <div class="p-3 rounded-xl bg-slate-50 border border-slate-100">
                    <p class="text-xs font-bold text-[var(--brand-primary)] mb-1">Cập nhật tiến độ công trình tại Cẩm Lệ – Hòa Xuân</p>
                    <p class="text-xs text-slate-600 leading-relaxed">
                      Đội ngũ kỹ sư Vũ Anh Khôi hoàn thành công tác nghiệm thu cốt thép sàn và chuẩn bị đổ bê tông đúng quy chuẩn kỹ thuật.
                    </p>
                  </div>
                  <div class="p-3 rounded-xl bg-slate-50 border border-slate-100">
                    <p class="text-xs font-bold text-[var(--brand-primary)] mb-1">Tư vấn thiết kế &amp; dự toán xây nhà trọn gói 2026</p>
                    <p class="text-xs text-slate-600 leading-relaxed">
                      Nhắn tin trực tiếp qua Fanpage hoặc Zalo 0919 316 101 để nhận bảng đơn giá chi tiết và khảo sát miễn phí tại Đà Nẵng.
                    </p>
                  </div>
                </div>
              </div>

              <!-- Nút hành động Fanpage -->
              <div class="grid grid-cols-2 gap-2.5 mt-4 pt-3 border-t border-slate-100">
                <a
                  href="https://www.facebook.com/search/top?q=C%C3%B4ng%20ty%20TNHH%20Ki%E1%BA%BFn%20Tr%C3%BAc%20v%C3%A0%20X%C3%A2y%20D%E1%BB%B1ng%20V%C5%A9%20Anh%20Kh%C3%B4i"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-xl bg-[#1877F2] hover:bg-[#1465D1] text-white text-xs font-bold transition-colors"
                >
                  <i class="fa-brands fa-facebook-f"></i>
                  <span>Thích Trang</span>
                </a>
                <a
                  href="https://zalo.me/0919316101"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-xl bg-slate-100 hover:bg-slate-200 text-[var(--brand-primary)] text-xs font-bold transition-colors"
                >
                  <i class="fa-regular fa-comment-dots"></i>
                  <span>Nhắn Tin Tư Vấn</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ======================================================================= -->
  <!-- FLATSOME FOOTER (4 cột gọn gàng, đầy đủ pháp lý & liên hệ)              -->
  <!-- ======================================================================= -->
  <footer class="w-full bg-[var(--brand-primary-dark)] text-slate-300 pt-12 pb-8">
    <div class="vak-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-8 pb-10 border-b border-white/10">

        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-4">
          <div class="flex items-center gap-3 mb-4">
            <div class="bg-white rounded-lg p-1.5 shrink-0">
              <img
                src="https://drive.google.com/thumbnail?id=11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im&sz=w300"
                alt="Logo Vũ Anh Khôi"
                class="h-10 w-auto object-contain"
                onerror="handleImgError(this, '11gH9qtpVuc2rLrRb_U4Q9-KwQYukG5Im', 'VAK')"
              />
            </div>
            <div>
              <h3 class="text-sm font-extrabold text-white uppercase leading-snug">
                CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI
              </h3>
              <p class="text-xs text-[var(--brand-accent)] font-semibold">VAK CONSTRUCTION</p>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-[var(--brand-accent)] mt-1 shrink-0"></i>
              <span>Trụ sở: 01 Trần Phước Thành, Phường Cẩm Lệ, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-[var(--brand-accent)] shrink-0"></i>
              <span>Hotline: <a href="tel:0919316101" class="text-white font-semibold hover:text-[var(--brand-accent)]">0919 316 101</a> – <a href="tel:0906467764" class="text-white font-semibold hover:text-[var(--brand-accent)]">0906 467 764</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-globe text-[var(--brand-accent)] shrink-0"></i>
              <span>Website: <a href="https://vuanhkhoi.com" class="text-white hover:text-[var(--brand-accent)]">vuanhkhoi.com</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-building-shield text-[var(--brand-accent)] shrink-0"></i>
              <span>Mã số thuế: 0402199882</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-4 pb-2 border-b border-white/10">
            Lĩnh Vực Hoạt Động
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#linh-vuc" class="hover:text-[var(--brand-accent)] transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc" class="hover:text-[var(--brand-accent)] transition-colors">Thi công phần thô chuẩn kỹ thuật</a></li>
            <li><a href="#linh-vuc" class="hover:text-[var(--brand-accent)] transition-colors">Thi công hoàn thiện công trình</a></li>
            <li><a href="#linh-vuc" class="hover:text-[var(--brand-accent)] transition-colors">Xây nhà trọn gói chìa khóa trao tay</a></li>
            <li><a href="#linh-vuc" class="hover:text-[var(--brand-accent)] transition-colors">Thi công nội thất &amp; Cải tạo nhà</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục nhanh -->
        <div class="lg:col-span-2">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-4 pb-2 border-b border-white/10">
            Danh Mục Chính
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#gioi-thieu" class="hover:text-[var(--brand-accent)] transition-colors">Giới thiệu công ty</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-[var(--brand-accent)] transition-colors">Công trình thực tế</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-[var(--brand-accent)] transition-colors">Dự án tại Đà Nẵng</a></li>
            <li><a href="#doi-tac" class="hover:text-[var(--brand-accent)] transition-colors">Đối tác vật tư</a></li>
            <li><a href="#tin-tuc" class="hover:text-[var(--brand-accent)] transition-colors">Tin tức xây dựng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Giờ làm việc & Cam kết -->
        <div class="lg:col-span-3">
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-4 pb-2 border-b border-white/10">
            Hỗ Trợ Khách Hàng
          </h4>
          <p class="text-xs sm:text-sm leading-relaxed mb-3">
            Tư vấn &amp; tiếp nhận yêu cầu khảo sát công trình tất cả các ngày trong tuần tại Đà Nẵng và khu vực miền Trung.
          </p>
          <p class="text-xs text-slate-400">Thứ 2 – Thứ 7: 07:30 – 17:30</p>
          <p class="text-xs text-slate-400 mt-1">Hotline tư vấn nhanh: 24/7</p>
          <div class="flex items-center gap-2.5 mt-4">
            <a href="https://zalo.me/0919316101" target="_blank" rel="noopener noreferrer" aria-label="Zalo Vũ Anh Khôi" class="w-9 h-9 rounded-lg bg-[#0068FF] text-white flex items-center justify-center text-xs font-extrabold hover:opacity-90">Zalo</a>
            <a href="https://www.facebook.com/search/top?q=C%C3%B4ng%20ty%20TNHH%20Ki%E1%BA%BFn%20Tr%C3%BAc%20v%C3%A0%20X%C3%A2y%20D%E1%BB%B1ng%20V%C5%A9%20Anh%20Kh%C3%B4i" target="_blank" rel="noopener noreferrer" aria-label="Facebook Vũ Anh Khôi" class="w-9 h-9 rounded-lg bg-[#1877F2] text-white flex items-center justify-center hover:opacity-90"><i class="fa-brands fa-facebook-f"></i></a>
            <a href="tel:0919316101" aria-label="Gọi Hotline" class="w-9 h-9 rounded-lg bg-[#DC2626] text-white flex items-center justify-center hover:opacity-90"><i class="fa-solid fa-phone"></i></a>
          </div>
        </div>

      </div>

      <div class="pt-6 text-center text-xs text-slate-400">
        Copyright © 2026 CÔNG TY TNHH KIẾN TRÚC VÀ XÂY DỰNG VŨ ANH KHÔI – vuanhkhoi.com. All rights reserved.
      </div>
    </div>
  </footer>

  <!-- ======================================================================= -->
  <!-- CỤM NÚT LIÊN HỆ NỔI BẬT (Zalo - Facebook - Hotline)                     -->
  <!-- Tương thích hoàn hảo cho cả Máy tính và Điện thoại, không tràn viền     -->
  <!-- ======================================================================= -->

  <!-- Phiên bản Máy tính (cố định gọn góc dưới bên phải) -->
  <div class="hidden lg:flex flex-col items-end gap-3 fixed bottom-6 right-5 z-50">
    <!-- Zalo -->
    <a
      href="https://zalo.me/0919316101"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2.5 bg-[#0068FF] hover:bg-[#0055D4] text-white pl-4 pr-3 py-2.5 rounded-full shadow-lg transition-all"
    >
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
      <span class="relative w-8 h-8 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">
        Zalo
      </span>
    </a>

    <!-- Facebook -->
    <a
      href="https://www.facebook.com/search/top?q=C%C3%B4ng%20ty%20TNHH%20Ki%E1%BA%BFn%20Tr%C3%BAc%20v%C3%A0%20X%C3%A2y%20D%E1%BB%B1ng%20V%C5%A9%20Anh%20Kh%C3%B4i"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2.5 bg-[#1877F2] hover:bg-[#1465D1] text-white pl-4 pr-3 py-2.5 rounded-full shadow-lg transition-all"
    >
      <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
      <span class="w-8 h-8 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
    </a>

    <!-- Hotline nổi bật có hiệu ứng nhịp sóng -->
    <a
      href="tel:0919316101"
      class="relative contact-pulse flex items-center gap-2.5 bg-[#DC2626] hover:bg-[#B91C1C] text-white pl-4 pr-3 py-2.5 rounded-full shadow-xl transition-all"
    >
      <span class="text-xs font-extrabold whitespace-nowrap">0919 316 101</span>
      <span class="w-8 h-8 rounded-full bg-white text-[#DC2626] flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-sm"></i>
      </span>
    </a>
  </div>

  <!-- Phiên bản Điện thoại & Tablet (Thanh cố định đáy màn hình 3 nút rõ ràng, dễ bấm) -->
  <div class="lg:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_16px_rgba(0,0,0,0.08)] px-2 py-2">
    <div class="grid grid-cols-3 gap-2">
      <a
        href="tel:0919316101"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#DC2626] text-white text-xs font-bold shadow-sm active:scale-95 transition-transform"
      >
        <i class="fa-solid fa-phone-volume"></i>
        <span>Hotline</span>
      </a>
      <a
        href="https://zalo.me/0919316101"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#0068FF] text-white text-xs font-bold shadow-sm active:scale-95 transition-transform"
      >
        <i class="fa-solid fa-comment-dots"></i>
        <span>Zalo</span>
      </a>
      <a
        href="https://www.facebook.com/search/top?q=C%C3%B4ng%20ty%20TNHH%20Ki%E1%BA%BFn%20Tr%C3%BAc%20v%C3%A0%20X%C3%A2y%20D%E1%BB%B1ng%20V%C5%A9%20Anh%20Kh%C3%B4i"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#1877F2] text-white text-xs font-bold shadow-sm active:scale-95 transition-transform"
      >
        <i class="fa-brands fa-facebook-f"></i>
        <span>Facebook</span>
      </a>
    </div>
  </div>

  <!-- ======================================================================= -->
  <!-- MODAL XEM CHI TIẾT CÔNG TRÌNH / SẢN PHẨM / BÀI VIẾT                     -->
  <!-- ======================================================================= -->
  <div id="detail-modal" class="hidden fixed inset-0 z-[60] bg-black/70 backdrop-blur-xs flex items-center justify-center p-3 sm:p-6">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-100 flex items-center justify-between gap-3 z-10">
        <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-[var(--brand-primary)] leading-snug"></h3>
        <button type="button" onclick="closeDetailModal()" aria-label="Đóng hộp thoại" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-6">
        <div class="rounded-xl overflow-hidden bg-slate-100 mb-4">
          <img id="modal-img" src="" alt="" class="w-full max-h-[420px] object-cover" />
        </div>
        <p id="modal-meta" class="text-xs font-semibold text-[var(--brand-accent)] mb-2"></p>
        <p id="modal-desc" class="text-sm text-slate-600 leading-relaxed mb-5"></p>
        <div class="flex flex-wrap items-center gap-2.5 pt-3 border-t border-slate-100">
          <a href="#bao-gia" onclick="closeDetailModal()" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-[var(--brand-accent)] hover:bg-[var(--brand-accent-hover)] text-white text-xs sm:text-sm font-bold transition-colors">
            Nhận báo giá hạng mục này
          </a>
          <a href="tel:0919316101" class="inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-[var(--brand-primary)] text-white text-xs sm:text-sm font-bold hover:opacity-95 transition-opacity">
            <i class="fa-solid fa-phone mr-2"></i>0919 316 101
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ======================================================================= -->
  <!-- JAVASCRIPT XỬ LÝ SLIDER, DỮ LIỆU ẢNH GOOGLE DRIVE, BỘ LỌC & FORM        -->
  <!-- ======================================================================= -->
  <script>
    /**
     * Tạo URL ảnh Google Drive tối ưu tốc độ tải và độ nét
     */
    function driveUrl(id, size) {
      return "https://drive.google.com/thumbnail?id=" + id + "&sz=w" + (size || 1000);
    }

    /**
     * Cơ chế dự phòng nhiều lớp nếu đường dẫn ảnh Google Drive bị gián đoạn
     */
    function handleImgError(img, fileId, label) {
      var step = parseInt(img.getAttribute("data-err-step") || "0", 10);
      if (step === 0) {
        img.setAttribute("data-err-step", "1");
        img.src = "https://lh3.googleusercontent.com/d/" + fileId;
      } else if (step === 1) {
        img.setAttribute("data-err-step", "2");
        img.src = "https://drive.google.com/uc?export=view&id=" + fileId;
      } else {
        img.onerror = null;
        img.src = "https://placehold.co/800x600/0F2B4C/C9962D?text=" + encodeURIComponent(label || "VU ANH KHOI");
      }
    }

    /* =====================================================================
     * 1. DỮ LIỆU DANH MỤC SẢN PHẨM & DỊCH VỤ (Lấy chuẩn từ mẫu tintruongthinh)
     * ===================================================================== */
    const servicesData = [
      {
        title: "Thiết kế Kiến trúc – Nội thất",
        category: "Thiết kế chuyên nghiệp",
        imgId: "1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff",
        desc: "Triển khai hồ sơ thiết kế kiến trúc 3D mặt tiền, bố trí công năng hợp phong thủy, kết cấu chịu lực, điện nước MEP và thiết kế nội thất đồng bộ."
      },
      {
        title: "Thi công phần thô & nhân công hoàn thiện",
        category: "Thi công kết cấu",
        imgId: "13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz",
        desc: "Thi công móng, cột, dầm, sàn, xây tường, tô trát chuẩn kỹ thuật bằng vật tư chính hãng Hòa Phát, Sông Gianh, Cadivi dưới sự giám sát trực tiếp của kỹ sư."
      },
      {
        title: "Thi công hoàn thiện công trình",
        category: "Hoàn thiện thẩm mỹ",
        imgId: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
        desc: "Ốp lát gạch đá, đóng trần thạch cao, sơn bả hoàn thiện, lắp đặt hệ cửa nhôm kính, lan can và thiết bị chiếu sáng – vệ sinh sắc nét từng chi tiết."
      },
      {
        title: "Thi công xây nhà trọn gói",
        category: "Chìa khóa trao tay",
        imgId: "157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT",
        desc: "Giải pháp trọn gói từ xin phép xây dựng, thiết kế, thi công phần thô đến hoàn thiện bàn giao nhà. Cam kết minh bạch đơn giá và không phát sinh."
      },
      {
        title: "Thi công nội thất nhà phố – căn hộ",
        category: "Nội thất đồng bộ",
        imgId: "1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz",
        desc: "Sản xuất và lắp đặt tủ bếp, phòng khách, phòng ngủ, hệ tủ âm tường sử dụng vật liệu gỗ chuẩn chất lượng, tinh gọn và hiện đại."
      },
      {
        title: "Mẫu thiết kế nhà phố hiện đại",
        category: "Bộ sưu tập mẫu nhà",
        imgId: "1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N",
        desc: "Đa dạng mẫu nhà phố 2 tầng, 3 tầng, 4 tầng tối ưu diện tích đất đô thị tại Đà Nẵng với mặt tiền thông thoáng và giếng trời đón sáng."
      },
      {
        title: "Mẫu thiết kế biệt thự – khách sạn",
        category: "Công trình cao cấp",
        imgId: "1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF",
        desc: "Kiến trúc biệt thự vườn, biệt thự 2 mặt tiền, khách sạn và căn hộ cho thuê mang dấu ấn thẩm mỹ riêng, tối ưu hiệu suất khai thác."
      },
      {
        title: "Cải tạo – Sửa chữa nhà trọn gói",
        category: "Nâng cấp không gian",
        imgId: "1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn",
        desc: "Khảo sát hiện trạng kết cấu, lên phương án nâng tầng, cải tạo mặt tiền, xử lý chống thấm và làm mới không gian sống tiết kiệm chi phí."
      }
    ];

    /* =====================================================================
     * 2. DỮ LIỆU 9 ẢNH THI CÔNG XÂY DỰNG THỰC TẾ (Đầy đủ 9 link Google Drive)
     * ===================================================================== */
    const constructionData = [
      {
        id: 1,
        cat: "phan-tho",
        catLabel: "Thi công phần thô",
        title: "Thi công phần thô kết cấu khung bê tông cốt thép",
        imgId: "13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz",
        desc: "Công tác lắp dựng cốt thép, cốp pha chuẩn bản vẽ kết cấu và kiểm tra nghiệm thu chặt chẽ trước khi đổ bê tông."
      },
      {
        id: 2,
        cat: "phan-tho",
        catLabel: "Thi công phần thô",
        title: "Thi công móng và giằng đài công trình dân dụng",
        imgId: "1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR",
        desc: "Triển khai hệ móng kiên cố, chống thấm nền và kiểm soát độ phẳng cốt nền ngay từ giai đoạn đầu."
      },
      {
        id: 3,
        cat: "phan-tho",
        catLabel: "Thi công phần thô",
        title: "Thi công đổ bê tông sàn và bảo dưỡng đúng quy chuẩn",
        imgId: "1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv",
        desc: "Đổ bê tông thương phẩm đúng mác thiết kế, đầm dùi kỹ lưỡng và bảo dưỡng ẩm liên tục giúp sàn đạt cường độ tối ưu."
      },
      {
        id: 4,
        cat: "hoan-thien",
        catLabel: "Thi công hoàn thiện",
        title: "Thi công xây tường bao và tô trát phẳng chuẩn kỹ thuật",
        imgId: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
        desc: "Xây gạch thẳng hàng, đóng lưới chống nứt vị trí tiếp giáp cột tường và tô trát đảm bảo độ phẳng mịn cao."
      },
      {
        id: 5,
        cat: "hoan-thien",
        catLabel: "Thi công hoàn thiện",
        title: "Thi công hệ thống điện nước âm tường MEP đồng bộ",
        imgId: "1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO",
        desc: "Đi ống luồn dây điện, cấp thoát nước khoa học, thử áp lực đường ống kỹ càng trước khi trám trét hoàn thiện."
      },
      {
        id: 6,
        cat: "nha-pho",
        catLabel: "Nhà phố – Biệt thự",
        title: "Thi công mặt tiền nhà phố hiện đại trọn gói",
        imgId: "1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t",
        desc: "Hoàn thiện các chi tiết kiến trúc mặt tiền, chống thấm tường ngoài trời và lắp đặt hệ cửa kính lấy sáng."
      },
      {
        id: 7,
        cat: "nha-pho",
        catLabel: "Nhà phố – Biệt thự",
        title: "Thi công ốp lát và hoàn thiện không gian nội thất",
        imgId: "1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_",
        desc: "Ốp lát gạch nền, cầu thang và khu vệ sinh chuẩn ron đều đẹp, kết hợp xử lý chống thấm đa lớp bền vững."
      },
      {
        id: 8,
        cat: "can-ho",
        catLabel: "Căn hộ – Văn phòng",
        title: "Thi công căn hộ dịch vụ và không gian cho thuê",
        imgId: "1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT",
        desc: "Tổ chức thi công khoa học, đảm bảo tiến độ bàn giao nhanh chóng cho chủ đầu tư sớm vận hành khai thác."
      },
      {
        id: 9,
        cat: "can-ho",
        catLabel: "Căn hộ – Văn phòng",
        title: "Hoàn thiện bàn giao công trình nhà ở tiêu chuẩn kỹ thuật",
        imgId: "1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn",
        desc: "Nghiệm thu tổng thể các hạng mục kiến trúc, điện nước, sơn hoàn thiện và vệ sinh công nghiệp trước khi bàn giao chìa khóa."
      }
    ];

    /* =====================================================================
     * 3. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Đầy đủ 10 link Google Drive)
     * ===================================================================== */
    const daNangProjects = [
      {
        cat: "cam-le",
        area: "Khu đô thị Hòa Xuân, Cẩm Lệ",
        title: "Nhà phố hiện đại 3 tầng Khu đô thị Hòa Xuân",
        imgId: "157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT",
        desc: "Thiết kế và thi công trọn gói nhà phố 3 tầng phong cách hiện đại với mặt tiền thông thoáng tại Hòa Xuân, Cẩm Lệ, Đà Nẵng."
      },
      {
        cat: "cam-le",
        area: "Phường Khuê Trung, Cẩm Lệ",
        title: "Biệt thự phố 2 mặt tiền Quận Cẩm Lệ",
        imgId: "1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff",
        desc: "Công trình biệt thự phố sang trọng, tối ưu hai mặt thoáng cùng hệ lam chắn nắng và ban công cây xanh."
      },
      {
        cat: "hai-chau",
        area: "Quận Hải Châu, Đà Nẵng",
        title: "Căn hộ dịch vụ cao cấp trung tâm Hải Châu",
        imgId: "1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz",
        desc: "Thiết kế thi công trọn gói tòa nhà căn hộ dịch vụ đầy đủ tiện nghi, tối ưu diện tích khai thác tại trung tâm TP Đà Nẵng."
      },
      {
        cat: "son-tra",
        area: "Quận Sơn Trà, Đà Nẵng",
        title: "Khách sạn mini & Căn hộ ven biển Sơn Trà",
        imgId: "1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k",
        desc: "Công trình lưu trú mang kiến trúc đương đại, sử dụng vật liệu chống ăn mòn hơi muối biển bền bỉ theo thời gian."
      },
      {
        cat: "son-tra",
        area: "Khu Nam Việt Á, Ngũ Hành Sơn",
        title: "Nhà phố gia đình Khu Nam Việt Á",
        imgId: "1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N",
        desc: "Thi công trọn gói nhà phố hiện đại với không gian phòng khách – bếp liên thông rộng rãi và giếng trời tự nhiên."
      },
      {
        cat: "hai-chau",
        area: "Quận Thanh Khê, Đà Nẵng",
        title: "Nhà phố kết hợp văn phòng Quận Thanh Khê",
        imgId: "1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML",
        desc: "Giải pháp kiến trúc linh hoạt kết hợp không gian làm việc tầng dưới và không gian sinh hoạt gia đình riêng tư tầng trên."
      },
      {
        cat: "lien-chieu",
        area: "Khu Phước Lý, Liên Chiểu",
        title: "Nhà phố hiện đại Khu đô thị Phước Lý",
        imgId: "1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF",
        desc: "Công trình nhà ở gia đình tại Phước Lý với bố cục hình khối mạnh mẽ, tối ưu chi phí đầu tư và tiến độ thi công."
      },
      {
        cat: "cam-le",
        area: "Nam Hòa Xuân, Đà Nẵng",
        title: "Biệt thự hiện đại Khu sinh thái Nam Hòa Xuân",
        imgId: "1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A",
        desc: "Thiết kế kiến trúc biệt thự kết hợp sân vườn xanh mát, đón gió sông thoáng đãng tại Nam Hòa Xuân."
      },
      {
        cat: "lien-chieu",
        area: "Hòa Vang, Đà Nẵng",
        title: "Nhà vườn mái hiện đại Hòa Vang",
        imgId: "1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80",
        desc: "Không gian sống chan hòa thiên nhiên với khoảng sân rộng, bố trí công năng khoa học cho gia đình đa thế hệ."
      },
      {
        cat: "son-tra",
        area: "Ngũ Hành Sơn, Đà Nẵng",
        title: "Nhà phố 3 tầng hiện đại Ngũ Hành Sơn",
        imgId: "1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4",
        desc: "Thi công phần thô và hoàn thiện nội thất đồng bộ, bàn giao đúng tiến độ cam kết với chủ đầu tư tại Ngũ Hành Sơn."
      }
    ];

    /* =====================================================================
     * 4. DỮ LIỆU BÀI VIẾT TIN TỨC TRANG CHỦ (Tương đồng web mẫu)
     * ===================================================================== */
    const articlesData = [
      {
        date: "Kinh nghiệm xây nhà",
        title: "Hướng dẫn bảo dưỡng bê tông móng đúng cách giúp công trình bền vững",
        imgId: "1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR",
        excerpt: "Bảo dưỡng ẩm bê tông đúng thời điểm sau khi đổ giúp hạn chế tối đa vết nứt bề mặt và đạt cường độ chịu lực chuẩn thiết kế.",
        fullDesc: "Trong thi công xây dựng nhà ở dân dụng, công tác bảo dưỡng bê tông móng và sàn đóng vai trò quyết định đến độ bền kết cấu lâu dài. Sau khi đổ bê tông từ 4 – 6 giờ, cần che phủ bao tải ẩm hoặc tưới nước phun sương nhẹ đều đặn trong suốt 7 ngày đầu tiên, đặc biệt trong điều kiện thời tiết nắng gió tại Đà Nẵng."
      },
      {
        date: "Tư vấn kiến trúc",
        title: "03 nỗi lo lớn nhất khi xây nhà trọn gói và cách phòng tránh hiệu quả",
        imgId: "157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT",
        excerpt: "Phát sinh chi phí, chậm tiến độ và sai lệch vật tư là 3 vấn đề chủ đầu tư cần kiểm soát kỹ ngay từ bước ký hợp đồng.",
        fullDesc: "Để quá trình xây dựng tổ ấm diễn ra suôn sẻ, gia chủ cần chuẩn bị bộ hồ sơ thiết kế kỹ thuật đầy đủ, bảng phân tích chủng loại vật tư rõ ràng (từ thép, xi măng, dây điện đến thiết bị hoàn thiện) và lựa chọn nhà thầu có đội ngũ kỹ sư giám sát minh bạch như Vũ Anh Khôi."
      },
      {
        date: "Không gian nội thất",
        title: "Tâm lý học không gian: Nội thất tác động đến chất lượng sống như thế nào?",
        imgId: "1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz",
        excerpt: "Ánh sáng tự nhiên, tỷ lệ không gian và bảng màu vật liệu ảnh hưởng trực tiếp tới cảm xúc thư giãn của các thành viên.",
        fullDesc: "Một ngôi nhà đẹp không chỉ nằm ở mặt tiền ấn tượng mà còn ở cảm giác dễ chịu mỗi khi trở về. Việc bố trí giếng trời, thông gió chéo, kết hợp gam màu trung tính ấm áp và vật liệu gần gũi giúp giảm căng thẳng và gắn kết gia đình."
      },
      {
        date: "Pháp lý & Dự toán",
        title: "Kinh nghiệm lập dự toán và xin giấy phép xây dựng tại Đà Nẵng",
        imgId: "1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N",
        excerpt: "Nắm rõ mật độ xây dựng, khoảng lùi, số tầng cho phép và cách tính diện tích sàn giúp chủ đầu tư chủ động ngân sách.",
        fullDesc: "Trước khi khởi công, chủ đầu tư cần kiểm tra quy hoạch lộ giới, mật độ xây dựng theo quy định từng khu vực tại Đà Nẵng. Vũ Anh Khôi hỗ trợ trọn gói tư vấn quy hoạch, lập hồ sơ xin phép xây dựng và lên bảng dự toán chi tiết từng hạng mục hoàn toàn miễn phí."
      }
    ];

    /* =====================================================================
     * RENDER CÁC KHỐI SẢN PHẨM, CÔNG TRÌNH THỰC TẾ, DỰ ÁN ĐÀ NẴNG, BÀI VIẾT
     * Không gắn nhãn dán đè lên ảnh; tên sản phẩm hiển thị đầy đủ trên mobile
     * ===================================================================== */
    function renderServices() {
      const container = document.getElementById("services-grid");
      container.innerHTML = servicesData.map(function (item, idx) {
        return (
          '<article onclick="openDetailModal(\'service\',' + idx + ')" class="cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-[var(--brand-accent)] transition-all flex flex-col fl-img-zoom">' +
            '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
              '<img src="' + driveUrl(item.imgId, 700) + '" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover" onerror="handleImgError(this, \'' + item.imgId + '\', \'DICH VU\')" />' +
            '</div>' +
            '<div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">' +
              '<h3 class="text-[12px] sm:text-[13.5px] md:text-[14px] font-bold text-[var(--brand-primary)] leading-snug break-words">' +
                item.title +
              '</h3>' +
              '<p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed hidden sm:block">' +
                item.category +
              '</p>' +
            '</div>' +
          '</article>'
        );
      }).join("");
    }

    function renderConstruction(filterCat) {
      const container = document.getElementById("construction-grid");
      const list = filterCat === "all"
        ? constructionData
        : constructionData.filter(function (c) { return c.cat === filterCat; });

      container.innerHTML = list.map(function (item) {
        const realIdx = constructionData.indexOf(item);
        return (
          '<article onclick="openDetailModal(\'construction\',' + realIdx + ')" class="cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-[var(--brand-accent)] transition-all flex flex-col fl-img-zoom">' +
            '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
              '<img src="' + driveUrl(item.imgId, 800) + '" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover" onerror="handleImgError(this, \'' + item.imgId + '\', \'THI CONG\')" />' +
            '</div>' +
            '<div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">' +
              '<h3 class="text-[12px] sm:text-[13.5px] md:text-[14px] font-bold text-[var(--brand-primary)] leading-snug break-words">' +
                item.title +
              '</h3>' +
              '<p class="text-[11px] text-[var(--brand-accent)] font-semibold mt-1.5">' +
                item.catLabel +
              '</p>' +
            '</div>' +
          '</article>'
        );
      }).join("");
    }

    function filterConstruction(cat) {
      renderConstruction(cat);
      document.querySelectorAll(".construction-tab").forEach(function (btn) {
        if (btn.getAttribute("data-cat") === cat) {
          btn.className = "construction-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-[var(--brand-primary)] text-white";
        } else {
          btn.className = "construction-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-white text-slate-700 border border-slate-200 hover:border-[var(--brand-accent)]";
        }
      });
    }

    function renderDaNang(filterCat) {
      const container = document.getElementById("danang-grid");
      const list = filterCat === "all"
        ? daNangProjects
        : daNangProjects.filter(function (p) { return p.cat === filterCat; });

      container.innerHTML = list.map(function (item) {
        const realIdx = daNangProjects.indexOf(item);
        return (
          '<article onclick="openDetailModal(\'danang\',' + realIdx + ')" class="cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-[var(--brand-accent)] transition-all flex flex-col fl-img-zoom">' +
            '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
              '<img src="' + driveUrl(item.imgId, 800) + '" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover" onerror="handleImgError(this, \'' + item.imgId + '\', \'DU AN DA NANG\')" />' +
            '</div>' +
            '<div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">' +
              '<h3 class="text-[12px] sm:text-[13px] font-bold text-[var(--brand-primary)] leading-snug break-words">' +
                item.title +
              '</h3>' +
              '<p class="text-[11px] text-slate-500 mt-1.5 leading-snug break-words">' +
                '<i class="fa-solid fa-location-dot text-[var(--brand-accent)] mr-1"></i>' + item.area +
              '</p>' +
            '</div>' +
          '</article>'
        );
      }).join("");
    }

    function filterDaNang(cat) {
      renderDaNang(cat);
      document.querySelectorAll(".danang-tab").forEach(function (btn) {
        if (btn.getAttribute("data-cat") === cat) {
          btn.className = "danang-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-[var(--brand-primary)] text-white";
        } else {
          btn.className = "danang-tab whitespace-nowrap px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-bold transition-colors bg-slate-100 text-slate-700 hover:bg-slate-200";
        }
      });
    }

    function renderArticles() {
      const container = document.getElementById("articles-grid");
      container.innerHTML = articlesData.map(function (item, idx) {
        return (
          '<article onclick="openDetailModal(\'article\',' + idx + ')" class="cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-[var(--brand-accent)] transition-all flex flex-col fl-img-zoom">' +
            '<div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">' +
              '<img src="' + driveUrl(item.imgId, 700) + '" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover" onerror="handleImgError(this, \'' + item.imgId + '\', \'TIN TUC\')" />' +
            '</div>' +
            '<div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">' +
              '<div>' +
                '<p class="text-[10.5px] sm:text-[11px] font-semibold text-[var(--brand-accent)] mb-1">' + item.date + '</p>' +
                '<h3 class="text-[12px] sm:text-[13.5px] font-bold text-[var(--brand-primary)] leading-snug break-words">' +
                  item.title +
                '</h3>' +
              '</div>' +
              '<p class="text-[11px] sm:text-xs text-slate-500 mt-2 leading-relaxed hidden sm:block">' +
                item.excerpt +
              '</p>' +
            '</div>' +
          '</article>'
        );
      }).join("");
    }

    /* =====================================================================
     * ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
     * ===================================================================== */
    let currentBanner = 0;
    const totalBanners = 2;
    let bannerTimer = null;

    function updateBannerUI() {
      const track = document.getElementById("banner-track");
      track.style.transform = "translateX(-" + (currentBanner * 100) + "%)";
      for (let i = 0; i < totalBanners; i++) {
        const dot = document.getElementById("dot-" + i);
        if (dot) {
          dot.className = i === currentBanner
            ? "w-7 h-2 rounded-full bg-[var(--brand-accent)] transition-all"
            : "w-2.5 h-2 rounded-full bg-white/50 hover:bg-white/80 transition-all";
        }
      }
    }

    function nextBanner() {
      currentBanner = (currentBanner + 1) % totalBanners;
      updateBannerUI();
      resetBannerTimer();
    }

    function prevBanner() {
      currentBanner = (currentBanner - 1 + totalBanners) % totalBanners;
      updateBannerUI();
      resetBannerTimer();
    }

    function goToBanner(idx) {
      currentBanner = idx;
      updateBannerUI();
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(function () {
        currentBanner = (currentBanner + 1) % totalBanners;
        updateBannerUI();
      }, 5500);
    }

    /* =====================================================================
     * MODAL XEM CHI TIẾT & XỬ LÝ FORM YÊU CẦU BÁO GIÁ
     * ===================================================================== */
    function openDetailModal(type, idx) {
      let item = null;
      let meta = "";
      let desc = "";
      if (type === "service") {
        item = servicesData[idx];
        meta = item.category;
        desc = item.desc;
      } else if (type === "construction") {
        item = constructionData[idx];
        meta = "Hạng mục: " + item.catLabel + " • Vũ Anh Khôi";
        desc = item.desc;
      } else if (type === "danang") {
        item = daNangProjects[idx];
        meta = "Địa điểm: " + item.area;
        desc = item.desc;
      } else if (type === "article") {
        item = articlesData[idx];
        meta = "Chuyên mục: " + item.date;
        desc = item.fullDesc;
      }
      if (!item) return;

      document.getElementById("modal-title").textContent = item.title;
      document.getElementById("modal-meta").textContent = meta;
      document.getElementById("modal-desc").textContent = desc;
      const modalImg = document.getElementById("modal-img");
      modalImg.removeAttribute("data-err-step");
      modalImg.src = driveUrl(item.imgId, 1200);
      modalImg.alt = item.title;
      modalImg.onerror = function () { handleImgError(modalImg, item.imgId, item.title); };

      document.getElementById("detail-modal").classList.remove("hidden");
      document.body.style.overflow = "hidden";
    }

    function closeDetailModal() {
      document.getElementById("detail-modal").classList.add("hidden");
      document.body.style.overflow = "";
    }

    /* Khởi tạo khi trang tải xong */
    document.addEventListener("DOMContentLoaded", function () {
      renderServices();
      renderConstruction("all");
      renderDaNang("all");
      renderArticles();
      resetBannerTimer();

      // Hỗ trợ vuốt ngang trên điện thoại cho 2 banner
      const slider = document.getElementById("hero-slider");
      let touchStartX = 0;
      slider.addEventListener("touchstart", function (e) {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      slider.addEventListener("touchend", function (e) {
        const diff = touchStartX - e.changedTouches[0].screenX;
        if (Math.abs(diff) > 40) {
          if (diff > 0) nextBanner();
          else prevBanner();
        }
      }, { passive: true });

      // Tạm dừng trượt khi rê chuột vào banner trên máy tính
      slider.addEventListener("mouseenter", function () {
        if (bannerTimer) clearInterval(bannerTimer);
      });
      slider.addEventListener("mouseleave", resetBannerTimer);

      // Menu mobile
      const mobileBtn = document.getElementById("mobile-menu-btn");
      const mobileMenu = document.getElementById("mobile-menu");
      mobileBtn.addEventListener("click", function () {
        mobileMenu.classList.toggle("hidden");
      });
      document.querySelectorAll(".mobile-nav-link").forEach(function (link) {
        link.addEventListener("click", function () {
          mobileMenu.classList.add("hidden");
        });
      });

      // Đóng modal khi bấm nền tối hoặc phím ESC
      const modal = document.getElementById("detail-modal");
      modal.addEventListener("click", function (e) {
        if (e.target === modal) closeDetailModal();
      });
      document.addEventListener("keydown", function (e) {
        if (e.key === "Escape") closeDetailModal();
      });

      // Xử lý form yêu cầu & báo giá (dùng thông báo inline, không dùng alert)
      const quoteForm = document.getElementById("quote-form");
      const feedback = document.getElementById("quote-feedback");
      quoteForm.addEventListener("submit", function (e) {
        e.preventDefault();
        const name = document.getElementById("q-name").value.trim();
        const phone = document.getElementById("q-phone").value.trim();
        const type = document.getElementById("q-type").value;
        feedback.textContent = "Cảm ơn anh/chị " + name + "! Yêu cầu tư vấn & báo giá hạng mục \"" + type + "\" (SĐT: " + phone + ") đã được ghi nhận. Kỹ sư Vũ Anh Khôi sẽ liên hệ sớm nhất qua Hotline 0919 316 101.";
        feedback.classList.remove("hidden");
        quoteForm.reset();
      });
    });
  </script>
</body>
</html>
