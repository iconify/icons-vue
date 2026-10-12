<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><path class="kjrslo5sp"/><path class="sheyzobar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spacesuit-sharp" /></template>
<style>
.kjrslo5sp {
  d: path("M8 10.25h9l.57.82l2.36 3.36l.57.82l-.81.58l-.13.09l-.81.58l-.6-.8l-1.05-1.4l-.6-.8v7.75h-3.75l-.22-.97l-.31-1.31L12 18l-.22.97l-.31 1.31l-.22.97H7.5V13.5l-.6.8l-1.05 1.4l-.6.8l-.81-.58l-.13-.09l-.81-.58l.57-.82l2.36-3.36l.57-.82z");
}

.sheyzobar {
  d: path("M10 13h4v2.5h-4z");
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
