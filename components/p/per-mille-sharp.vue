<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="iatyddcmd"/><circle class="f3klz9dak"/><circle class="rctbt0bba"/><path class="l-a3p-biv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:per-mille-sharp" /></template>
<style>
.f3klz9dak {
  cx: 12.25px;
  cy: 17.5px;
  r: 2.25px;
}

.iatyddcmd {
  cx: 5.75px;
  cy: 6.75px;
  r: 2.25px;
}

.l-a3p-biv {
  d: path("m16.75 3.75l-13 16.5");
}

.rctbt0bba {
  cx: 18.75px;
  cy: 17.5px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
