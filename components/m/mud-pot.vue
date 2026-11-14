<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t94xwjbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mud-pot" /></template>
<style>
.t94xwjbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17a9.5 3.75 0 1 0 19 0a9.5 3.75 0 1 0-19 0m4-8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.5-3a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
