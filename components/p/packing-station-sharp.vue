<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="se_jd4bqw"/><circle class="bc1vn5bja"/><path class="zg2x11b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:packing-station-sharp" /></template>
<style>
.bc1vn5bja {
  cx: 18.25px;
  cy: 8.75px;
  r: 2px;
}

.se_jd4bqw {
  d: path("M5.5 5H14v5.75H5.5zm4.25 0v2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zg2x11b5s {
  d: path("M2.75 13.25h18.5m-16.5 0v8m14.5-8v8m-14.5-3.5h14.5");
}

</style>
