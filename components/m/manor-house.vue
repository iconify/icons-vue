<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t-peadbli"/><path class="klewgmbgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:manor-house" /></template>
<style>
.klewgmbgr {
  d: path("M4.5 9.75V4h3v3.25m9 0V4h3v5.75M10 21v-4a2 2 0 0 1 4 0v4");
}

.t-peadbli {
  d: path("m3 11l9-7.5l9 7.5v10H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
