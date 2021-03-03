<template>
  <div class="home">
    <HeaderShyna />
    <HeroShyna />
    <WomenShyna />
    <InstaShyna />
    <PartnerShyna />
    <FooterShyna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShyna from "@/components/HeaderShyna.vue";
import HeroShyna from "@/components/HeroShyna.vue";
import WomenShyna from "@/components/WomenShyna.vue";
import InstaShyna from "@/components/InstaShyna.vue";
import PartnerShyna from "@/components/PartnerShyna.vue";
import FooterShyna from "@/components/FooterShyna.vue";

export default {
  name: "Home",
  components: {
    HeaderShyna,
    HeroShyna,
    WomenShyna,
    InstaShyna,
    PartnerShyna,
    FooterShyna,
  },
};
</script>
