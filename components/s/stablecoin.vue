<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vzrb_jbrn"/><path class="vyzbnkbbf"/><path class="zr9bgyb0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stablecoin" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vyzbnkbbf {
  d: path("M2.5 9v3a4 2.5 0 0 0 8 0V9m3 0a4 2.5 0 1 0 8 0a4 2.5 0 1 0-8 0Z");
}

.vzrb_jbrn {
  d: path("M2.5 9a4 2.5 0 1 0 8 0a4 2.5 0 1 0-8 0Z");
}

.zr9bgyb0d {
  d: path("M13.5 9v3a4 2.5 0 0 0 8 0V9m-19 8.5h19");
}

</style>
