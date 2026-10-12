<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="clbhulbjp"/><path class="lizp9hbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nutrition-sharp" /></template>
<style>
.clbhulbjp {
  cx: 9.5px;
  cy: 12px;
  r: 6.75px;
}

.lizp9hbae {
  d: path("M9.5 5.25v13.5m0-6.75h6.75m2.25-8.25v5H21v-5m-1.25 5v11.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
