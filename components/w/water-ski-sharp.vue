<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="t8yaf7baj"/><path class="sf0hycc7f"/><path class="fn9jtbcsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-ski-sharp" /></template>
<style>
.fn9jtbcsg {
  d: path("M2.75 15.75c3 1.25 9 1.5 13 1m-13 3.75L5 19.375L7.25 20.5l2.25 1.125l2.25-1.125c1.5-.75 3 .75 4.5 0");
}

.sf0hycc7f {
  d: path("m7.25 7.5l-.75 4l3.25 2.25l-.75 2.5M7.25 7.5L13 9m-6.5 2.5l-2 4.5M13 9l8.25-4.75");
}

.t8yaf7baj {
  cx: 6.5px;
  cy: 4.5px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
