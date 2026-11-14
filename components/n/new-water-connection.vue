<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpftwkdoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:new-water-connection" /></template>
<style>
.kpftwkdoc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h6a4 4 0 0 1 4 4V12h-4v-1.25a1 1 0 0 0-1-1h-5M3 2.5h5m-2.5 0v3m5 9.5c1 1.25 1.75 2.25 1.75 3a1.75 1.75 0 0 1-3.5 0c0-.75.75-1.75 1.75-3m7.5 0v6m-3-3h6");
}

</style>
