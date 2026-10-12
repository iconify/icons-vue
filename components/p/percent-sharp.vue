<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="y4edlk8up"/><circle class="ekwj1i_0m"/><path class="fyjv9jblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:percent-sharp" /></template>
<style>
.ekwj1i_0m {
  cx: 17px;
  cy: 17px;
  r: 2.75px;
}

.fyjv9jblo {
  d: path("m18.75 5.25l-13.5 13.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4edlk8up {
  cx: 7px;
  cy: 7px;
  r: 2.75px;
}

</style>
