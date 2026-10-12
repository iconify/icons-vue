<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rknchmb5r"/><path class="tgrk4ac-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:users-link-sharp" /></template>
<style>
.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

.tgrk4ac-l {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zm12.5-11V6H20v3.25m0 3v3.25h-3.5v-3.25m1.75-3.75V13");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
