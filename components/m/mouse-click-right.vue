<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnuqv_vxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouse-click-right" /></template>
<style>
.gnuqv_vxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 5.5h4A3.5 3.5 0 0 1 15 9v9a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 4 18V9a3.5 3.5 0 0 1 3.5-3.5Zm2 0V11M4 11h11m6-8l-2 2m2.5 3.5H19m-3.5-6v1");
}

</style>
