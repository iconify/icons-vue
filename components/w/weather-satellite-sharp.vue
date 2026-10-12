<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l3czwq2ei"/><path class="kx5d_cc4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:weather-satellite-sharp" /></template>
<style>
.kx5d_cc4c {
  d: path("m9.8 5.21l1.69-.62l.56-.2l.21.56l1.3 3.57l.2.57l-.56.2l-1.69.62l-.56.2l-.21-.56l-1.3-3.57l-.2-.57zm.69 15.99a2.5 2.5 0 0 1-.34-4.99a3.6 3.6 0 0 1 6.66-.86a2.82 2.82 0 0 1-.37 5.85Z");
}

.l3czwq2ei {
  d: path("m13.02 4.84l4.22-1.54l.71-.26l.26.71l.68 1.87l.26.71l-.71.26l-4.23 1.53l-.7.26l-.26-.7l-.68-1.88l-.26-.71zM4.56 7.91l4.23-1.53l.7-.26l.26.7l.68 1.88l.26.71l-.71.25l-4.22 1.54l-.71.26l-.26-.71l-.68-1.87l-.26-.71z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
