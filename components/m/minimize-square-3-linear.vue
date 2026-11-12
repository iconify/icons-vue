<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cb03pibjf"/><path class="vv3m6lbyb"/><path class="yqghi_b_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-3-linear" /></template>
<style>
.cb03pibjf {
  d: path("M13 21.9994C17.055 21.9921 19.1785 21.8926 20.5355 20.5355C22 19.0711 22 16.714 22 12C22 7.28595 22 4.92893 20.5355 3.46447C19.071 2 16.714 2 12 2C7.28593 2 4.9289 2 3.46444 3.46447C2.10741 4.8215 2.00785 6.94493 2.00055 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vv3m6lbyb {
  stroke-linejoin: round;
  d: path("M17 7L12 12M12 8.25V12H15.75");
}

.yqghi_b_r {
  d: path("M6 22C4.11438 22 3.17157 22 2.58579 21.4142C2 20.8284 2 19.8856 2 18C2 16.1144 2 15.1716 2.58579 14.5858C3.17157 14 4.11438 14 6 14C7.88562 14 8.82843 14 9.41421 14.5858C10 15.1716 10 16.1144 10 18C10 19.8856 10 20.8284 9.41421 21.4142C8.82843 22 7.88562 22 6 22Z");
}

</style>
