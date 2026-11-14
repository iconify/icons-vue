<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rrw_6nbku"/><path class="k2jt89bee"/><path class="c_ioktuuv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-and-compass" /></template>
<style>
.c_ioktuuv {
  d: path("M17 14.25L18.25 17L17 19.75L15.75 17Z");
}

.k2jt89bee {
  d: path("M12 17a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.rrw_6nbku {
  d: path("M9.239 16.913L8 16.5l-5.5 2v-13l5.5-2l6 2l5.5-2v6.071M8 3.5v13m6-11v4.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
