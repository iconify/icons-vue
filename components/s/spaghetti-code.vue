<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0tsm-byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spaghetti-code" /></template>
<style>
.w0tsm-byl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17C6 17 6 7 10 7s4 8 1 8s-2-9.5 3-9.5c4.5 0 4.5 7.5 2 7.5s-1-4.5 5.5-4.5M3.5 20C9 20 13 17.5 21 20");
}

</style>
