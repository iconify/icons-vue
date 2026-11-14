<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh9vg4iij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sprout-soil" /></template>
<style>
.nh9vg4iij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19c3.5-4.5 15.5-4.5 19 0Zm9.5-3.25V9m0 2.5C12 8 14.5 5 18 5c0 3.5-2.5 6.5-6 6.5");
}

</style>
