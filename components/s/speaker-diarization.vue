<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cnafh2bzb"/><path class="guprb7bcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:speaker-diarization" /></template>
<style>
.cnafh2bzb {
  d: path("M4.5 4H10a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H7l-2.5 2.5V15a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2M17 9h2.5a2 2 0 0 1 2 2v8L19 16.5h-2a2 2 0 0 1-2-2V11a2 2 0 0 1 2-2");
}

.guprb7bcz {
  d: path("M5.25 9.5c.75-1.75 1.5-1.75 2 0s1.25 1.75 2 0M17 12.75c.5-1 1-1 1.25 0s.75 1 1.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
