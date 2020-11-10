# Web-slider
輪播系統

# 使用說明

## CDN

## 架構

~~~

<!-- 輪播圖大盒子 : data-slider-duration 自動輪播速度-->
    <div id="tammy-slider" data-slider-duration="2000">

        <!-- 輪播圖項目 : 根據需求複製貼上 active 只有一組-->
        <div class="tammy-item tammy-active">
            <img src="..." alt="">
            <h1>...</h1>
        </div>

        <div class="tammy-item">
            <img src="..." alt="">
            <h1>...</h1>
        </div>

        <div class="tammy-item">
            <img src="..." alt="">
            <h1>...</h1>
        </div>

        <div class="tammy-item">
            <img src="..." alt="">
            <h1>...</h1>
        </div>

        <!-- 大顆按鈕區塊 -->
        <div id="tammy-prev"></div>
        <div id="tammy-next"></div>

        <!-- 小顆按鈕區塊 : 根據需求複製貼上 active 只有一組-->
        <!-- 編號可以依需求增減-->
        <div id="tammy-buttons tammy-buttom-active">
            <div class="tammy-button" data-slider-item="1"></div>
            <div class="tammy-button" data-slider-item="2"></div>
            <div class="tammy-button" data-slider-item="3"></div>
            <div class="tammy-button" data-slider-item="4"></div>
        </div>
    </div>
    ~~~