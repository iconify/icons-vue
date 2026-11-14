<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hihstsbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paw-wash" /></template>
<style>
.hihstsbgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 15.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4-4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M8 19c0-2.25 2-3.5 4-3.5s4 1.25 4 3.5c0 2-2 2.5-4 2c-2 .5-4 0-4-2M5.5 2.5S4 4.5 4 5.5a1.5 1.5 0 0 0 3 0c0-1-1.5-3-1.5-3m6.5 0s-1.5 2-1.5 3a1.5 1.5 0 0 0 3 0c0-1-1.5-3-1.5-3m6.5 0s-1.5 2-1.5 3a1.5 1.5 0 0 0 3 0c0-1-1.5-3-1.5-3");
}

</style>
