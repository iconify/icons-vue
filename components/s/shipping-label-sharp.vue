<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b_njy0z2n"/><path class="qw1o8ibgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shipping-label-sharp" /></template>
<style>
.b_njy0z2n {
  d: path("M2.75 4.75h18.5v14.5H2.75zm3 3.5h5.5m-5.5 3h3.5m-3.5 4h12.5");
}

.qw1o8ibgk {
  d: path("M14.25 7.25h4v4h-4z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
