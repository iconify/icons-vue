<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvmrhmb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weightlessness" /></template>
<style>
.yvmrhmb_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M4 20.5h16m-15.5-10V15m15-4.5V15");
}

</style>
