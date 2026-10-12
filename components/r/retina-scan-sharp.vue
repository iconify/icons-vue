<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dpp15ybdm"/><circle class="pfpt48slt"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retina-scan-sharp" /></template>
<style>
.dpp15ybdm {
  d: path("M3.75 8V3.75H8m8 0h4.25V8m0 8v4.25H16m-8 0H3.75V16");
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.pfpt48slt {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
