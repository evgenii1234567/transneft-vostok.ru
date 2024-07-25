<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transneft</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/faac65ac32.js" crossorigin="anonymous"></script>
</head>
<body>
    <div class="nav" class="logo-holder">
        <a href="https://transneft.ru/" target="_blank" class="active">
            <img src="images/t2.png" align="left" alt="Транснефть" class="logo-img">
        </a>
        <a href="transneft.html">Главная</a>
        <a href="transneft2.html">О компании</a>
        <a href="transneft4.html">Новости</a>
        <a href="transneft3.html">Контакты</a>
        <a href="mailto:transneft@transneft.ru"><i class="fas fa-envelope"></i></a>
        <a href="tel:+74959508178"><i class="fas fa-phone-alt"></i></a>

    </div>



    <div class="slider middle">
        <div class="slides">
            <input type="radio" name="r" id="r1" checked onclick="moveToSlide(0)" />
            <input type="radio" name="r" id="r2" onclick="moveToSlide(1)" />
            <input type="radio" name="r" id="r3" onclick="moveToSlide(2)" />
            <input type="radio" name="r" id="r4" onclick="moveToSlide(3)" />
    
            <div class="slide "><img src="images/01.jpg" alt="">
                <div class="textSlide"><b><i>Команда профессионалов - залог успеха</i></b></div>
            </div>
            <div class="slide"><img src="images/02.jpg" alt="">
                <div class="textSlide"><b><i>Нефть под надежным контролем</i></b></div>
            </div>
            <div class="slide"><img src="images/03.jpg" alt="">
                <div class="textSlide"><b><i>Наши решения - ваша уверенность</i></b></div>
            </div>
            <div class="slide"><img src="images/04.jpg" alt="">
                <div class="textSlide"><b><i>Точность и контроль на каждом этапе</i></b></div>
            </div>
        </div>
    
        <div class="navigation">
            <label for="r1" class="bar"></label>
            <label for="r2" class="bar"></label>
            <label for="r3" class="bar"></label>
            <label for="r4" class="bar"></label>
        </div>
    </div>    
       
    
    <script>
        
        var indexValue = 0; // Начальная позиция слайда
        var slideTimer; // Переменная для хранения таймера

        function SlideShow() {
            var slide = document.querySelectorAll(".slide");

            // Скрываем все слайды
            for (var x = 0; x < slide.length; x++) {
                slide[x].style.display = "none";
            }

            // Показываем текущий слайд
            slide[indexValue].style.display = "block";

            // Запускаем автоматическое переключение слайдов
            slideTimer = setTimeout(function() {indexValue = (indexValue + 1) % slide.length; // Увеличиваем индекс и переходим к следующему слайду
                SlideShow(); 
            }, 3000); // Переход к следующему слайду через 3 секунды
        }

        function moveToSlide(startIndex) {
            clearTimeout(slideTimer); // Сбрасываем таймер

            indexValue = startIndex; // Устанавливаем индекс на начальное значение

            SlideShow(); // Запускаем слайд-шоу
        }

        // Инициализируем слайд-шоу
        SlideShow();
    
    </script>
    
    
    
    


    <div class="text">
        
        <center><p><a href="https://ru.wikipedia.org/wiki/Транснефть" target="_blank" style="text-decoration: none; color: #222"><b>«Транснефть»</b></a> <b> — крупнейшая в мире трубопроводная компания в области транспортировки нефти и нефтепродуктов </b></p></center>
                    
        <p><i>
            Транснефть – ведущая компания в России и крупнейшая нефтепроводная компания в мире, занимающаяся транспортировкой нефти и нефтепродуктов. Основанная в 1993 году, она управляет разветвленной сетью трубопроводов, обеспечивая надежную поставку углеводородов по всей стране и за её пределами. 
        </i></p>

        <center><img src="images/07.webp" alt="Транснефть" title="Транснефть" style="box-shadow: rgb(140, 165, 236) 0px 5px 30px 2px; width: 120vh; height: auto;"></center>

        <p><i>
            Грузооборот Транснефти более чем в семь раз превышает показатель грузооборота ближайших аналогов – Enbridge и Colonial. По протяженности нефтепроводов Транснефть также занимает первое место, превышая медианное значение более чем в 6,6 раза.
        </i></p>

        <p><i>
            Компания активно реализует проекты по модернизации инфраструктуры, повышая эффективность и безопасность транспортировки.
        </i></p>

        <center><img src="images/06.jpg" alt="Транснефть" title="Транснефть" style="box-shadow: rgb(140, 165, 236) 0px 5px 30px 2px; width: 120vh; height: auto;"></center>

        <p><i>
            Помимо транспортировки нефти и нефтепродуктов по территории России, у Транснефти есть свои представительства в Венгрии, Словакии, Республике Беларусь и других странах. Она оказывает услуги по хранению нефти и нефтепродуктов в системе магистральных трубопроводов, компаундированию нефти (технология управляемого смешения нескольких потоков разных сортов нефти в один установленного качества) и реализации нефти и нефтепродуктов.
        </i></p>

        <p><i>
            Транснефть также уделяет внимание экологии, внедряя технологии, направленные на снижение негативного воздействия на окружающую среду.
        </i></p>

        <center><img src="images/05.jpg" alt="Транснефть" title="Транснефть" style="box-shadow: rgb(140, 165, 236) 0px 5px 30px 2px; width: 120vh; height: auto;"></center>
    
    </div>
    
    
    
    <style>
        body {
            background-image: url(https://baldezh.top/uploads/posts/2021-12/1640356125_26-funart-pro-p-foni-dlya-stranits-na-saiti-26.jpg) ;
        }
    </style>
    
    
    
    
    
    <section id="footer">
        <div class="footer">
            <div class="footer-left">
                <h2>Часы работы</h2>
                <p><i class="fas fa-clock"></i> Понедельник - Пятница: 8:00 - 17:00</p>
                <p><i class="fas fa-clock"></i> Суббота - Воскресенье: Выходной</p>
                <h1><i class="fas fa-globe"></i><a href="transneft.html" style="text-decoration: none; color: #fff;"><i>ТРАНСНЕФТЬ</i></a></h1>
            </div>
            <div class="footer-right">
                <h2>Контакты</h2>
                <p><i class="fas fa-map-marker-alt"></i> 123112, г. Москва, Пресненская набережная, д. 4, стр. 2, башня «Эволюция»</p>
                <p><i class="fas fa-envelope"></i> <a href="mailto:transneft@transneft.ru" style="text-decoration: none; color: #fff">transneft@transneft.ru</a></p>
                <p><i class="fas fa-phone-alt"></i> <a href="tel:+74959508178" style="text-decoration: none; color: #fff">+7 (495) 950-81-78</a></p>
            </div>
        </div>
        <div class="social-links">
            <a href="https://vk.com/transneftofficial" target="_blank"><i class="fab fa-vk"></i></a>
            <a href="https://t.me/transneftofficial" target="_blank"><i class="fab fa-telegram"></i></a>
            <a href="https://rutube.ru/channel/24671057/videos/" target="_blank"><i class="fab fa-youtube"></i></a>
        </div>
    </section>




</body>
</html>
