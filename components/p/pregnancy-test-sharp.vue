<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="j0vlx6bgz"/><path class="cvvmbgblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pregnancy-test-sharp" /></template>
<style>
.cvvmbgblk {
  d: path("M9.5 7.5h5V14h-5zM12 9.25v3M7 16.5h10");
}

.j0vlx6bgz {
  d: path("M7 2.75h10v18.5H7z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
