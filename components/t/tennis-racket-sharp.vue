<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u0n2nfbgy"/><circle class="b2vzpybzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tennis-racket-sharp" /></template>
<style>
.b2vzpybzx {
  cx: 18.5px;
  cy: 18.5px;
  r: 2px;
}

.u0n2nfbgy {
  d: path("M17.59 3.88a6.25 5-35 1 1-7.18 10.24a6.25 5-35 1 1 7.18-10.24Zm0 0l-7.18 10.24M9.9 6.13l8.2 5.74m-7.69 2.25l-1.72 2.46m-.41-.29l.82.58l.82.57l-.57.82l-1.44 2.04l-.57.82l-.82-.57l-.82-.58l-.82-.57l.57-.82l1.44-2.04l.57-.82z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
