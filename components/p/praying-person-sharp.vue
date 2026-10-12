<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="eoenbp1iq"/><path class="u8xnuhq8x"/><path class="i9lue-apj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:praying-person-sharp" /></template>
<style>
.eoenbp1iq {
  cx: 9.5px;
  cy: 4.75px;
  r: 2px;
}

.i9lue-apj {
  d: path("m9.5 10.5l3 3.25L14.75 9");
}

.u8xnuhq8x {
  d: path("M9.5 8.75v9H19v3.5H5.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
