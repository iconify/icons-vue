<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp9crj-vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ppe-kit" /></template>
<style>
.yp9crj-vf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12v7.5c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V12Zm0 0l1.75-2.5M21 12l-1.75-2.5M10.125 3h3.75A2.625 2.625 0 0 1 16.5 5.625v.25A2.625 2.625 0 0 1 13.875 8.5h-3.75A2.625 2.625 0 0 1 7.5 5.875v-.25A2.625 2.625 0 0 1 10.125 3M8.5 5.75h7M7.5 4c-2 0-2 3.5 0 3.5m9-3.5c2 0 2 3.5 0 3.5m-4.5 7V19m-2.25-2.25h4.5");
}

</style>
