<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mae_cfb_s"/><path class="h_9l67buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-fold-sharp" /></template>
<style>
.h_9l67buq {
  d: path("M20 14.5h-5.5v6.25l.53-.53l5.19-5.19l.53-.53zM6.5 17.25c1.75-2.5 1.25-5 4-5.75s3.75-2 4.5-3.25m0 0l2.5-1.75");
}

.mae_cfb_s {
  d: path("M4.75 3.25h16V14.5l-1.06 1.06l-4.13 4.13l-1.06 1.06H3.25V3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
