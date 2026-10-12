<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y-xauh0_k"/><path class="u9o849bfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wide-door-sharp" /></template>
<style>
.u9o849bfm {
  d: path("M7 12h10m-8-2l-2 2l2 2m6-4l2 2l-2 2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-xauh0_k {
  d: path("M3.75 21.25V2.75h16.5v18.5m-17.5 0h18.5");
}

</style>
