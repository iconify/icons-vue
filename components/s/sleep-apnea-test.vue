<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yro2r43sv"/><path class="cy5p6abng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sleep-apnea-test" /></template>
<style>
.cy5p6abng {
  d: path("M10.75 9h2.5A1.75 1.75 0 0 1 15 10.75v1.5A1.75 1.75 0 0 1 13.25 14h-2.5A1.75 1.75 0 0 1 9 12.25v-1.5A1.75 1.75 0 0 1 10.75 9m9 5.25c-2.5.25-4.5 2-4.5 4.25c0 1.75 1.5 3.25 3.5 3.25c1.5 0 2.5-.75 3-1.75c-2.5 0-4-1.75-3.5-3.75c.25-1 .75-1.5 1.5-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yro2r43sv {
  d: path("M9.5 2.5c0 1.75-1.25 2.5-3 3L5 6c-1.25.5-1.75 1.25-1.5 2.5l2.25 5c.25 1-.5 4-.5 8h8.014m5.888-10.005L20.5 8.5c.25-1.25-.25-2-1.5-2.5l-1.5-.5c-1.75-.5-3-1.25-3-3m-9 9H9m6 0h3.5");
}

</style>
