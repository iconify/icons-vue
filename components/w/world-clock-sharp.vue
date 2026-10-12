<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mdswc-b6o"/><path class="yj4rhqsqh"/><circle class="req4htxyv"/><path class="eseyp7btj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:world-clock-sharp" /></template>
<style>
.eseyp7btj {
  d: path("M15.5 12.5v3l-2 1.75");
}

.mdswc-b6o {
  cx: 9px;
  cy: 9px;
  r: 6.25px;
}

.req4htxyv {
  cx: 15.5px;
  cy: 15.5px;
  r: 5.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yj4rhqsqh {
  d: path("M9 5.5V9h2.5");
}

</style>
