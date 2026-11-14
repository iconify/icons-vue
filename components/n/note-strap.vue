<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn9ucuzmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:note-strap" /></template>
<style>
.qn9ucuzmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 5.5h13.75A2.625 2.625 0 0 1 21.5 8.125v6.25A2.625 2.625 0 0 1 18.875 17H5.125A2.625 2.625 0 0 1 2.5 14.375v-6.25A2.625 2.625 0 0 1 5.125 5.5M3.5 20h17M9.5 5.5V17m5-11.5V17M6 11.25h.01m11.99 0h.01");
}

</style>
