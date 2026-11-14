<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ydwudw6zd"/><path class="evjg_vhnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-spot-finder" /></template>
<style>
.evjg_vhnj {
  d: path("M8.75 14V7H11a2.25 2.25 0 0 1 0 4.5H8.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydwudw6zd {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm12 5l5 5");
}

</style>
