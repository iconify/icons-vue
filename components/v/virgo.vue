<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bskne_hzy"/><path class="lix-bvb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:virgo" /></template>
<style>
.bskne_hzy {
  d: path("M3.75 6.5C5.25 6.5 6 7.5 6 9v11.25M6 9c0-1.5 1-2.5 2.5-2.5S11 7.5 11 9v11.25M11 9c0-1.5 1-2.5 2.5-2.5S16 7.5 16 9v11.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lix-bvb9h {
  d: path("M16 13c2.75-1 4.25.5 4.25 2.5c0 2.5-2.25 4.25-6 4.75");
}

</style>
