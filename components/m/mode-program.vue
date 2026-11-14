<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aok1dqold"/><path class="gf6ja9xsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mode-program" /></template>
<style>
.aok1dqold {
  d: path("M4.5 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0m6.987-11.5h1.026a.513.513 0 0 1 .362.875a1.237 1.237 0 0 1-1.75 0a.513.513 0 0 1 .362-.875m-1.737 8V18");
}

.gf6ja9xsh {
  d: path("M9.75 10.5h2.5a2.25 2.25 0 0 1 0 4.5h-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
