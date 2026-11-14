<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cix13btzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-data-centre" /></template>
<style>
.cix13btzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3.5h12.75A2.625 2.625 0 0 1 21 6.125v1.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 7.875v-1.75A2.625 2.625 0 0 1 5.625 3.5m0 10h12.75A2.625 2.625 0 0 1 21 16.125v1.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 17.875v-1.75A2.625 2.625 0 0 1 5.625 13.5M7 7h.01M11 7h6M7 17h.01M11 17h6");
}

</style>
