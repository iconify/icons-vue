<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4ts4bc7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:square-rounded" /></template>
<style>
.f4ts4bc7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h8m5 5v8m-5 5H8m-5-5V8m13-5a5 5 0 0 1 5 5m0 8a5 5 0 0 1-5 5m-8 0a5 5 0 0 1-5-5m0-8a5 5 0 0 1 5-5");
}

</style>
