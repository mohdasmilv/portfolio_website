<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royaldrive - Luxury Garage</title>
    <style>
        body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 0;
}

.header{
    background-color: #000b0c;
    color: rgb(233, 233, 233);
    text-align: center;
    padding: 40px 0;
    font-size: 36px;
    font-weight: bold;
}

.car-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 40px;
    max-width: 1600px;
    margin: 0 auto;
}

.car-item {
    background-color: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    color: inherit;
}

.car-item:hover {
    transform: scale(1.05);
}

.car-item img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-bottom: 1px solid #e0e0e0;
}

.car-name {
    padding: 15px;
    font-size: 18px;
    font-weight: 600;
    color: #333;
}

@media (max-width: 768px) {
    .header {
        font-size: 28px;
    }

    .car-name {
        font-size: 16px;
    }
}

    </style>
</head>
<body>

    <div class="header">
        Royal-Drive
    </div>

    <div class="car-list">
        
        <a href="https://www.lamborghini.com/en-en/models/aventador" target="_blank" class="car-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTY4qW62-yS0GBYkvAfAY-KVM4zijhA_YdyJg&s" alt="Lamborghini Aventador">
            <div class="car-name">LAMBORGINI AVENTODER</div>
            
        </a>

    
        <a href="https://www.ferrari.com/en-EN/auto/812-superfast" target="_blank" class="car-item">
            <img src="https://stimg.cardekho.com/images/carexteriorimages/630x420/Ferrari/812/7859/1591619494883/front-left-side-47.jpg?imwidth=320&impolicy=resize" alt="Ferrari 812 Superfast">
            <div class="car-name">FERRARI 812 SUPERFAST</div>
        </a>

        
        <a href="https://www.porsche.com/international/models/911/911-turbo-models/" target="_blank" class="car-item">
            <img src="https://stimg.cardekho.com/images/carexteriorimages/630x420/Porsche/911/10997/Porsche-911-Turbo-S/1717681627351/front-left-side-47.jpg" alt="Porsche 911 Turbo S">
            <div class="car-name">PORSCHE 911 TURBO S</div>
        </a>

        <a href="https://www.astonmartin.com/en/models/dbs-superleggera" target="_blank" class="car-item">
            <img src="https://wallpapersmug.com/download/1024x768/fe092b/car-aston-martin-dbs-superleggera-luxurious.jpg" alt="Aston Martin DBS Superleggera">
            <div class="car-name">ASTON MARTIN DBS SUPERLEGGERA</div>
        </a>

        <a href="https://www.bentleymotors.com/en/models/new-continental-gt.html" target="_blank" class="car-item">
            <img src="https://stimg.cardekho.com/images/carexteriorimages/630x420/Bentley/Continental/7771/1708637147871/front-left-side-47.jpg?imwidth=420&impolicy=resize" alt="Bentley Continental GT">
            <div class="car-name">BENTLEY CONTINENTAL GT</div>
        </a>

        <a href="https://www.rolls-roycemotorcars.com/en_GB/showroom/phantom.html" target="_blank" class="car-item">
            <img src="https://www.topgear.com/sites/default/files/cars-car/image/2017/10/_jl58227.jpg" alt="Rolls Royce Phantom">
            <div class="car-name">ROLLS ROYCE PHANTOM</div>
        </a>

        <a href="https://www.mercedes-benz.co.in/passengercars/models/saloon/s-class/overview.html" target="_blank" class="car-item">
            <img src="https://www.financialexpress.com/wp-content/uploads/2016/03/Mercedes-Benz-S-Class-2021-india-launch-amg-line.jpg?resize=768,512" alt="Mercedes-Benz S-Class">
            <div class="car-name">Mercedes-Benz S-Class</div>
        </a>

        <a href="https://www.mercedes-benz.co.in/passengercars/models/suv/g-class/overview.html" target="_blank" class="car-item">
            <img src="https://oasislimo.b-cdn.net/wp-content/uploads/2016/05/g-wagon-black-slider1-1.jpg" alt="Mercedes-Benz G-Class (G Wagon)">
            <div class="car-name">MERCEDES-BENZ-G-CLASS (G Wagon)</div>
        </a>

        <a href="https://www.bmw.com/en/bmw-models/7-series-sedan.html" target="_blank" class="car-item">
            <img src="https://www.bmw-special-sales.com/content/dam/bmw/marketBMWCOM/bmw-special-sales_com/common/protection/7-protection/bmw-css-7-series-protection-cp-protection-desktop.jpg" alt="BMW 7 Series">
            <div class="car-name">BMW 7 SERIES</div>
        </a>

        <a href="https://www.audi.com/en/models/a8.html" target="_blank" class="car-item">
            <img src="https://www.carblogindia.com/wp-content/uploads/2019/08/2019-audi-a8l-first-drive-1.jpg" alt="Audi A8">
            <div class="car-name">AUDI A8</div>
        </a>

        <a href="https://cars.mclaren.com/en/supercars/720s" target="_blank" class="car-item">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/2018_McLaren_720S_V8_S-A_4.0.jpg/280px-2018_McLaren_720S_V8_S-A_4.0.jpg" alt="McLaren 720S">
            <div class="car-name">Mcleren 720S</div>
        </a>

        <a href="https://www.bugatti.com/chiron/" target="_blank" class="car-item">
            <img src="https://preview.redd.it/7prpmvj0tmr91.jpg?width=1080&crop=smart&auto=webp&s=6659cae38316743d6995d42bd7ae019048b1053f" alt="Bugatti Chiron">
            <div class="car-name">BUGGATI CHIRON</div>
        </a>

        <a href="https://www.pagani.com/huayra/" target="_blank" class="car-item">
            <img src="https://cdn.motor1.com/images/mgl/7ZvJM1/s3/pagani-huayra-r-evo.jpg" alt="Pagani Huayra">
            <div class="car-name">PAGANI HUAYRA</div>
        </a>

        <a href="https://www.maserati.com/global/en/models/quattroporte" target="_blank" class="car-item">
            <img src="https://maserati.scene7.com/is/image/maserati/maserati/international/Models/my22/quattroporte-my22/trofeo/16_9/QP_pista.jpg?$1400x2000$&fit=constrain" alt="Rolls Royce Phantom">
            <div class="car-name">MASERATI QUATTROPORTE</div>
        </a>

        <a href="https://www.jaguar.com/jaguar-range/xj/index.html" target="_blank" class="car-item">
            <img src="https://i.pinimg.com/736x/3b/7a/68/3b7a6842d7d607772e8119816b62b67a.jpg" alt="Jaguar XJ">
            <div class="car-name">JAGUAR XJ</div>
        </a>

        <a href="https://www.lexus.com/models/LS" target="_blank" class="car-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBjcIm7u7Z28_nLjVo2_jd3zIfjfDijuTqRQ&s" alt="Lexus LS">
            <div class="car-name">LEXUS LS</div>
        </a>

        <a href="https://www.cadillac.com/sedans/ct6-sedan" target="_blank" class="car-item">
            <img src="https://hips.hearstapps.com/amv-prod-cad-assets.s3.amazonaws.com/vdat/submodels/cadillac_ct6_cadillac-ct6_2020-1641330797773.jpg?fill=18:11&resize=640:*" alt="Cadillac CT6">
            <div class="car-name">CADILLAC CT6</div>
        </a>

        <a href="https://www.genesis.com/worldwide/en/models/luxury-sedan-genesis/g90/highlights.html" target="_blank" class="car-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTN7k7l2kxKmwVolsjsb6ITwMIwut7_sPkWOg&s" alt="Genesis G90">
            <div class="car-name">GENESIS G90</div>
        </a>

        <a href="https://www.landrover.com/vehicles/range-rover/index.html" target="_blank" class="car-item">
            <img src="https://stimg.cardekho.com/images/carexteriorimages/930x620/Land-Rover/Range-Rover/11540/1719037980777/front-left-side-47.jpg" alt="Range Rover Autobiography">
            <div class="car-name">RANGE ROVER AUTOBIOGRAPHY</div>
        </a>

        <a href="https://www.tesla.com/models" target="_blank" class="car-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQQkALdLw7qab9Ax7s3FKz5IjzG6-1DcF2bmg&s" alt="Tesla Model S Plaid">
            <div class="car-name">TESLA MODEL S PLAID</div>
        </a>

        <a href="https://www.lucidmotors.com/air" target="_blank" class="car-item">
            <img src="https://hips.hearstapps.com/hmg-prod/images/2022-lucid-air-dream-edition-performance-101-1636049140.jpg?crop=1.00xw:1.00xh;0,0&resize=640:*" alt="Lucid Air Dream Edition">
            <div class="car-name">LUCID AIR DREAM EDITION</div>
            
        </a>

        <a href="https://www.astonmartin.com/en/models/vantage" target="_blank" class="car-item">
            <img src="https://static.toiimg.com/thumb/msid-112888111,width-1280,height-720,resizemode-4/112888111.jpg" alt="Aston Martin Vantage">
            <div class="car-name">ASTON MARTIN VANTAGE</div>
        </a>

        <a href="https://www.ferrari.com/en-EN/auto/ferrari-roma" target="_blank" class="car-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSraU-HqNtMuCKh9_NMSp89-ubrHDwmuSDe_g&s" alt="Ferrari Roma">
            <div class="car-name">FERRARI ROMA</div>
        </a>

        <a href="https://www.bmw.com/en/bmw-models/bmw-i8.html" target="_blank" class="car-item">
            <img src="https://static.wixstatic.com/media/393310_9408e36a2fb1484d9e5afb37309c18c8~mv2.jpg/v1/fill/w_520,h_348,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/393310_9408e36a2fb1484d9e5afb37309c18c8~mv2.jpg" alt="BMW i8">
            <div class="car-name">BMW i8</div>
        </a>

        <a href="https://www.rolls-roycemotorcars.com/en_GB/bespoke/collection-cars/wraith-black-arrow.html" target="_blank" class="car-item">
            <img src=https://cdn.motor1.com/images/mgl/13jgw/s3/rolls-royce-black-badge-wraith-by-spofec.jpg alt="Rolls Royce Wraith">
            <div class="car-name">ROLLS ROYCE WRAITH</div>
        </a>

    </div>
    <footer style="text-align: center;">
        <p>&copy; Royal-Drive 2024</p>
    </footer>
    
    


</body>
</html>
