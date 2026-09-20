<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phk9ipbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-cricket-outline-sharp" /></template>
<style>
.phk9ipbcl {
  fill: currentColor;
  d: path("M11.5 16.854L2.452 7.806l3.354-3.354l9.048 9.048zm0-1.415l1.938-1.939L5.8 5.862L3.862 7.8zm7.1 5.869l-4.327-4.327l.708-.708l4.327 4.327zM16.544 7.456q-.813-.814-.813-1.956t.813-1.956t1.956-.813t1.956.813t.813 1.956t-.813 1.956t-1.956.813t-1.956-.813m3.21-.701q.515-.515.515-1.255t-.514-1.255t-1.255-.514t-1.255.514t-.514 1.255t.514 1.255t1.255.514t1.255-.514M8.65 10.65");
}

</style>
