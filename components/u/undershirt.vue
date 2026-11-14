<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmtxjlbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:undershirt" /></template>
<style>
.xmtxjlbgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.5V5c0 3-2.25 4.5-2.25 7v9.5h15V12c0-2.5-2.25-4-2.25-7V2.5h-3c0 6-4.5 6-4.5 0Zm-2.25 16h15");
}

</style>
