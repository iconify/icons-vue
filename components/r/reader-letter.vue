<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul340fp9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reader-letter" /></template>
<style>
.ul340fp9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.5L3 4v14.5l9 1.5l9-1.5V4Zm0 0V20M6 8.5L9 9m-3 3l3 .5M15 9l3-.5m-3 4l3-.5");
}

</style>
