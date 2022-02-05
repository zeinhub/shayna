<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeaderShayna/>
    <HeroSection/>
    <WomenBanner/>
    <InstaShayna/>
    <PartnerShayna/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroSection from '@/components/HeroSection.vue'
import WomenBanner from '@/components/WomenBanner'
import InstaShayna from '@/components/InstaShayna'
import PartnerShayna from '@/components/PartnerShayna'
import FooterShayna from '@/components/FooterShayna'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    HeaderShayna,
    HeroSection,
    WomenBanner,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
