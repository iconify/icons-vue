<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="akvay5xpc"/><path class="r3my3obvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sun-haze-sharp" /></template>
<style>
.akvay5xpc {
  cx: 12px;
  cy: 9.5px;
  r: 4px;
}

.r3my3obvz {
  d: path("M6.5 9.5h-1m2.61-3.89L7.4 4.9M12 4V3m3.89 2.61l.71-.71m.9 4.6h1M3.75 17h16.5m-13.5 3.75h10.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
