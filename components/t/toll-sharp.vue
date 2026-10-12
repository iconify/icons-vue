<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gwiv1cb4l"/><path class="a0ljzhbqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toll-sharp" /></template>
<style>
.a0ljzhbqy {
  d: path("M6.5 8.25H9v3.5H6.5Zm7 5h7.75");
}

.gwiv1cb4l {
  d: path("M3.75 4.75h8v16.5h-8z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
