<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x7vk12b2r"/><path class="waw662eej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quote-compare-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.waw662eej {
  d: path("M14 7h7v6l-3.5 3.5L14 13Z");
}

.x7vk12b2r {
  d: path("M3 7h7v6l-3.5 3.5L3 13Z");
}

</style>
