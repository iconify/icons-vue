<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r-5g8_bwl"/><path class="ax8re0_an"/><path clip-rule="evenodd" class="v8bb7zbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tram-front-sharp-two-tone" /></template>
<style>
.ax8re0_an {
  d: path("M4 6L20 6L20 20L4 20ZM4 12L20 12M7 2L17 2M10 6L12 2L14 6M8 20L6.7236 22.5528M16 20L17.2764 22.5528");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r-5g8_bwl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5L20 5C20.5523 5 21 5.4477 21 6L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 6C3 5.4477 3.4477 5 4 5Z");
  stroke: none;
}

.v8bb7zbok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16ZM17 16C17 16.5523 16.5523 17 16 17C15.4477 17 15 16.5523 15 16C15 15.4477 15.4477 15 16 15C16.5523 15 17 15.4477 17 16Z");
  stroke: none;
}

</style>
