<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v9q4yubzo"/><path class="v2rafgywz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:puddle-sharp" /></template>
<style>
.v2rafgywz {
  d: path("M8.5 17.25a3.5 1 0 0 0 7 0M11.72 3.41L9.79 7.09a2.5 2.5 0 1 0 4.42 0l-1.93-3.68l-.28-.53z");
}

.v9q4yubzo {
  d: path("M2.75 17.5a9.25 3.75 0 1 0 18.5 0a9.25 3.75 0 1 0-18.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
