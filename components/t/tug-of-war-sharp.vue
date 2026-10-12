<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="x_nrb2b4o"/><path class="c_e9d2t8h"/><circle class="eoe7_1bcb"/><path class="lqhk8ib8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tug-of-war-sharp" /></template>
<style>
.c_e9d2t8h {
  d: path("m5.5 10l2.75 6m0 0l2 5m-2-5L7 21M5.9 10.9L9.25 13");
}

.eoe7_1bcb {
  cx: 19.5px;
  cy: 7.75px;
  r: 1.75px;
}

.lqhk8ib8s {
  d: path("m18.5 10l-2.75 6m0 0l-2 5m2-5L17 21m1.1-10.1L14.75 13M3 13h18m-9-2.5v5");
}

.x_nrb2b4o {
  cx: 4.5px;
  cy: 7.75px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
