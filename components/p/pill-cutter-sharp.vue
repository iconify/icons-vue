<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m9rgx858q"/><path class="y_rsoy2st"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pill-cutter-sharp" /></template>
<style>
.m9rgx858q {
  d: path("M20.28 10.02L4.22 6.23L3.25 6V3l.97.23l16.06 3.79l.97.23v3zM2.75 12.5h18.5v8.25H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_rsoy2st {
  d: path("M8.75 14.75h6.5v3.75h-6.5zm3.25 0v3.75");
}

</style>
