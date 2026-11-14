<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0h8r-iyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:server-alert" /></template>
<style>
.h0h8r-iyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5h11A3.5 3.5 0 0 1 21 7a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 7a3.5 3.5 0 0 1 3.5-3.5m5.75 10H5a2 2 0 0 0-2 2v3a2 2 0 0 0 2 2h7.25M6.75 7h.01m-.01 10h.01M11.5 7h6m.5 7.5V18m0 3h.01");
}

</style>
