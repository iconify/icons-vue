<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a977idc5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rear-fog-light" /></template>
<style>
.a977idc5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6c-4.25 0-7 2.5-7 6s2.75 6 7 6Zm3 2h7m-7 4h7m-7 4h7M17 5.5c-1.25 2 1.25 4 0 6.5s1.25 4.5 0 6.5");
}

</style>
