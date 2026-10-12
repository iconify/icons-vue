<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="r6uvok62f"/><circle class="hsg5pubci"/><path class="hgj314i_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-ring-heart-sharp" /></template>
<style>
.hgj314i_g {
  d: path("m9 4.5l3-2.99l3 2.99");
}

.hsg5pubci {
  cx: 12px;
  cy: 14px;
  r: 4.5px;
}

.r6uvok62f {
  cx: 12px;
  cy: 14px;
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
