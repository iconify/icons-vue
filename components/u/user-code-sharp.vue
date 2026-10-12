<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rknchmb5r"/><path class="fl8yz3bka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-code-sharp" /></template>
<style>
.fl8yz3bka {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zm13.25-12L15.5 10.5l1.75 2.25m2.25-4.5l1.75 2.25l-1.75 2.25");
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
