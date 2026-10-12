<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="r57sxrb_d"/><circle class="lf940mbnz"/><circle class="ap-miurjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:more-vertical-sharp" /></template>
<style>
.ap-miurjd {
  cx: 12px;
  cy: 19.25px;
  r: 1.25px;
}

.lf940mbnz {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
}

.r57sxrb_d {
  cx: 12px;
  cy: 4.75px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
