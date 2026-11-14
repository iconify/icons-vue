<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zirnbbebd"/><path class="tfi2fmhym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:space-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tfi2fmhym {
  d: path("M6.5 6a5.5 1.5 0 1 0 11 0a5.5 1.5 0 1 0-11 0");
}

.zirnbbebd {
  d: path("M12 21c-2.5-1.5-6-2-9.5-1.5v-8c3.5-.5 7 0 9.5 1.5c2.5-1.5 6-2 9.5-1.5v8c-3.5-.5-7 0-9.5 1.5m0-8v8M9.25 6a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
