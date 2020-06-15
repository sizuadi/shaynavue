<template>
  <div class="home">
    <Header />
    <HeroHeader />
    <SliderProducts />
    <InstaView />
    <LogoPartner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue';
import HeroHeader from '@/components/HeroHeader.vue';
import SliderProducts from '@/components/SliderProducts.vue';
import InstaView from '@/components/InstaView.vue';
import LogoPartner from '@/components/LogoPartner.vue'
import Footer from '@/components/Footer.vue';

export default {
  name: 'home',
  components: {
      Header,
      HeroHeader,
      SliderProducts,
      InstaView,
      LogoPartner,
      Footer
  }
}
</script>

