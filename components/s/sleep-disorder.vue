<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m7c2u4ipu"/><path class="fa7xchh_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sleep-disorder" /></template>
<style>
.fa7xchh_g {
  fill: currentColor;
  d: path("M17 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.m7c2u4ipu {
  d: path("M3 5v15M5 9.75h5v2.75H5ZM3 14h8.25c.761 0 1.378.435 1.629 1.084m-1.59 2.416H3m8.25.9V20m3-2c1.25-2 2.5-2.75 3.75-2.75s2.5.75 3.75 2.75c-1.25 2-2.5 2.75-3.75 2.75S15.5 20 14.25 18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
