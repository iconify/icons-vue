<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xo40o401p"/><path class="wrzhaubou"/><path class="q1bxsco5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stadium" /></template>
<style>
.q1bxsco5j {
  d: path("M2.5 14a9.5 3.5 0 0 0 19 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrzhaubou {
  d: path("M2.5 11v6a9.5 3.5 0 0 0 19 0v-6M7 8V3l3 1.25L7 5.5M17 8V3l3 1.25l-3 1.25");
}

.xo40o401p {
  d: path("M2.5 11a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0Z");
}

</style>
