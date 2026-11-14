<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn-s_m-ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:poison-control" /></template>
<style>
.qn-s_m-ag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3h4v4l3 3v9.5a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2V10l3-3Zm0 9.75l4 4m0-4l-4 4");
}

</style>
