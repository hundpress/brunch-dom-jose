let currentLang = "pt";
const CONTENT = {
    pt: {
        nav: { about: "O Nosso Espaço", services: "Menu", contacts: "Reservas", cta: "Ligar" },
        hero: { tag: "Caldelas • Brunch & Coffee", static: "O seu melhor", titles: ["Brunch.", "Momento.", "Sabor."], sub: "Desfrute de uma experiência única com pratos preparados para satisfazer o seu paladar num ambiente acolhedor.", btnMenu: "Ver Menu", btnBook: "Reservar Mesa" },
        services: { over: "O Nosso Menu", title: "Sugestões Dom José", items: [
            { t: "Ovo Red Velvet", d: "Chocolate de leite, frosting de queijo creme e bolo veludo.", img: "./images/a.jpg" },
            { t: "Ovo Ferrero Rocher", d: "Chocolate de leite, creme de avelã, avelãs tostadas e bombom.", img: "./images/b.jpg" },
            { t: "Ovo Kinder White", d: "Ganache de chocolate branco, creme de avelã e Kinder Bueno.", img: "./images/c.jpg" },
            { t: "Ovo KitKat Brownie", d: "Brownie, creme de baunilha, mousse de chocolate, KitKat e estrelas.", img: "./images/d.jpg" },
            { t: "Panquecas Lotus Biscoff", d: "Panquecas, creme Biscoff, bolacha Lotus, banana e gelado de baunilha.", img: "./images/e.jpg" },
            { t: "Bowl de Pitaia", d: "Pitaia, granola, kiwi, banana, morangos e sementes de abóbora.", img: "./images/f.jpg" },
            { t: "Panquecas com Picolé", d: "Panquecas, chocolate, picolé, morango, banana, chantilly e avelãs.", img: "./images/g.jpg" },
            { t: "Milkshake de Chocolate", d: "Leite, chocolate, chantilly, cacau em pó e um wafer.", img: "./images/h.jpg" },
            { t: "Cookies de Kinder", d: "Massa de chocolate, creme de avelã, chocolate derretido e Kinder.", img: "./images/i.jpg" },
            { t: "Cookies de M&M", d: "Massa de cookie, gotas de chocolate, cobertura de chocolate e M&Ms.", img: "./images/j.jpg" },
            { t: "Bagel de Bacon", d: "Bagel de gergelim, bacon, ovos mexidos, abacate e molho especial.", img: "./images/k.jpg" }
        ]},
        about: { over: "Sobre o Dom José", intro: "Uma tradição de sabor e hospitalidade em Caldelas.", desc: ["Fundado com a paixão pela gastronomia de qualidade, o Brunch Dom José é mais do que um restaurante; é um ponto de encontro onde o design moderno se funde com os sabores tradicionais.", "Utilizamos apenas ingredientes locais e frescos, garantindo que cada prato que sai da nossa cozinha conte uma história de dedicação. Venha conhecer o nosso espaço e deixe-se surpreender."] },
        contacts: { title: "Faça a sua Reserva", sub: "Estamos na R. António de Barros 68, Caldelas. Esperamos por si para uma refeição inesquecível.", hoursTitle: "Horário", btnPhone: "Ligar Agora", btnMap: "Ver Mapa", socialCta: "Siga-nos para acompanhar todas as novidades e momentos diários.", hours: [{d:"Seg-Sáb", t:"07-20:30h"},{d:"Dom", t:"07:30-19:30h"}] },
        footer: "© 2026 BRUNCH DOM JOSÉ. CALDELAS."
    },
    en: {
        nav: { about: "Our Space", services: "Menu", contacts: "Bookings", cta: "Call" },
        hero: { tag: "Caldelas • Brunch & Coffee", static: "Your best", titles: ["Brunch.", "Moment.", "Flavor."], sub: "Enjoy a unique experience with dishes prepared to satisfy your palate in a cozy and welcoming environment.", btnMenu: "View Menu", btnBook: "Book a Table" },
        services: { over: "Our Menu", title: "Dom José Suggestions", items: [
            { t: "Red Velvet Egg", d: "Milk chocolate, cream cheese frosting, and red velvet cake crumbs.", img: "./images/a.jpg" },
            { t: "Ferrero Rocher Egg", d: "Milk chocolate, hazelnut cream, toasted hazelnuts, and Ferrero Rocher.", img: "./images/b.jpg" },
            { t: "Kinder White Egg", d: "White chocolate ganache, hazelnut cream, and Kinder Bueno.", img: "./images/c.jpg" },
            { t: "KitKat Brownie Egg", d: "Brownie, vanilla cream, chocolate mousse, KitKat, and stars.", img: "./images/d.jpg" },
            { t: "Lotus Biscoff Pancakes", d: "Pancakes, Biscoff cream, Lotus biscuits, banana, and vanilla ice cream.", img: "./images/e.jpg" },
            { t: "Pitaia Bowl", d: "Pitaia, granola, kiwi, banana, strawberries, and pumpkin seeds.", img: "./images/f.jpg" },
            { t: "Pancakes with Popsicle", d: "Pancakes, chocolate, popsicle, strawberries, banana, whipped cream, and hazelnuts.", img: "./images/g.jpg" },
            { t: "Chocolate Milkshake", d: "Milk, chocolate, whipped cream, cocoa powder, and a wafer.", img: "./images/h.jpg" },
            { t: "Kinder Cookies", d: "Chocolate dough, hazelnut cream, melted chocolate, and Kinder.", img: "./images/i.jpg" },
            { t: "M&M Cookies", d: "Cookie dough, chocolate chips, chocolate coating, and M&Ms.", img: "./images/j.jpg" },
            { t: "Brunch Bagel", d: "Toasted bagel, poached egg, cheddar cheese, deli meat, and arugula.", img: "./images/k.jpg" }
        ]},
        about: { over: "About Dom José", intro: "A tradition of flavor and hospitality in Caldelas.", desc: ["Founded with a passion for quality gastronomy, Brunch Dom José is more than just a restaurant; it's a meeting point where modern design merges with traditional flavors.", "We use only fresh local ingredients, ensuring that every dish leaving our kitchen tells a story of dedication. Come visit our space and let us surprise you."] },
        contacts: { title: "Make a Reservation", sub: "We are at R. António de Barros 68, Caldelas. We look forward to seeing you for an unforgettable meal.", hoursTitle: "Opening Hours", btnPhone: "Call Now", btnMap: "View Map", socialCta: "Follow us to keep up with all the news and daily moments.", hours: [{d:"Mon-Sat", t:"07am-8:30pm"},{d:"Sun", t:"07:30am-07:30pm"}] },
        footer: "© 2026 BRUNCH DOM JOSÉ. CALDELAS."
    }
};

function updateLanguage(code) {
    currentLang = code;
    const d = CONTENT[code];
    
    document.getElementById('lang-menu').classList.add('hidden');

    const navLinks = `
        <li><a href="#about" class="nav-link" onclick="closeMobileMenu()">${d.nav.about}</a></li>
        <li><a href="#services" class="nav-link" onclick="closeMobileMenu()">${d.nav.services}</a></li>
        <li><a href="#contacts" class="nav-link" onclick="closeMobileMenu()">${d.nav.contacts}</a></li>
    `;
    document.getElementById('nav-list').innerHTML = navLinks;
    
    document.getElementById('cta-nav-text').textContent = d.nav.cta;
    document.getElementById('active-lang').textContent = code.toUpperCase();
    document.getElementById('active-flag').textContent = code === 'pt' ? '🇵🇹' : '🇬🇧';
    
    document.getElementById('hero-tag').textContent = d.hero.tag;
    document.getElementById('hero-static').textContent = d.hero.static;
    document.getElementById('hero-sub').textContent = d.hero.sub;
    document.getElementById('hero-cta-text').textContent = d.hero.btnBook;
    document.getElementById('hero-menu-text').textContent = d.hero.btnMenu;

    const track = document.getElementById('gallery-track');
    const itemsHtml = d.services.items.map(i => `<div class="menu-item"><img src="${i.img}"><h4>${i.t}</h4><p>${i.d}</p></div>`).join('');
    track.innerHTML = itemsHtml + itemsHtml + itemsHtml;

    document.getElementById('about-mini').textContent = d.about.over;
    document.getElementById('about-intro').textContent = d.about.intro;
    document.getElementById('about-desc').innerHTML = d.about.desc.map(p => `<p>${p}</p>`).join('');

    document.getElementById('contact-title').textContent = d.contacts.title;
    document.getElementById('contact-sub').textContent = d.contacts.sub;
    document.getElementById('hours-title').textContent = d.contacts.hoursTitle;
    document.getElementById('hours-box').innerHTML = d.contacts.hours.map(h => `<div class="flex justify-between py-3 border-b border-orange-50"><span class="f-xs font-bold uppercase opacity-50">${h.d}</span><span class="f-sm font-black">${h.t}</span></div>`).join('');
    
    document.getElementById('social-cta').textContent = d.contacts.socialCta;

    document.getElementById('contact-pills').innerHTML = `
        <a href="tel:253471226" class="px-8 py-4 bg-[var(--primary)] text-white rounded-full font-bold f-xs uppercase flex items-center justify-center gap-2 text-center w-full sm:w-auto">
          <i data-lucide="phone" class="w-4 h-4"></i> ${d.contacts.btnPhone}
        </a>
        <a href="https://maps.app.goo.gl/PYqBNZkXFCboJncV7" target="_blank" class="px-8 py-4 bg-white border border-orange-100 rounded-full font-bold f-xs uppercase flex items-center justify-center gap-2 text-center w-full sm:w-auto">
          <i data-lucide="map-pin" class="w-4 h-4"></i> ${d.contacts.btnMap}
        </a>
    `;

    document.getElementById('footer-copy').textContent = d.footer;
    initRotator();
    lucide.createIcons();
}

function closeMobileMenu() {
    document.getElementById('nav-list').classList.remove('mobile-active');
}

function initRotator() {
    const titles = CONTENT[currentLang].hero.titles;
    const container = document.getElementById('title-rotator');
    container.innerHTML = titles.map(t => `<span class="title-item">${t}</span>`).join('');
    const items = container.querySelectorAll('.title-item');
    let idx = 0; gsap.set(items[0], { opacity: 1, y: 0 });
    if(window.rotatorTimer) clearInterval(window.rotatorTimer);
    window.rotatorTimer = setInterval(() => {
        gsap.to(items[idx], { y: "-100%", opacity: 0, duration: 0.6 });
        idx = (idx + 1) % items.length;
        gsap.fromTo(items[idx], { y: "100%", opacity: 0 }, { y: "0%", opacity: 1, duration: 0.6 });
    }, 3000);
}

function initMenuScroll() {
    const track = document.getElementById('gallery-track');
    const slider = document.getElementById('menu-gallery');
    let scrollPos = 0, isPaused = false, isDragging = false, startX, scrollLeftAtStart;
    
    function step() { 
        if(!isPaused && !isDragging) { 
            scrollPos += 0.8; 
            const halfWidth = track.scrollWidth / 3; 
            if(scrollPos >= halfWidth * 2) scrollPos = halfWidth; 
            track.style.transform = `translate3d(-${scrollPos}px, 0, 0)`; 
        } 
        requestAnimationFrame(step); 
    }

    // Mouse Events
    slider.addEventListener('mousedown', (e) => { 
        isDragging = true; isPaused = true; 
        startX = e.pageX - slider.offsetLeft; 
        scrollLeftAtStart = scrollPos; 
        slider.style.cursor = 'grabbing'; 
    });

    // Touch Events for Mobile
    slider.addEventListener('touchstart', (e) => {
        isDragging = true; isPaused = true;
        startX = e.touches[0].pageX - slider.offsetLeft;
        scrollLeftAtStart = scrollPos;
    });

    window.addEventListener('mousemove', (e) => handleMove(e.pageX));
    window.addEventListener('touchmove', (e) => handleMove(e.touches[0].pageX));

    function handleMove(currentX) {
        if (!isDragging) return;
        const x = currentX - slider.offsetLeft;
        const walk = (x - startX) * 1.5;
        scrollPos = scrollLeftAtStart - walk;
        const halfWidth = track.scrollWidth / 3;
        if(scrollPos < halfWidth) scrollPos += halfWidth;
        if(scrollPos > halfWidth * 2) scrollPos -= halfWidth;
        track.style.transform = `translate3d(-${scrollPos}px, 0, 0)`;
    }

    const endDrag = () => { isDragging = false; isPaused = false; slider.style.cursor = 'grab'; };
    window.addEventListener('mouseup', endDrag);
    window.addEventListener('touchend', endDrag);

    requestAnimationFrame(step);
}

window.onload = () => {
    // Scroll Indicator logic
    window.addEventListener('scroll', () => {
        const indicator = document.getElementById('scroll-indicator');
        if (window.scrollY > 50) {
            indicator.classList.add('opacity-0');
        } else {
            indicator.classList.remove('opacity-0');
        }
    });

    // Mobile Menu Toggle
    document.getElementById('mobile-menu-btn').onclick = (e) => {
        e.stopPropagation();
        document.getElementById('nav-list').classList.toggle('mobile-active');
    };

    document.getElementById('lang-menu').innerHTML = `<button onclick="updateLanguage('pt')" class="block w-full px-4 py-3 text-left hover:bg-orange-50 f-xs font-bold border-b border-orange-50">PT (Português)</button><button onclick="updateLanguage('en')" class="block w-full px-4 py-3 text-left hover:bg-orange-50 f-xs font-bold">EN (English)</button>`;
    document.getElementById('lang-btn').onclick = (e) => { e.stopPropagation(); document.getElementById('lang-menu').classList.toggle('hidden'); };
    
    window.onclick = () => {
        document.getElementById('lang-menu').classList.add('hidden');
        document.getElementById('nav-list').classList.remove('mobile-active');
    };
    
    updateLanguage('pt');
    initMenuScroll();
    gsap.to("#nav", { opacity: 1, y: 0, duration: 1 });
    ScrollTrigger.batch(".reveal", { onEnter: b => gsap.to(b, { opacity: 1, y: 0, duration: 0.8, stagger: 0.1 }) });
};
