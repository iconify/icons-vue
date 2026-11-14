<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c53pwwozk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soundbar" /></template>
<style>
.c53pwwozk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12.5h14a3 3 0 0 1 3 3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3a3 3 0 0 1 3-3m1 3h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01M9.879 8.879a3 3 0 0 1 4.242 0M7.983 6.212a6.25 6.25 0 0 1 8.034 0");
}

</style>
