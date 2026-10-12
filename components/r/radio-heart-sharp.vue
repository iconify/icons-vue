<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ffgbqnb4v"/><circle class="lgl_seb5t"/><path class="qsd0rsxse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radio-heart-sharp" /></template>
<style>
.ffgbqnb4v {
  d: path("M2.75 8.25h18.5v12H2.75zm4.75 0L12.75 3");
}

.lgl_seb5t {
  cx: 16.25px;
  cy: 14.25px;
  r: 2.5px;
}

.qsd0rsxse {
  d: path("M6.25 12.5h4.5M6.25 16h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
