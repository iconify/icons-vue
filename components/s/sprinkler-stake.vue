<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-x3d1bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprinkler-stake" /></template>
<style>
.q-x3d1bvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 8h5.5v3.5h-5.5Zm1.25 3.5h3l-1.5 10ZM3 18h18M10 5Q6.5 1.5 3 6.5M14 5q3.5-3.5 7 1.5");
}

</style>
