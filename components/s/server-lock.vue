<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjo_ss8st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:server-lock" /></template>
<style>
.hjo_ss8st {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5h11A3.5 3.5 0 0 1 21 7a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 7a3.5 3.5 0 0 1 3.5-3.5m5.75 10H5a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h7.25M6.75 7h.01m-.01 10h.01M11.5 7h6m-.75 10h2.5A1.75 1.75 0 0 1 21 18.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-1A1.75 1.75 0 0 1 16.75 17m-.5 0v-1.25a1.75 1.75 0 0 1 3.5 0V17");
}

</style>
