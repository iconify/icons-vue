<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v90gbqbox"/><path class="mzwke6bta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:solar-eclipse-sharp" /></template>
<style>
.mzwke6bta {
  d: path("M19.99 9.09a8.5 8.5 0 1 1-5.08-5.08m3.81-1.23l.3 2.2l2.2.3l-2.2.3l-.3 2.2l-.3-2.2l-2.2-.3l2.2-.3z");
}

.v90gbqbox {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
