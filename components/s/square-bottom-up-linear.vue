<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cb03pibjf"/><path class="bhy-axcbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-bottom-up-linear" /></template>
<style>
.bhy-axcbm {
  stroke-linejoin: round;
  d: path("M3 21L11 13M11 19V13H5");
}

.cb03pibjf {
  d: path("M13 21.9994C17.055 21.9921 19.1785 21.8926 20.5355 20.5355C22 19.0711 22 16.714 22 12C22 7.28595 22 4.92893 20.5355 3.46447C19.071 2 16.714 2 12 2C7.28593 2 4.9289 2 3.46444 3.46447C2.10741 4.8215 2.00785 6.94493 2.00055 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
