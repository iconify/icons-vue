<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="lqhrolaqd"/><path class="m96kdikcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-arrow-left-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lqhrolaqd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 3C11.0711 3 13 4.9289 13 7C13 9.0711 11.0711 11 9 11C6.9289 11 5 9.0711 5 7C5 4.9289 6.9289 3 9 3ZM8 13L10 13C13.7279 13 17 16.2721 17 20L17 21C17 21.5523 16.5523 22 16 22L2 22C1.4477 22 1 21.5523 1 21L1 20C1 16.2721 4.2721 13 8 13Z");
  stroke: none;
}

.m96kdikcc {
  d: path("M23 7L16 7M19.2929 3.7071L16 7L19.2929 10.2929");
}

</style>
