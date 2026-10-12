<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><circle class="lth1vpd0k"/><circle class="z4na1z2mr"/><path class="u1b6yhbql"/><path class="rclv5q5tw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:study-group-sharp" /></template>
<style>
.lth1vpd0k {
  cx: 5.25px;
  cy: 8.75px;
  r: 2px;
}

.rclv5q5tw {
  d: path("m12 13.25l-2.312-1.445l-2.938.445v7.5c1.65-.25 3.65 0 5.25 1c1.6-1 3.6-1.25 5.25-1v-7.5l-2.938-.445zm0 0v7.5");
}

.u1b6yhbql {
  d: path("M2.75 16.25v-.5A3 3 0 0 1 7 13m14.25 3.25v-.5A3 3 0 0 0 17 13");
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4na1z2mr {
  cx: 18.75px;
  cy: 8.75px;
  r: 2px;
}

</style>
