<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u-gkr4b6f"/><path class="he1evqb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pie-slice-sharp" /></template>
<style>
.he1evqb6c {
  d: path("M8.75 6.82a7 7 0 1 0 7.93 7.93");
}

.u-gkr4b6f {
  d: path("M12 11.5V2.75a8.75 8.75 0 0 1 8.75 8.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
