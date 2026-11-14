<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wsr5fgb5v"/><path class="shdwwuy4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sim-adapter" /></template>
<style>
.shdwwuy4t {
  d: path("M7.5 11h5l3 3v4.5h-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsr5fgb5v {
  d: path("M4.5 2.5h10l5 5v14h-15Z");
}

</style>
