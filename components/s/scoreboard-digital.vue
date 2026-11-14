<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hrzc23bjy"/><path class="y0gcmyb3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scoreboard-digital" /></template>
<style>
.hrzc23bjy {
  d: path("M2.5 3h19v13.5h-19ZM7 16.5v5m10-5v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0gcmyb3j {
  d: path("M6 6.5h4V13H6Zm10 0V13m-1.5-5L16 6.5");
}

</style>
