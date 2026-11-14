<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vmi1h-b1x"/><path class="y4vrbebce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swimmer-backstroke" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vmi1h-b1x {
  d: path("M3 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m7.5 2H21");
}

.y4vrbebce {
  d: path("M12.5 13c0-7-6.5-9-10-6.5m0 11q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
