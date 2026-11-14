<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5lu7b39y"/><path class="hqja51g1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tariff-card" /></template>
<style>
.hqja51g1h {
  d: path("M13.75 13.75h4l3.75 3.75l-4 4l-3.75-3.75Zm2.75 2.75h.01");
}

.i5lu7b39y {
  d: path("M10.9 15.5H2.5v-12h17v8.1m-17-4.1h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
