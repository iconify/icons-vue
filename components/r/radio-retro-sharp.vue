<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qn095d5nw"/><circle class="fhgqn2bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radio-retro-sharp" /></template>
<style>
.fhgqn2bmk {
  cx: 16.25px;
  cy: 14.5px;
  r: 2px;
}

.qn095d5nw {
  d: path("M4.75 21.25h-2V12c0-4.5 4.15-8 9.25-8s9.25 3.5 9.25 8v9.25h-2Zm2-8.75v5.25M9.25 11v6.75m2.5-6.75v6.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
