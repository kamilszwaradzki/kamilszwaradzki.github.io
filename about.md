# About
<style>
    
        #profile .card {
            margin: 0 4em 0 4em !important;
        }
        a.d-flex span[data-target="home"] {
            border: 2px solid black;
            height: fit-content;
            width: fit-content;
            margin-right: 1em;
        }

        a.d-flex span[data-target="home"]::before {
            font: 800 37px Arial;
            content: '<CODE';
            color: white;
            /*color: #0AF;*/
            background: black;
            /*background: black;*/
        }

        a.d-flex span[data-target="home"]::after {
            font: 800 37px Arial;
            content: '4ALL>';
            color: black;
            background: white;
            /*background: #0AF;*/
        }

        a.d-flex span[data-target="home"]:hover {
            filter: invert(1);
        }

        /* The side navigation menu */
        .sidebar {
            margin: 0;
            padding: 0;
            width: 200px;
            background-color: #f1f1f1;
            position: fixed;
            height: 100%;
            overflow: auto;
        }

        /* Sidebar links */
        .sidebar a {
            display: block;
            color: black;
            padding: 16px;
            text-decoration: none;
        }

        /* Active/current link */
        .sidebar a.active {
            background-color: #04AA6D;
            color: white;
        }

        /* Links on mouse-over */
        .sidebar a:hover:not(.active) {
            background-color: #555;
            color: white;
        }

        /* Page content. The value of the margin-left property should match the value of the sidebar's width property */
        div.content {
            margin-left: 200px;
            padding: 1px 16px;
            height: 1000px;
        }

        /* On screens that are less than 700px wide, make the sidebar into a topbar */
        @media screen and (max-width: 700px) {
            .sidebar {
                width: 100%;
                height: auto;
                position: relative;
            }

            .sidebar a {float: left;}
            div.content {margin-left: 0;}
        }

        /* On screens that are less than 400px, display the bar vertically, instead of horizontally */
        @media screen and (max-width: 400px) {
            .sidebar a {
                text-align: center;
                float: none;
            }
        }

    
</style>
<div class="container-fluid">
    <div class="row flex-nowrap">
    <div class="col">
                <div class="row">
                    <div class="col-auto m-auto m-lg-0">
                        <div id="navigation">
                            <div class="card mt-4">
                                <div class="card-header">
                                    Table Of Contents
                                </div>
                                <div class="card-body">
                                    <ul class="list-group">
                                        <li class="list-group-item"><a id="profile-link" href="#profile">Profil zawodowy</a></li>
                                        <li class="list-group-item"><a id="skills-link" href="#skills">Umiejętności</a></li>
                                        <li class="list-group-item"><a id="experience-link" href="#experience">Doświadczenie</a></li>
                                        <li class="list-group-item"><a id="education-link" href="#education">Edukacja</a></li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <section id="profile" class="my-5">
                            <h2>Profil zawodowy</h2>
                            <div class="card">
                                <div class="card-body">
                                    <p class="text-wrap fs-4">
                                        Jestem programistą PHP z około 3 letnią praktyką w IT, 1 rok i 3 miesiące w PHP, w tym 7
                                        miesięcy w CodeIgniterze,
                                        6 miesięcy w Symfony, 5 miesięcy w Laravel.
                                        Wyspecjalizowałem się w stosowaniu narzędzi PHP, dlatego na stanowisku PHP Developer czuje się
                                        najlepiej.
                                    </p>
                                </div>
                            </div>
                        </section>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <section id="skills">
                            <h2>Umiejętności</h2>
                            <ul class="list-group" id="skills-list">
                                <li class="list-group-item">Znajomość PHP w wersji 7.x+</li>
                                <li class="list-group-item">Znajomość JS/CSS/HTML</li>
                                <li class="list-group-item">Znajomość Vue.js, Backbone.js, Grunt</li>
                                <li class="list-group-item">Znajomość Apache/Nginx, Linux</li>
                                <li class="list-group-item">Angielski poziom B2</li>
                            </ul>
                        </section>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <section id="experience" class="my-5">
                            <h2 id="header-experience">Doświadczenie</h2>
                            <div class="accordion" id="accordionExample">
                                                            <div class="accordion-item">
                                    <h2 class="accordion-header">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapsePHP" aria-expanded="false" aria-controls="collapsePHP">
                                        PHP
                                        <div class="rating">
                                        <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="half-color">★</span>
                    <span>★</span>
                                        </div>
                                    </button>
                                    </h2>
                                    <div id="collapsePHP" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                                        <div class="accordion-body cards">
                                            <div class="card" style="background: #CCCCFC;">
                                                <h2>PHP</h2>
                                                <div class="rating">
                                                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="half-color">★</span>
                    <span>★</span>
                                                </div>
                                                <p>
                                                    <label id="lbl-progress-php" for="exp_subtotal_1">Rok i Trzy miesiące</label>
                          <progress id="exp_subtotal_1" value="41" max="100">41%</progress>
                                                </p>
                                            </div>
                                            <div class="card" style="background: #d3d3ff;">
                                                <h2 class='header-worked-on'>Pracowałem nad:</h2>
                                                <ul id='list-worked-on-php'>
                                                                                                            <li>Rozwijanie oprogramowania CRM vtenext,</li>
                                                                                                            <li>Dodawanie zmian na życzenie klientów w zakresie spersonalizowanego oprogramowania CRM vtenext,</li>
                                                                                                            <li>Dostarczanie poprawek do istniejących rozwiązań w środowisku klienta w oparciu o CRM vtenext,</li>
                                                                                                    </ul>
                                                <h2 class='header-used-techs'>Używane technologie:</h2>
                                                <b>PHP 7.x, jQuery, MySQL, SVN, Smarty, JS/CSS/HTML</b>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                                            <div class="accordion-item">
                                    <h2 class="accordion-header">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseCodeIgniter" aria-expanded="false" aria-controls="collapseCodeIgniter">
                                        CodeIgniter
                                        <div class="rating">
                                        <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="half-color">★</span>
                    <span>★</span>
                    <span>★</span>
                                        </div>
                                    </button>
                                    </h2>
                                    <div id="collapseCodeIgniter" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                                        <div class="accordion-body cards">
                                            <div class="card" style="background: #CCCCFC;">
                                                <h2>CodeIgniter</h2>
                                                <div class="rating">
                                                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="half-color">★</span>
                    <span>★</span>
                    <span>★</span>
                                                </div>
                                                <p>
                                                    <label id="lbl-progress-codeigniter" for="exp_subtotal_2">Siedem miesięcy</label>
                          <progress id="exp_subtotal_2" value="19" max="100">19%</progress>
                                                </p>
                                            </div>
                                            <div class="card" style="background: #d3d3ff;">
                                                <h2 class='header-worked-on'>Pracowałem nad:</h2>
                                                <ul id='list-worked-on-codeigniter'>
                                                                                                            <li>Aplikacja o wielu zastosowaniach dla ubezpieczalni w Wielkiej Brytanii m.in. porównywarka ubezpieczeń oraz kalkulator podatków za sprowadzenie auta z Irlandii na podstawie numeru rejstracyjnego, kosztorys napraw</li>
                                                                                                    </ul>
                                                <h2 class='header-used-techs'>Używane technologie:</h2>
                                                <b>CodeIgniter 3.x, jQuery, MySQL, Git, Vue.js, JS/CSS/HTML, webpack, Twig</b>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                                            <div class="accordion-item">
                                    <h2 class="accordion-header">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSymfony" aria-expanded="false" aria-controls="collapseSymfony">
                                        Symfony
                                        <div class="rating">
                                        <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="half-color">★</span>
                    <span>★</span>
                    <span>★</span>
                                        </div>
                                    </button>
                                    </h2>
                                    <div id="collapseSymfony" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                                        <div class="accordion-body cards">
                                            <div class="card" style="background: #CCCCFC;">
                                                <h2>Symfony</h2>
                                                <div class="rating">
                                                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="half-color">★</span>
                    <span>★</span>
                    <span>★</span>
                                                </div>
                                                <p>
                                                    <label id="lbl-progress-symfony" for="exp_subtotal_3">Sześć miesięcy</label>
                          <progress id="exp_subtotal_3" value="18" max="100">18%</progress>
                                                </p>
                                            </div>
                                            <div class="card" style="background: #d3d3ff;">
                                                <h2 class='header-worked-on'>Pracowałem nad:</h2>
                                                <ul id='list-worked-on-symfony'>
                                                                                                            <li>Projekt do wysyłania i interpretowania zapytań w JSON/XML</li>
                                                                                                            <li>Sklep B2B,</li>
                                                                                                            <li>Generator faktur,</li>
                                                                                                    </ul>
                                                <h2 class='header-used-techs'>Używane technologie:</h2>
                                                <b>MySQL, Symfony, Backbone.js, React.js, PostgreSQL, Docker, Twig, jQuery, Git, Grunt, JS/CSS/HTML, PHP 7.x,PHP 5.6</b>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                                            <div class="accordion-item">
                                    <h2 class="accordion-header">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseLaravel" aria-expanded="false" aria-controls="collapseLaravel">
                                        Laravel
                                        <div class="rating">
                                        <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span>★</span>
                    <span>★</span>
                                        </div>
                                    </button>
                                    </h2>
                                    <div id="collapseLaravel" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                                        <div class="accordion-body cards">
                                            <div class="card" style="background: #CCCCFC;">
                                                <h2>Laravel</h2>
                                                <div class="rating">
                                                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span>★</span>
                    <span>★</span>
                                                </div>
                                                <p>
                                                    <label id="lbl-progress-laravel" for="exp_subtotal_4">Pięć miesięcy</label>
                          <progress id="exp_subtotal_4" value="17" max="100">17%</progress>
                                                </p>
                                            </div>
                                            <div class="card" style="background: #d3d3ff;">
                                                <h2 class='header-worked-on'>Pracowałem nad:</h2>
                                                <ul id='list-worked-on-laravel'>
                                                                                                            <li>Projekt do obsługi SEO i kampanii SEO</li>
                                                                                                            <li>Projekt do analizy danych z Google Search Console</li>
                                                                                                    </ul>
                                                <h2 class='header-used-techs'>Używane technologie:</h2>
                                                <b>jQuery, Laravel, MySQL, Laravel LiveWire, Git, JS/CSS/HTML, AlpineJS</b>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                                            <div class="accordion-item">
                                    <h2 class="accordion-header">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapsePython" aria-expanded="false" aria-controls="collapsePython">
                                        Python
                                        <div class="rating">
                                        <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span>★</span>
                    <span>★</span>
                    <span>★</span>
                                        </div>
                                    </button>
                                    </h2>
                                    <div id="collapsePython" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                                        <div class="accordion-body cards">
                                            <div class="card" style="background: #CCCCFC;">
                                                <h2>Python</h2>
                                                <div class="rating">
                                                    <span class="hover">★</span>
                    <span class="hover">★</span>
                    <span>★</span>
                    <span>★</span>
                    <span>★</span>
                                                </div>
                                                <p>
                                                    <label id="lbl-progress-python" for="exp_subtotal_5">Jeden miesiąc</label>
                          <progress id="exp_subtotal_5" value="5" max="100">5%</progress>
                                                </p>
                                            </div>
                                            <div class="card" style="background: #d3d3ff;">
                                                <h2 class='header-worked-on'>Pracowałem nad:</h2>
                                                <ul id='list-worked-on-python'>
                                                                                                            <li>Checkout dla sklepu Shopify w shopify api</li>
                                                                                                    </ul>
                                                <h2 class='header-used-techs'>Używane technologie:</h2>
                                                <b>Flask, Shopify, Python, Babel, MongoDB</b>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                                        </div>
                        </section>
                    </div>
                </div>
                <div class="row">
                    <div class="col">
                        <section id="education">
                            <h2 id="header-education">Edukacja</h2>
                        </section>
                    </div>
                </div>
                <footer>Copyright&COPY;2023-2024 Kamil Szwaradzki</footer>
        </div>
    </div>
</div>
