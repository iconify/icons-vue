<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fiihs3-8t"/><path class="lm782rbia"/><circle class="cret48b_z"/><path class="tgvveba2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:today-sharp" /></template>
<style>
.cret48b_z {
  cx: 12px;
  cy: 15.25px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fiihs3-8t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.25h16.5v15H3.75zm0 4.75h16.5M8 2.75v4.5m8-4.5v4.5");
}

.lm782rbia {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15.25h.01");
}

.tgvveba2o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 15.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
