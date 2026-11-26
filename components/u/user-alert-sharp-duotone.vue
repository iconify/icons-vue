<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i8hq46b4m"/><path class="p6g1_whuo"/><path clip-rule="evenodd" class="btwd0w9_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-alert-sharp-duotone" /></template>
<style>
.btwd0w9_q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 9C20 9.5523 19.5523 10 19 10C18.4477 10 18 9.5523 18 9C18 8.4477 18.4477 8 19 8C19.5523 8 20 8.4477 20 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i8hq46b4m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 13L13 13C16.7279 13 20 16.2721 20 20L20 21C20 21.5523 19.5523 22 19 22L5 22C4.4477 22 4 21.5523 4 21L4 20C4 16.2721 7.2721 13 11 13ZM12 3C14.0711 3 16 4.9289 16 7C16 9.0711 14.0711 11 12 11C9.9289 11 8 9.0711 8 7C8 4.9289 9.9289 3 12 3Z");
  stroke: none;
}

.p6g1_whuo {
  d: path("M19 2L19 6");
}

</style>
