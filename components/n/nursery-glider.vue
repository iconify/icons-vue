<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n-9tk3bho"/><path class="ez9d3ktpn"/><path class="itxyfybyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nursery-glider" /></template>
<style>
.ez9d3ktpn {
  d: path("M6.75 9.5h9.75v9.75M8 13.5v6");
}

.itxyfybyu {
  d: path("M3 17.5q9 5 18 0");
}

.n-9tk3bho {
  d: path("m5.5 3l2 10.5h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
