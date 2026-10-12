<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ll76k-wyk"/><path class="qeq6gop0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-waving-sharp" /></template>
<style>
.ll76k-wyk {
  cx: 10px;
  cy: 6.25px;
  r: 2px;
}

.qeq6gop0s {
  d: path("M10 11v5.25m-2.25 5l2.25-5l2.25 5M10 12l-2.75 3.5M10 12l3.75-1.5L15 6.25m3.25-3l1.846 1.422L20 7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
