<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkffo7b1e"/><path class="ksstlkr8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weight-hanging" /></template>
<style>
.bkffo7b1e {
  d: path("M6 2.5h12m-6 0V6M9.75 8.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksstlkr8f {
  d: path("M10.242 10.5h3.516a1.75 1.75 0 0 1 1.652 1.172l2.275 6.5a1.75 1.75 0 0 1-1.652 2.328H7.967a1.75 1.75 0 0 1-1.652-2.328l2.275-6.5a1.75 1.75 0 0 1 1.652-1.172");
}

</style>
