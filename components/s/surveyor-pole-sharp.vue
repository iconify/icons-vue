<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="inf4ddb2s"/><path class="o6a500beq"/><path class="huq-91b4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:surveyor-pole-sharp" /></template>
<style>
.huq-91b4d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25v2.5m-1.25 0h2.5v9.5h-2.5zm0 3.25h2.5m-2.5 3.25h2.5");
}

.inf4ddb2s {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
