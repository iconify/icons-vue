<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rknchmb5r"/><path class="tnc52_0yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-vip-sharp" /></template>
<style>
.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

.tnc52_0yt {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zM16.23 8.67l.79-1.09l.23-.33H20l.23.33l.79 1.09l.23.33l-.24.32l-2.17 2.86l-.24.32l-.24-.32l-2.12-2.86L16 9z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
