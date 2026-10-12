<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gx1xg5ykg"/><path class="d92z1c-_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:risk-matrix-sharp" /></template>
<style>
.d92z1c-_p {
  d: path("M5.75 2.75h6v6h-6zm9.5 0h6v6h-6zm-9.5 9.5h6v6h-6zm9.5 0h6v6h-6zm3-7.75V6m0 1.25v.01");
}

.gx1xg5ykg {
  d: path("M2.75 2.75v18.5h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
