<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pjes74b9i"/><path class="joz1zabqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rug-sharp" /></template>
<style>
.joz1zabqp {
  d: path("m12 8.5l3.5 3.5l-3.5 3.5L8.5 12ZM2.75 8h2m-2 4h2m-2 4h2m14.5-8h2m-2 4h2m-2 4h2");
}

.pjes74b9i {
  d: path("M4.75 5.25h14.5v13.5H4.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
