<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfroi4bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radio-telescope-sharp" /></template>
<style>
.xfroi4bsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.75a7.5 4.5-30 0 0 13-7.5Zm8.75.15l-4-6.9m3.75 7.75L9 20.5m3.5-8.75L16 20.5m-10.5 0h13");
}

</style>
