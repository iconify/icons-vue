<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jdo7z8-qu"/><path class="w-bnpitut"/><path class="ws24-9bwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:paintbrush-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdo7z8-qu {
  d: path("m3 21 9 -9");
}

.w-bnpitut {
  d: path("m12 12 3 -3 4 4 -3 3Z");
}

.ws24-9bwu {
  d: path("m19 13 2 -2 -4 -4 -2 2Z");
}

</style>
