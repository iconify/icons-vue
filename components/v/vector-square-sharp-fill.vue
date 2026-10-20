<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="gz6_lrssd"/><path class="jeua-kmfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-square-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gz6_lrssd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L7 2C7.5523 2 8 2.4477 8 3L8 7C8 7.5523 7.5523 8 7 8L3 8C2.4477 8 2 7.5523 2 7L2 3C2 2.4477 2.4477 2 3 2ZM17 2L21 2C21.5523 2 22 2.4477 22 3L22 7C22 7.5523 21.5523 8 21 8L17 8C16.4477 8 16 7.5523 16 7L16 3C16 2.4477 16.4477 2 17 2ZM3 16L7 16C7.5523 16 8 16.4477 8 17L8 21C8 21.5523 7.5523 22 7 22L3 22C2.4477 22 2 21.5523 2 21L2 17C2 16.4477 2.4477 16 3 16ZM17 16L21 16C21.5523 16 22 16.4477 22 17L22 21C22 21.5523 21.5523 22 21 22L17 22C16.4477 22 16 21.5523 16 21L16 17C16 16.4477 16.4477 16 17 16Z");
  stroke: none;
}

.jeua-kmfe {
  d: path("M7 5L17 5M7 19L17 19M5 7L5 17M19 7L19 17");
}

</style>
