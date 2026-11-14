<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8b8wf1ym"/><path class="hp5g1ymeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:new-build" /></template>
<style>
.c8b8wf1ym {
  d: path("m3.579 14.479l3.25-2.925a1.75 1.75 0 0 1 2.342 0l3.25 2.925a1.75 1.75 0 0 1 .579 1.3v3.971a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 3 19.75v-3.971a1.75 1.75 0 0 1 .579-1.3M18.5 21.5v-19m-14 3h17M8 5.5v2m8.5 14h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hp5g1ymeh {
  d: path("M6.5 21.5V18h3v3.5");
}

</style>
