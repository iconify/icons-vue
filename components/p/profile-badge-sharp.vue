<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rknchmb5r"/><path class="h2nzvge9l"/><circle class="k-pua8b2l"/><path class="b3ocf71ya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:profile-badge-sharp" /></template>
<style>
.b3ocf71ya {
  d: path("m17 11.75l-.75 3l2-1l2 1l-.75-3");
}

.h2nzvge9l {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75z");
}

.k-pua8b2l {
  cx: 18.25px;
  cy: 9.25px;
  r: 2.5px;
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
