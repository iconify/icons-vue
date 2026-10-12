<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ssznpn3eo"/><path class="nv-2zsecj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:property-search-sharp" /></template>
<style>
.nv-2zsecj {
  d: path("m15.4 15.4l5.85 5.85M7 12.65v-2.9l.46-.38l2.08-1.74l.46-.38l.46.38l2.08 1.74l.46.38v3.5H7z");
}

.ssznpn3eo {
  cx: 10px;
  cy: 10px;
  r: 7.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
