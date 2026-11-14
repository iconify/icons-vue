<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw-55ib9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:palm-tree" /></template>
<style>
.rw-55ib9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21c0-6 1-11 1-15m0 0c-3-1-5 0-6.5 2M13 6c3-1 5 0 6.5 2M13 6c-1-2.5-3-3-4.5-2.5M13 6c2-2.5 4-3 5-2.5M7 21h10");
}

</style>
