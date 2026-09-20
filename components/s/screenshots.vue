<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qjscruovd"/><path class="luqif_bcr"/><path class="l4lit0b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:screenshots" /></template>
<style>
.l4lit0b2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.924 36.48l-9.406 5.427c-.907.523-2.017 1.077-3.531-.13c-2.706-2.156-4.03-7.226-4.03-11.19v-6.435c0-3.03.477-3.743 1.906-4.568l8.9-5.136c1.78-1.027 3.22-.328 3.22 1.733V21.8c0 3.546 1.044 7.997 3.229 10.416c1.184 1.311 1.087 3.47-.288 4.264");
}

.luqif_bcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.447 34.968L18.18 37.43c-1.78 1.028-3.22.328-3.22-1.733V19.912c0-3.03.478-3.743 1.907-4.568l8.9-5.136c1.78-1.027 3.22-.327 3.22 1.733v4.684");
}

.qjscruovd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.96 31.012l-3.774 2.178c-1.78 1.028-3.22.328-3.22-1.733V15.672c0-3.03.478-3.743 1.908-4.568l8.9-5.136c1.78-1.027 3.219-.327 3.219 1.733v4.686");
}

</style>
