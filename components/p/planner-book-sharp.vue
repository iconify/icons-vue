<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="psizqf3sa"/><path class="pxf9mqb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:planner-book-sharp" /></template>
<style>
.psizqf3sa {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3.5 0v18.5");
}

.pxf9mqb_m {
  d: path("M11.5 2.75H15v7L13.25 8.5L11.5 9.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
