<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rz6q0vb8a"/><path class="vssnpkb6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skeleton-full" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rz6q0vb8a {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2v8m-6.5.5l2-6h9l2 6");
}

.vssnpkb6r {
  d: path("m8.5 21.5l1.5-7h4l1.5 7m-6-9.75h5");
}

</style>
