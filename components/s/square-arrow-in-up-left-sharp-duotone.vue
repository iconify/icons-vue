<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wvzbsvdug"/><path class="k7ejdbcuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-in-up-left-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k7ejdbcuv {
  d: path("M21.2929 21.2929L13.1464 13.1464M22 13L13 13L13 22");
}

.wvzbsvdug {
  stroke-opacity: 0.4;
  d: path("M10 17L3 17L3 3L17 3L17 10");
}

</style>
