<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jl4903ezj"/><path class="yut2xo4dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ssl-certificate-sharp" /></template>
<style>
.jl4903ezj {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yut2xo4dj {
  d: path("m8.5 14.73l-1.25 6.52l4.75-2.5l4.75 2.5l-1.25-6.52m-6-6.23h5v4h-5zm1 0v-3h3v3");
}

</style>
