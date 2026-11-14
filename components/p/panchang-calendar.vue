<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="kt8nbeoen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:panchang-calendar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt8nbeoen {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5m-9.5-7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-3.75V4.5m0 8.75v1.25m-3.75-5H7m8.75 0H17m-2.25-2.75L15.5 6m-.75 6.25l.75.75m-6.25-.75L8.5 13m.75-6.25L8.5 6");
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

</style>
