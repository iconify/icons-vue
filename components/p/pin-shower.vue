<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fgqqg8b1s"/><path class="wdg-u7bfj"/><path class="y1t4e_bqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-shower" /></template>
<style>
.fgqqg8b1s {
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wdg-u7bfj {
  d: path("M9 11.5a3 3 0 0 1 6 0Z");
}

.y1t4e_bqf {
  d: path("M12 8.5V6.75h2.5m-5.25 7.5h.01m2.74.5h.01m2.74-.5h.01");
}

</style>
