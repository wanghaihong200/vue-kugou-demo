<template>
  <div id="app">
    <HeadTop />
    <div class="main">
      <keep-alive>
        <router-view></router-view>
      </keep-alive>
    </div>
    <Player />
	  <DetailPlayer />
	</div>
</template>

<script>
  import HeadTop from './components/header/Head'
  import Player from './components/Player'
  import DetailPlayer from './components/DetailPlayer'
  export default {
    components: {
      HeadTop, Player, DetailPlayer
    }
  }
</script>

