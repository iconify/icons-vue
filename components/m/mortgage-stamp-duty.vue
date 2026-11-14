<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp3dqbcfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-stamp-duty" /></template>
<style>
.rp3dqbcfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8V5a2 2 0 0 1 4 0v3M5 8h14v3.5H5Zm1.5 5.75h11M8 19l4-3l4 3v2.5H8Z");
}

</style>
