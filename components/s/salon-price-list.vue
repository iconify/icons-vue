<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r_i533bfi"/><path class="ogqc3xmjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:salon-price-list" /></template>
<style>
.ogqc3xmjh {
  d: path("M7.5 2.5h5v3h-5Zm-1 7.5h7m-7 4H11m3.5 4l2.25-3h4.75v6h-4.75Z");
}

.r_i533bfi {
  d: path("M13.3 21H3V3.5h14v8.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
