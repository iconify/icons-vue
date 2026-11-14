<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdp__bb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repo-contributors" /></template>
<style>
.rdp__bb6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0M6.5 20v-1c0-3 2.5-5 5.5-5s5.5 2 5.5 5v1M2.25 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m15.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2 18.5v-1c0-1.75.75-3 2.25-3.25M22 18.5v-1c0-1.75-.75-3-2.25-3.25");
}

</style>
