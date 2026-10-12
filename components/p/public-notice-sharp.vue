<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t9l8gwb1y"/><path class="x0yvusb1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:public-notice-sharp" /></template>
<style>
.t9l8gwb1y {
  d: path("M2.75 3.25h18.5v12H2.75zm3.75 12v6m11-6v6");
}

.x0yvusb1f {
  d: path("M8.25 5.75h7.5v7h-7.5zm2 2.5h3.5m-3.5 2.25h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
