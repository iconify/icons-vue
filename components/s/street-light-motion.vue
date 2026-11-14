<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tz7_7eb0h"/><path class="egqwlm6cz"/><path class="wm6xrqbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:street-light-motion" /></template>
<style>
.egqwlm6cz {
  fill: currentColor;
  d: path("M17.25 13.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tz7_7eb0h {
  d: path("M5 21.5V8a4.5 4.5 0 0 1 4.5-4.5H11m1.177-.5h3.646a1.036 1.036 0 0 1 .927 1.5l-.335.671A1.5 1.5 0 0 1 15.073 6h-2.146a1.5 1.5 0 0 1-1.342-.829L11.25 4.5a1.036 1.036 0 0 1 .927-1.5M3 21.5h4");
}

.wm6xrqbhl {
  d: path("m18 16l-1 3m0 0l-1.5 2.5M17 19l2 2.5m-3.5-4L18 16l2 1.5");
}

</style>
