<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rknchmb5r"/><path class="h2nzvge9l"/><circle class="joko_go6x"/><path class="g_h0r_20e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-key-sharp" /></template>
<style>
.g_h0r_20e {
  d: path("M18.66 8.41L21.25 11m0 0L20 12.25m-.4-2.9l-1 1");
}

.h2nzvge9l {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75z");
}

.joko_go6x {
  cx: 17.25px;
  cy: 7px;
  r: 2px;
}

.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
