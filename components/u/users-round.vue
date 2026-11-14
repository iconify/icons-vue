<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmn_dvpka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:users-round" /></template>
<style>
.mmn_dvpka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M3 20.5c0-3.5 2.75-5.75 6.5-5.75S16 17 16 20.5M15 4.25a3.5 3.5 0 0 1 0 7m2.5 3.5c2 .5 3.5 2.25 3.5 5.75");
}

</style>
