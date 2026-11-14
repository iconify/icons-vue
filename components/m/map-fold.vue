<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acvbhdcdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-fold" /></template>
<style>
.acvbhdcdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.577 5.051L7.875 3.26a1.75 1.75 0 0 1 1.262-.032l5.726 2.044a1.75 1.75 0 0 0 1.262-.032l2.952-1.23A1.75 1.75 0 0 1 21.5 5.625v11.708a1.75 1.75 0 0 1-1.077 1.616l-4.298 1.791a1.75 1.75 0 0 1-1.262.032l-5.726-2.044a1.75 1.75 0 0 0-1.262.032l-2.952 1.23A1.75 1.75 0 0 1 2.5 18.375V6.667a1.75 1.75 0 0 1 1.077-1.616M8.5 3v15.5m7-13V21");
}

</style>
