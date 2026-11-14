<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svr3sab3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:measure-sound" /></template>
<style>
.svr3sab3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13a8.5 8.5 0 0 1 17 0M11 13l3.5-4.25M11 13h.01m4.24 4v3M18 15.5v6m2.75-4.5v3");
}

</style>
