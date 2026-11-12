<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="hllyxzboc"/><path class="mj_6ev9oe"/><path class="v9bhxmb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-close-linear" /></template>
<style>
.hllyxzboc {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mj_6ev9oe {
  d: path("M20 20L22 22");
}

.v9bhxmb2h {
  d: path("M9.73223 9.73185L11.5 11.4996M11.5 11.4996L13.2678 13.2674M11.5 11.4996L9.73223 13.2674M11.5 11.4996L13.2678 9.73185");
}

</style>
