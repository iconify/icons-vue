<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="c70vv4bjr"/><path class="dh2r74irw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plunger-sharp" /></template>
<style>
.c70vv4bjr {
  cx: 12px;
  cy: 4.75px;
  r: 1.75px;
}

.dh2r74irw {
  d: path("M12 6.5v5.25m-1.5 0h3c3 .5 4.5 3 3.75 5.75c-.3 1.2-.2 2.4 2.25 3.75h-15c2.45-1.35 2.55-2.55 2.25-3.75c-.75-2.75.75-5.25 3.75-5.75Zm-7.75 9.5h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
