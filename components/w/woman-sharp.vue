<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="cypi79q4s"/><path class="d0o9tibdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:woman-sharp" /></template>
<style>
.cypi79q4s {
  cx: 12px;
  cy: 9px;
  r: 3.25px;
}

.d0o9tibdg {
  d: path("M5 21.25h14.75v-.75c0-3.2-3.5-5.5-7.75-5.5s-7.75 2.3-7.75 5.5v.75zM8.88 3.59A6.25 6.25 0 0 0 5.75 9c0 2.25.1 4 .5 5.25m8.87-10.66A6.25 6.25 0 0 1 18.25 9c0 2.25-.1 4-.5 5.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
