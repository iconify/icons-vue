<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo39tibvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouse-x" /></template>
<style>
.qo39tibvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3h4a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 14 21h-4a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 10 3Zm2 3.5v3m-1.75 3l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
