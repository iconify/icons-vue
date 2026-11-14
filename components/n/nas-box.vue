<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltmtgl9ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nas-box" /></template>
<style>
.ltmtgl9ai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h7a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 13 20H6a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 6 4m0 5h4m-4 5h4m3-5h.01M13 14h.01m3.49-2h2a2.5 2.5 0 0 1 2.5 2.5v6");
}

</style>
