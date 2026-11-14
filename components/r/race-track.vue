<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="agxsf6wer"/><path class="sgpwnvbza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:race-track" /></template>
<style>
.agxsf6wer {
  d: path("M2.5 15a9.5 5.5 0 1 0 19 0a9.5 5.5 0 1 0-19 0M12 9.5v-7m1.5 0H16A1.5 1.5 0 0 1 17.5 4v1A1.5 1.5 0 0 1 16 6.5h-2.5A1.5 1.5 0 0 1 12 5V4a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sgpwnvbza {
  d: path("M7 15a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0");
}

</style>
