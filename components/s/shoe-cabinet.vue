<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp5pn0fst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shoe-cabinet" /></template>
<style>
.zp5pn0fst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 11.5h12.75A2.625 2.625 0 0 1 21 14.125v2.25A2.625 2.625 0 0 1 18.375 19H5.625A2.625 2.625 0 0 1 3 16.375v-2.25A2.625 2.625 0 0 1 5.625 11.5M5.5 19v2.5m13-2.5v2.5M6.5 8.75V3.5h4l1 2h3a3.25 3.25 0 0 1 3.25 3.25ZM12 11.5V19");
}

</style>
