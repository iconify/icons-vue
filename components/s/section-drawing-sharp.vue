<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="neheeeyuc"/><path class="jiwr6wx4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:section-drawing-sharp" /></template>
<style>
.jiwr6wx4f {
  d: path("M8.5 16.5v-9h7v9m-7-4.5h7");
}

.neheeeyuc {
  d: path("M2.75 2.75h18.5v18.5H2.75zM6 16.5h12M7.5 19l2-2.5M11 19l2-2.5m1.5 2.5l2-2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
