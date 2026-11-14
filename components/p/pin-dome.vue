<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uph9ekb-n"/><path class="f5-wzybro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-dome" /></template>
<style>
.f5-wzybro {
  d: path("M10 20.5V17a2 2 0 0 1 4 0v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uph9ekb-n {
  d: path("M5 12a7 7 0 0 1 14 0M3.5 12h17v8.5h-17ZM12 2.5V5");
}

</style>
