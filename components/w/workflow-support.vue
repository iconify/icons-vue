<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chb_wfbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:workflow-support" /></template>
<style>
.chb_wfbvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h1.5A2.5 2.5 0 0 1 9 5.5A2.5 2.5 0 0 1 6.5 8H5a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 5 3m12.5 0H19a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 19 8h-1.5A2.5 2.5 0 0 1 15 5.5A2.5 2.5 0 0 1 17.5 3M5 15h1.5A2.5 2.5 0 0 1 9 17.5A2.5 2.5 0 0 1 6.5 20H5a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 5 15m4-9.5h6M5.75 8v7m8.75 3a3.25 3.25 0 0 1 6.5 0m-6.5 0za1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V19a1 1 0 0 1 1-1m6.5 0za1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V19a1 1 0 0 1 1-1");
}

</style>
