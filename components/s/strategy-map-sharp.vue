<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wvxidbnsz"/><circle class="x2ld5m6gw"/><path class="av4uq-txz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:strategy-map-sharp" /></template>
<style>
.av4uq-txz {
  d: path("M10.75 5.5H18v14m-2.75-2.75L18 19.5l2.75-2.75");
}

.wvxidbnsz {
  d: path("m3.75 3.75l3.5 3.5m0-3.5l-3.5 3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2ld5m6gw {
  cx: 5.5px;
  cy: 17.75px;
  r: 2.75px;
}

</style>
