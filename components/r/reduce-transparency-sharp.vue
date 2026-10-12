<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gfwfgvbhl"/><path class="imq4_mabh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reduce-transparency-sharp" /></template>
<style>
.gfwfgvbhl {
  d: path("M10.5 10.5h10.75v10.75H10.5z");
}

.imq4_mabh {
  d: path("M2.75 2.75h12v12h-12zM6 9.5L9.5 6M6 13l7-7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
