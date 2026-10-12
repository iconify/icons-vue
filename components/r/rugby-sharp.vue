<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nbvd3dxpo"/><path class="pudhj47xv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rugby-sharp" /></template>
<style>
.nbvd3dxpo {
  d: path("M4.63 17.16A9 5.5-35 1 1 19.37 6.84A9 5.5-35 1 1 4.63 17.16Z");
}

.pudhj47xv {
  d: path("m7.49 15.15l1.64-1.14l-.72-1.02l1.44 2.04l-.72-1.02L12 12l-.72-1.02l1.44 2.04L12 12l2.87-2.01l-.72-1.02l1.44 2.04l-.72-1.02l1.64-1.14");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
