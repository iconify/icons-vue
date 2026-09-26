<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uu2ywi0jh"/><path class="dzmd--vds"/><path class="oj7ascbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-cast-sharp-duotone" /></template>
<style>
.dzmd--vds {
  d: path("M3 18L4 18C6.2091 18 8 19.7909 8 22L8 23M3 14L4 14C8.4183 14 12 17.5817 12 22L12 23");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oj7ascbsc {
  fill: currentColor;
  d: path("M5 22C5 22.5523 4.5523 23 4 23C3.4477 23 3 22.5523 3 22C3 21.4477 3.4477 21 4 21C4.5523 21 5 21.4477 5 22Z");
  stroke: none;
}

.uu2ywi0jh {
  stroke-opacity: 0.4;
  d: path("M6 11.0455L6 2L20 2L20 22L16 22L15 22M10.5 6L15.5 6");
}

</style>
