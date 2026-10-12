<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tdcx0rb0t"/><path class="xbbzq2yxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-switch-sharp" /></template>
<style>
.tdcx0rb0t {
  d: path("M3.25 8.25h12.5v13H3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbbzq2yxs {
  d: path("M7 11.25h5v7H7zm0 3.5h5m3.58-8.97l2.246.394l.394 2.246M16.1 2.83a6.25 6.25 0 0 1 5.07 5.07");
}

</style>
