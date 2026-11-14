<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="we74n-pzu"/><path class="shxk8y2pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scan-booking" /></template>
<style>
.shxk8y2pl {
  d: path("M14.5 16v-1.5H16m4 0h1.5V16m0 4v1.5H20m-4 0h-1.5V20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.we74n-pzu {
  d: path("M11.7 20.5H3.5V5h17v6.7M8 3v4m8-4v4M3.5 10h17");
}

</style>
