<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e9vgbdcse"/><path class="u4f303mhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swot-sharp" /></template>
<style>
.e9vgbdcse {
  d: path("M2.75 2.75h8v8h-8zm10.5 0h8v8h-8zm-10.5 10.5h8v8h-8zm10.5 0h8v8h-8zm-6.5-8.37v3.75M4.88 6.75h3.75m6.75 0h3.75");
}

.u4f303mhb {
  d: path("M6.75 19.25V15.5M5.12 17l1.63-1.5L8.38 17m8.87-1.5v2.25m0 1.75v.01");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
