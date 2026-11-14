<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0nhrcrde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pruning-rose" /></template>
<style>
.o0nhrcrde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5q2.25 2 4-1q1.75 3 4 1V7a4 4 0 0 1-8 0Zm4 7.5v10.5m0-4l1.699-.85M13.5 16l8 3.5m-5.5-6l3.5 8");
}

</style>
