<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="hp1fi4b9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:respirator-required-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hp1fi4b9p {
  d: path("M7 11.5c1.75-1 3.25-1.5 5-1.5s3.25.5 5 1.5v2c0 2.5-2.5 4.5-5 4.5s-5-2-5-4.5Zm3.75 2.75h2.5m-6.25-2L5.75 11M17 12.25L18.25 11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
