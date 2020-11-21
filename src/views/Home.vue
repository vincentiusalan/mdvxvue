<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
      <header-mdvx/>
      <hero-mdvx/>
      <slide-item/>
      <insta-mdvx/>
      <partner-mdvx/>
      <footer-mdvx/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderMdvx from '@/components/HeaderMdvx.vue';
import HeroMdvx from '@/components/HeroMdvx.vue';
import SlideItem from '@/components/SlideItem.vue';
import InstaMdvx from '@/components/InstaMdvx.vue';
import PartnerMdvx from '../components/PartnerMdvx.vue';
import FooterMdvx from '../components/FooterMdvx.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld
    HeaderMdvx,
    HeroMdvx,
    SlideItem,
    InstaMdvx,
    PartnerMdvx,
    FooterMdvx
  }
}
</script>
