<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v7qsuq7rf"/><path class="prmv6_0xb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treehouse" /></template>
<style>
.prmv6_0xb {
  d: path("M11 14v-3h2v3m-.25 0v7.5m3-7.5v7.5m-3-4.75h3m-3 2.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7qsuq7rf {
  d: path("M7.5 9L12 4.5L16.5 9v5h-9Zm-2 5h13m-9 0v7.5M6 14L3 9m15 5l3-5");
}

</style>
