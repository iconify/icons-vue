<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gf3mmwbgk"/><path class="c9_k57e9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mop-bucket" /></template>
<style>
.c9_k57e9e {
  d: path("M5.75 11.25c1.75-1 3.75-1 5.75 0s4 1 6.25-.25");
}

.gf3mmwbgk {
  d: path("M6.005 8h11.99a1.75 1.75 0 0 1 1.734 1.986l-1.023 7.5A1.75 1.75 0 0 1 16.972 19H7.028a1.75 1.75 0 0 1-1.734-1.514l-1.023-7.5A1.75 1.75 0 0 1 6.005 8M5 8a7 5 0 0 1 14 0M6.5 20.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m8.5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
