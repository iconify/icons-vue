<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mohe24bzn"/><path class="b6p2qf15b"/><path class="bythc1b6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:model-version-sharp" /></template>
<style>
.b6p2qf15b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.9L9 9.05l5.5-3.15M9 9.05v6.2m4.75.5H18l.74.68l1.52 1.39l.74.68l-.74.68l-1.52 1.39l-.74.68h-5.25v-5.5z");
}

.bythc1b6v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 18.5h.01");
}

.mohe24bzn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.87 3.25l3.76 2.15l.87.5v6.2l-.87.5l-3.76 2.15l-.87.5l-.87-.5l-3.76-2.15l-.87-.5V5.9l.87-.5l3.76-2.15l.87-.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
