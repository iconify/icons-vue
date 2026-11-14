<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggdt2ukoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:talent-acquisition" /></template>
<style>
.ggdt2ukoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 4h-4a8 8 0 0 0 0 16h4v-4.5h-4a3.5 3.5 0 0 1 0-7h4Zm-2 0v4.5m0 7V20m4.75-11a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-.5 8.5c0-2.25 1.25-3.5 2.75-3.5s2.75 1.25 2.75 3.5Z");
}

</style>
