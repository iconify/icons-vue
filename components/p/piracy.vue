<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3pcr1b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:piracy" /></template>
<style>
.e3pcr1b0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 14v-1.25a5.5 5.5 0 1 1 5.5 0V14ZM5 15.5L19 21m0-5.5L5 21M9.75 8.75h.01m4.49 0h.01");
}

</style>
