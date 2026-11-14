<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxwreacjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:margarita" /></template>
<style>
.jxwreacjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19c0 4-4.5 6-9.5 6s-9.5-2-9.5-6m9.5 6v8m-4 0h8m-.5-14a3 3 0 0 1 6 0");
}

</style>
