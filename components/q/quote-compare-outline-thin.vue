<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7vk12b2r"/><path class="waw662eej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quote-compare-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.waw662eej {
  d: path("M14 7h7v6l-3.5 3.5L14 13Z");
}

.x7vk12b2r {
  d: path("M3 7h7v6l-3.5 3.5L3 13Z");
}

</style>
