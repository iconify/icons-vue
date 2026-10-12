<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bjd3m4byv"/><circle class="v0gbo5fpj"/><circle class="rslbrvbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skateboard-sharp" /></template>
<style>
.bjd3m4byv {
  d: path("M2.75 10.5V9h2.5l1.5 1.25h10.5L18.75 9h2.5v1.5c0 1.75-1.5 3.25-3.25 3.25H2.75z");
}

.rslbrvbax {
  cx: 17px;
  cy: 18.75px;
  r: 2.25px;
}

.v0gbo5fpj {
  cx: 7px;
  cy: 18.75px;
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
