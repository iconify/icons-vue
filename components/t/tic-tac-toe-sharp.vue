<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s0oiepv6v"/><circle class="e1_x4r67w"/><path class="keeb62bzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tic-tac-toe-sharp" /></template>
<style>
.e1_x4r67w {
  cx: 4.75px;
  cy: 4.75px;
  r: 2px;
}

.keeb62bzb {
  d: path("m17.25 17.25l3 3m0-3l-3 3");
}

.s0oiepv6v {
  d: path("M9 3v18m6-18v18M3 9h18M3 15h18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
