<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="fhcsjwttb"/><path class="jo4rfcc8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:on-time-sharp" /></template>
<style>
.fhcsjwttb {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

.jo4rfcc8i {
  d: path("M10 2.75h4m-2 0v3M17.5 8l1.75-1.75M9 13.75l2 2l4-4.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
