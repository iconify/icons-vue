<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="gg525p0gt"/><path class="ho1z23b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-puzzle-sharp" /></template>
<style>
.gg525p0gt {
  cx: 12px;
  cy: 7.25px;
  r: 4px;
}

.ho1z23b4s {
  d: path("M5 20.25h15v-1c0-3-3.6-5.25-8-5.25s-8 2.25-8 5.25v1z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
