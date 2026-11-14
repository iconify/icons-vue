<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="feek_ol5u"/><path class="pydf6sb7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:slipstream" /></template>
<style>
.feek_ol5u {
  d: path("M8.5 15v-3q0-1.5 1.5-1.5L12.5 7H17l3 3.5q1.5 0 1.5 1.5v3Z");
}

.pydf6sb7m {
  d: path("M10 16.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm6.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM2.5 8.5q2 0 3.25 1M3.25 12h2.5M2.5 15.5q2 0 3.25-1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
