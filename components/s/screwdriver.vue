<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxey3cbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:screwdriver" /></template>
<style>
.lxey3cbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.929 14.121l1.768-1.767a3.5 3.5 0 0 1 4.949 0a3.5 3.5 0 0 1 0 4.949l-1.767 1.768a3.5 3.5 0 0 1-4.95 0a3.5 3.5 0 0 1 0-4.95m6.364-3.889za1.25 1.25 0 0 1 1.768 0l.707.707a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0L11.293 12a1.25 1.25 0 0 1 0-1.768m2.121.354l7.071-7.071M7.05 16.95l2.475-2.475");
}

</style>
