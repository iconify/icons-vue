<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mx0ir3bdi"/><path class="dv7i_bc8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mayor-sash-sharp" /></template>
<style>
.dv7i_bc8i {
  d: path("M4.25 21.25a7.75 7.75 0 0 1 15.5 0Zm3.5-6.75l6.75 6.25");
}

.mx0ir3bdi {
  cx: 12px;
  cy: 6.75px;
  r: 4px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
