<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ni7uz5z6i"/><path class="nuoa3usnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-zap-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ni7uz5z6i {
  d: path("M20.2929 3.7071L17 7L21 7L17.7071 10.2929");
}

.nuoa3usnr {
  fill: currentColor;
  d: path("M10 3C12.0711 3 14 4.9289 14 7C14 9.0711 12.0711 11 10 11C7.9289 11 6 9.0711 6 7C6 4.9289 7.9289 3 10 3ZM9 13L11 13C14.7279 13 18 16.2721 18 20L18 21C18 21.5523 17.5523 22 17 22L3 22C2.4477 22 2 21.5523 2 21L2 20C2 16.2721 5.2721 13 9 13Z");
  stroke: none;
}

</style>
