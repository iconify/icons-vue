<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-c3k92gq"/><path class="hd2fz_b3w"/><path class="u7gar7qdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:villa" /></template>
<style>
.hd2fz_b3w {
  d: path("M3.5 7.5v14h17v-14M3.5 3h17M6 3v2.5M12 3v2.5M18 3v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u7gar7qdg {
  d: path("M5 15v-3.5a1.5 1.5 0 0 1 3 0V15Zm11 0v-3.5a1.5 1.5 0 0 1 3 0V15Zm-5.75 6.5V15a1.75 1.75 0 0 1 3.5 0v6.5");
}

.x-c3k92gq {
  fill: currentColor;
  d: path("M3.5 5.5h17a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>
