<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7mtbeafw"/><path class="tmze3ubnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-newsagent" /></template>
<style>
.k7mtbeafw {
  d: path("M3.5 4H17v14.75a1.75 1.75 0 0 0 1.75 1.75H5.5a2 2 0 0 1-2-2Z");
}

.tmze3ubnw {
  d: path("M17 8.5h3.5v10.25a1.75 1.75 0 0 1-1.75 1.75M6.5 7H14v4H6.5Zm0 7H14m-7.5 3.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
