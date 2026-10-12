<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tqh305-3q"/><path class="vtjiqfpsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:telescope-observatory-sharp" /></template>
<style>
.tqh305-3q {
  d: path("M4 21.25V12.5a8 8 0 0 1 16 0v8.75Z");
}

.vtjiqfpsv {
  d: path("M10.5 21.25V17h3v4.25m.02-12.54l4.71-4.92l.52-.54l.53.53l1.19 1.19l.53.53l-.52.54l-4.71 4.92l-.52.54l-.53-.53l-1.19-1.19l-.53-.53z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
