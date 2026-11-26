<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yl2584b_u"/><path class="zg5tt4bnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-distort-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yl2584b_u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L7 2C7.5523 2 8 2.4477 8 3L8 7C8 7.5523 7.5523 8 7 8L3 8C2.4477 8 2 7.5523 2 7L2 3C2 2.4477 2.4477 2 3 2ZM19 5L21 5C21.5523 5 22 5.4477 22 6L22 10C22 10.5523 21.5523 11 21 11L17 11C16.4477 11 16 10.5523 16 10L16 6C16 5.4477 16.4477 5 17 5ZM17 16L19 16C19.5523 16 20 16.4477 20 17L20 21C20 21.5523 19.5523 22 19 22L15 22C14.4477 22 14 21.5523 14 21L14 17C14 16.4477 14.4477 16 15 16ZM7 12L9 12C9.5523 12 10 12.4477 10 13L10 17C10 17.5523 9.5523 18 9 18L5 18C4.4477 18 4 17.5523 4 17L4 13C4 12.4477 4.4477 12 5 12Z");
  stroke: none;
}

.zg5tt4bnd {
  d: path("M3 3L7 3L7 7L3 7ZM17 6L21 6L21 10L17 10ZM15 17L19 17L19 21L15 21ZM5 13L9 13L9 17L5 17ZM7 5L17 8M19 10L17 17M15 19L9 15M7 13L5 7");
}

</style>
