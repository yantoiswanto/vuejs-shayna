<template>
  <div class="home">
    <Header />
    <Hero/>
    <Woman/>
    <Instagram />
    <LogoPartner/>
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import Woman from '@/components/WomanProduct.vue';
import Instagram from '@/components/Instagram.vue'
import LogoPartner from '@/components/LogoPartner.vue';
import Footer from '@/components/Footer.vue';
export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Woman,
    Instagram,
    LogoPartner,
    Footer
  }
}
</script>

