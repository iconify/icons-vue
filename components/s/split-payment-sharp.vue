<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h0lvcc43a"/><path class="g318udbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:split-payment-sharp" /></template>
<style>
.g318udbsp {
  d: path("M5.25 11.5H8.5v2.75H5.25z");
}

.h0lvcc43a {
  d: path("M2.75 5.25h18.5v13.5H2.75zm0 3.5h18.5m-6.75-3.5l-5 13.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
