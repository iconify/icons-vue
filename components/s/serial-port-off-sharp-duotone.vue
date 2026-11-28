<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kbv2zjb5q"/><path class="qib3ujb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:serial-port-off-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kbv2zjb5q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 19H4.159C3.675 19 3.26 18.653 3.175 18.177L1.017 6.177C1.007 6.119 1.001 6.059 1.001 6C1.001 5.448 1.449 5 2.001 5H5L19 19ZM8.657 5H12H21.998C22.551 5 22.998 5.448 22.998 6C22.998 6.059 22.993 6.119 22.983 6.177L20.979 17.322L8.657 5ZM17 10C17 9.448 16.552 9 16 9C15.448 9 15 9.448 15 10C15 10.552 15.448 11 16 11C16.552 11 17 10.552 17 10Z");
  stroke: none;
}

.qib3ujb7r {
  d: path("M1.707 1.707L22.293 22.293");
}

</style>
