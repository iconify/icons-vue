<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x906v9bos"/><path class="kbc6v7brq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:teleprompter-sharp" /></template>
<style>
.kbc6v7brq {
  d: path("M17 13V7m-1.75 1.75L17 7l1.75 1.75m-6.75 8v4.5m-3.75 0h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x906v9bos {
  d: path("M2.75 2.75h18.5v14H2.75zM6 7h7M6 9.75h7M6 12.5h4.5");
}

</style>
