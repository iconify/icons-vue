<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zw_tbcbml"/><path class="hpno7k-2y"/><path class="ifgz10bgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-arrow-right-duotone" /></template>
<style>
.hpno7k-2y {
  fill: currentColor;
  d: path("M14 2.558C14 1.472 15.071 0.744 16.058 1.083L16.254 1.165L21.139 3.607C22.287 4.181 22.286 5.819 21.139 6.393L16.254 8.835C15.219 9.352 14 8.6 14 7.442V2.558Z");
  stroke: none;
}

.ifgz10bgv {
  d: path("M15 5H10.5C8.567 5 7 6.567 7 8.5C7 10.433 8.567 12 10.5 12H14.5C16.433 12 18 13.567 18 15.5C18 17.433 16.433 19 14.5 19H9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zw_tbcbml {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 19C10 21.209 8.209 23 6 23C3.791 23 2 21.209 2 19C2 16.791 3.791 15 6 15C8.209 15 10 16.791 10 19Z");
  stroke: none;
}

</style>
