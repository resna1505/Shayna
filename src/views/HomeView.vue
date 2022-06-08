<template>
  <div class="home">
    <HeaderShayna/>
    <HeroShayna/>
    <WomanShayna/>
    <InstagramShayna/>
    <PartnerShayna/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import WomanShayna from '@/components/WomanShayna.vue'
import InstagramShayna from '@/components/InstagramShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'
// import carousel from 'vue-owl-carousel'

export default {
  name: 'HomeView',
    components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstagramShayna,
    PartnerShayna,
    FooterShayna
}
}
</script>
