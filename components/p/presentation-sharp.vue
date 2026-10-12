<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cgzof0bky"/><path class="ijhqdybvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:presentation-sharp" /></template>
<style>
.cgzof0bky {
  d: path("M2.75 3.25h18.5v12.5H2.75z");
}

.ijhqdybvf {
  d: path("m7 11.75l3-3l2.5 2l4.5-4.5m-5 9.5v3m-3.5 2.5l3.5-2.5l3.5 2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
