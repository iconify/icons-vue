<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl2uyx8pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:netball" /></template>
<style>
.fl2uyx8pb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M3.5 12.5a6.5 1.5 0 1 0 13 0a6.5 1.5 0 1 0-13 0m16-10v19m-3-9h3M5 13.5l2.5 7m7.5-7l-2.5 7");
}

</style>
