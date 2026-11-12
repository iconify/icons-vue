<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="q0pnou38b"/><path class="wws34lbrr"/><path class="tloly4b5q"/><path class="qy5qlq-tp"/><path class="t9mbxobpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wad-of-money-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0pnou38b {
  d: path("M22 12C22 14.8089 22 16.2134 21.3259 17.2223C21.034 17.659 20.659 18.034 20.2223 18.3259C19.2134 19 17.8089 19 15 19H9C6.19108 19 4.78661 19 3.77772 18.3259C3.34096 18.034 2.96596 17.659 2.67412 17.2223C2 16.2134 2 14.8089 2 12C2 9.19108 2 7.78661 2.67412 6.77772C2.96596 6.34096 3.34096 5.96596 3.77772 5.67412C4.78661 5 6.19108 5 9 5L15 5C17.8089 5 19.2134 5 20.2223 5.67412C20.659 5.96596 21.034 6.34096 21.3259 6.77772C22 7.78661 22 9.19108 22 12Z");
}

.qy5qlq-tp {
  d: path("M9 5V18.5");
}

.t9mbxobpm {
  d: path("M15 5V18.5");
}

.tloly4b5q {
  d: path("M15 9C16.6569 9 18 10.3431 18 12C18 13.6569 16.6569 15 15 15");
}

.wws34lbrr {
  d: path("M9 15C7.34315 15 6 13.6569 6 12C6 10.3431 7.34315 9 9 9");
}

</style>
