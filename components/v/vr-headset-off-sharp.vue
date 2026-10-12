<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="le8mpsbtv"/><path class="q7yktwbvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vr-headset-off-sharp" /></template>
<style>
.le8mpsbtv {
  d: path("M7 7.25V4h10v3.25m-12 0h16V17h-6.005l-.445-.67l-1.3-1.95L12 12.496l-1.25 1.884l-1.3 1.95l-.445.67H3V7.25z");
}

.q7yktwbvr {
  d: path("M6 9.75h12v2.5H6z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
