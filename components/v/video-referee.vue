<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uny270b5p"/><path class="le6wmbbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-referee" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.le6wmbbbe {
  d: path("M9.5 12.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7 20.5c0-2.25 2.25-3 5-3s5 .75 5 3");
}

.uny270b5p {
  d: path("M4.5 7h15a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2m4-4.25L12 7l3.5-4.25");
}

</style>
