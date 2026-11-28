<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="p_9_b_b4f"/><path class="p6g1_whuo"/><path clip-rule="evenodd" class="btwd0w9_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-alert-sharp-fill" /></template>
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

.p_9_b_b4f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C14.0711 2 16 3.9289 16 6C16 8.0711 14.0711 10 12 10C9.9289 10 8 8.0711 8 6C8 3.9289 9.9289 2 12 2ZM11 12L13 12C16.7279 12 20 15.2721 20 19L20 21C20 21.5523 19.5523 22 19 22L5 22C4.4477 22 4 21.5523 4 21L4 19C4 15.2721 7.2721 12 11 12Z");
  stroke: none;
}

.p6g1_whuo {
  d: path("M19 2L19 6");
}

</style>
