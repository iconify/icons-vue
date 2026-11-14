<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqsi8y5hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speed-gun" /></template>
<style>
.jqsi8y5hw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5h12v6.5h-5.5l-1 7.5h-4.5l1-7.5h-2Zm14.681 1a3.5 3.5 0 0 1 0 4.5m2.298-6.428a6.5 6.5 0 0 1 0 8.356");
}

</style>
