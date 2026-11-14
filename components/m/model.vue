<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pc88xhzvh"/><path class="fv5pcnpmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:model" /></template>
<style>
.fv5pcnpmp {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pc88xhzvh {
  d: path("m12.873 3.003l6.5 3.742a1.75 1.75 0 0 1 .877 1.517v7.476a1.75 1.75 0 0 1-.877 1.517l-6.5 3.742a1.75 1.75 0 0 1-1.746 0l-6.5-3.742a1.75 1.75 0 0 1-.877-1.517V8.262a1.75 1.75 0 0 1 .877-1.517l6.5-3.742a1.75 1.75 0 0 1 1.746 0M3.75 7.25l6.5 3.75m10-3.75L13.75 11M12 14v7.5");
}

</style>
