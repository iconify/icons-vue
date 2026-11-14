<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy9la2w0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-park" /></template>
<style>
.hy9la2w0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 4h10.75A2.625 2.625 0 0 1 20 6.625v.75A2.625 2.625 0 0 1 17.375 10H6.625A2.625 2.625 0 0 1 4 7.375v-.75A2.625 2.625 0 0 1 6.625 4M4 13h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 16H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 13m2.5-3v3M5 16v4m12.5-10v3m1.5 3v4");
}

</style>
