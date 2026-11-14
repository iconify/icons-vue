<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk7yu5bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meet-the-maker" /></template>
<style>
.hk7yu5bba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-4 14c0-4 3.5-6.5 8-6.5c.791 0 1.552.077 2.268.227M8.5 15.5l1 6m12-7.5l-2.75 2.75m-4.25 2a2.25 1.25 0 1 0 4.5 0a2.25 1.25 0 1 0-4.5 0m-.25 2.75h.01");
}

</style>
