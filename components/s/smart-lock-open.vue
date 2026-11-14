<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j22kj5mgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-lock-open" /></template>
<style>
.j22kj5mgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 10.5h9A3.5 3.5 0 0 1 20 14v4a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18v-4a3.5 3.5 0 0 1 3.5-3.5m8 0V6a3.5 3.5 0 0 0-7 0v1.5m3.5 7v3");
}

</style>
