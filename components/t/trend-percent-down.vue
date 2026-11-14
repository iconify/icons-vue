<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcvrk1xux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trend-percent-down" /></template>
<style>
.qcvrk1xux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 17.5l7-11m-7.25 1a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm4 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM17 3.5V20m-3.5-3.5L17 20l3.5-3.5");
}

</style>
