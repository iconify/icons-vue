<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5pn9d7ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tagging-table" /></template>
<style>
.w5pn9d7ex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5h16A1.5 1.5 0 0 1 21.5 9a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 9A1.5 1.5 0 0 1 4 7.5m1 3v11m14-11v11m-7-11V13m-1.987 1.987l.75-.75a1.75 1.75 0 0 1 2.474 0l.75.75a1.75 1.75 0 0 1 .513 1.238v2.525a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-2.525a1.75 1.75 0 0 1 .513-1.238M12 15.75h.01M7.5 3h3A1.5 1.5 0 0 1 12 4.5V6a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 6 6V4.5A1.5 1.5 0 0 1 7.5 3");
}

</style>
