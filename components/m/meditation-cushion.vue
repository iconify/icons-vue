<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dupv38a4z"/><path class="o2e0w1bey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meditation-cushion" /></template>
<style>
.dupv38a4z {
  d: path("M3 17h18c.75-6-3-9.5-9-9.5S2.25 11 3 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2e0w1bey {
  d: path("M6 13q6 1.75 12 0");
}

</style>
