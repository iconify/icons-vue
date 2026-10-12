<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="syxmtqd-u"/><path class="uuyeooblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waiting-area-sharp" /></template>
<style>
.syxmtqd-u {
  cx: 17.5px;
  cy: 6px;
  r: 3.25px;
}

.uuyeooblb {
  d: path("M17.5 4.5V6l1 1M3.25 11.5h7V18h-7zm10.5 0h7V18h-7zm-11 6.5h18.5M5 18v3.25M19 18v3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
