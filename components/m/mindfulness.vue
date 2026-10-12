<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uvozaq6fn"/><path class="y6q0vdbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mindfulness" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uvozaq6fn {
  d: path("M15.5 21.25v-3h1.75a1.5 1.5 0 0 0 1.5-1.5V14.5l1.5-.6a.6.6 0 0 0 .25-.9l-1.75-2.75a7.25 7.25 0 1 0-12 6v5Z");
}

.y6q0vdbik {
  d: path("M11.5 6.75c1.3 1.05 1.9 2.35 1.9 3.65s-.6 2.4-1.9 3.1c-1.3-.7-1.9-1.8-1.9-3.1s.6-2.6 1.9-3.65");
}

</style>
