<template>
  <div class="home">
    <header-shayna />
    <banner-hero />
    <banner-begin/>
    <banner-insta/>
    <logo-partners/>
    <footer-shayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from "@/components/HeaderShayna.vue";
import BannerHero from "@/components/BannerHero.vue";
import BannerBegin from "@/components/BannerBegin.vue";
import BannerInsta from "@/components/BannerInsta.vue";
import LogoPartners from "@/components/LogoPartners.vue";
import FooterShayna from '@/components/FooterShayna';

export default {
  name: "Home",
  components: {
    // HelloWorld
    HeaderShayna,
    BannerHero,
    BannerBegin,
    BannerInsta,
    LogoPartners,
    FooterShayna,
  },
};
</script>
