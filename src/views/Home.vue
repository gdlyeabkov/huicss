<template>
  <div>
    <HuiHeader />
    <div class="hui-main">
      <div style="margin-top: 25px; margin-left: 25px;">
        <div style="float: left; width: 55%;">
          <p class="hui-header-of-block">
            Строй удобно, сайты отвечающие ожиданиям с HuiCSS
          </p>
          <p class="hui-desc-of-block">
            Быстро создавайте и настраивайте адаптивные сайты, ориентированные на мобильные устройства, с помощью HuiCSS, самого популярного в мире инструментария с открытым исходным кодом для интерфейса пользователя, включающего переменные и миксины Sass, адаптивную сеточную систему, обширные готовые компоненты и мощные плагины JavaScript.
          </p>
          <div style="margin: 15px;">
            <button class="hui-button  hui-error" @click="$router.push({ name: 'GetStarted' })">Начать</button>
            <button class="hui-button  hui-light" @click="$router.push({ name: 'Download' })">Скачать</button>
          </div>
          <p>Currently v5.1.1 · v4.6.x docs · All releases</p>
        </div>
        <div style="margin-left: 25px; background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Internet_Explorer_10%2B11_logo.svg/1200px-Internet_Explorer_10%2B11_logo.svg.png'); background-size: 100% 100%; float: left; width: 175px; height: 175px;">
        </div>
        
        <div style="clear: both;"></div>
        <div class="hui-pad-25">
          <div class="hui-picture-layout">
          </div>
          <div class="hui-part">
            <div class="hui-part-of-layout">
              <p class="hui-header-of-block">
                Установка
              </p>
              <p class="hui-supHeader">
                Установите исходные файлы Sass и JavaScript HuiCSS через npm, Composer или Meteor.
              </p>
              <p class="hui-sub-header">
                Установки, управляемые пакетами, не включают в себя документацию или наши полные скрипты сборки. Вы также можете использовать репозиторий шаблонов npm для быстрого создания проекта HuiCSS через npm.
              </p>
            </div>
            <div>
              <div class="hui-editor">
                <button class="hui-editor-btn hui-button  hui-light">копия</button>
                <p class="hui-editor-string">npm install HuiCSS</p>
              </div>
              <div class="hui-editor">
                <button class="hui-editor-btn hui-button  hui-light">копия</button>
                <p class="hui-indent">gem install HuiCSS -v 5.1.1</p>
              </div>
            </div>
          </div>
          <button class="hui-pad-25 hui-button hui-light">Как установить</button>
        </div>

        <div class="hui-pad-25">
          <div style="margin-left: 25px; background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Internet_Explorer_10%2B11_logo.svg/1200px-Internet_Explorer_10%2B11_logo.svg.png'); background-size: 100% 100%; float: left; width: 75px; height: 75px;">
          </div>
          <div style="width: 100%; display: flex;">
            <div style="width: 35%;">
              <p class="hui-header-block">
                jsDelivr
              </p>
              <p class="hui-supHeader">
                Когда вам нужно включить только скомпилированный CSS или JS HuiCSS, вы можете использовать jsDelivr.
              </p>
              <p class="hui-sub-header">
                Посмотрите, как это работает, с помощью нашего простого стартового шаблона или просмотрите примеры, чтобы начать свой следующий проект. Вы также можете включить Popper и наш JS по отдельности.
              </p>
            </div>
            <div>
              <div class="hui-editor">
                <button class="hui-editor-btn hui-button  hui-light">копия</button>
                <p class="hui-editor-string">npm install HuiCSS</p>
              </div>
              <div class="hui-editor">
                <button class="hui-editor-btn hui-button  hui-light">копия</button>
                <p style="padding: 15px;">gem install HuiCSS -v 5.1.1</p>
              </div>
            </div>
          </div>
          <button class="hui-pad-25 hui-button hui-light">Посмотреть доки</button>
        </div>

        <div class="hui-pad-25">
          <div style="margin-left: 25px; background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Internet_Explorer_10%2B11_logo.svg/1200px-Internet_Explorer_10%2B11_logo.svg.png'); background-size: 100% 100%; float: left; width: 75px; height: 75px;">
          </div>
          <div style="width: 100%; display: flex;">
            <div style="width: 35%;">
              <p class="hui-header-block">
                HuiCSS иконки
              </p>
              <p class="hui-supHeader">
                Впервые в истории HuiCSS есть собственная библиотека значков SVG с открытым исходным кодом, предназначенная для наилучшей работы с нашими компонентами и документацией.
              </p>
              <p class="hui-sub-header">
                Иконки HuiCSS лучше всего работают с компонентами HuiCSS, но они будут работать в любом проекте. Это SVG-файлы, поэтому они легко и быстро масштабируются, могут быть реализованы несколькими способами и стилизованы с помощью CSS.
              </p>
            </div>
            <div>
              <img src="https://getbootstrap.com/docs/5.1/assets/img/bootstrap-icons.png" alt="" class="hui-picture">
            </div>
          </div>
          <button class="hui-pad-25 hui-button hui-light">Получить иконки</button>
        </div>

        <div class="hui-pad-25">
          <div style="margin-left: 25px; background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Internet_Explorer_10%2B11_logo.svg/1200px-Internet_Explorer_10%2B11_logo.svg.png'); background-size: 100% 100%; float: left; width: 75px; height: 75px;">
          </div>
          <div style="width: 100%; display: flex;">
            <div style="width: 35%;">
              <p class="hui-header-of-block">
                Официальные темы
              </p>
              <p class="hui-sup-header">
                Поднимите HuiCss на новый уровень с премиальными темами с официального магазина HuiCSS Themes.
              </p>
              <p class="hui-sub-header">
                Темы создаются на HuiCss как собственные расширенные фреймворки, богатые новыми компонентами и плагинами, документацией и мощными инструментами сборки.
              </p>
            </div>
            <div>
              <img src="https://getbootstrap.com/docs/5.1/assets/img/bootstrap-themes.png" alt="" class="hui-picture">
            </div>
          </div>
          <button class="hui-pad-25 hui-button hui-light">Смотреть темы</button>
        </div>

      </div>

    </div>

    <HuiFooter />

  </div>
</template>

<script>
import HuiHeader from "@/components/HuiHeader.vue"
import HuiFooter from "@/components/HuiFooter.vue"

export default {
  name: 'Home',
  components: {
    HuiHeader,
    HuiFooter
  }
}
</script>