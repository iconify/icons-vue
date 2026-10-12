<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="r9rp8qjbt"/><path class="yzp3cabcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tree-view-sharp" /></template>
<style>
.r9rp8qjbt {
  cx: 5px;
  cy: 5.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yzp3cabcz {
  d: path("M5 7.75v11h6.25M5 9.25V12h6.25m-1-6.75h10m-6 6.75h6m-6 6.75h6");
}

</style>
