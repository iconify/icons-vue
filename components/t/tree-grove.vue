<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu3uyccan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tree-grove" /></template>
<style>
.yu3uyccan {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8a2.25 5.5 0 1 0 4.5 0a2.25 5.5 0 1 0-4.5 0M12 13.5v8m-9.5-11a2.25 4.5 0 1 0 4.5 0a2.25 4.5 0 1 0-4.5 0M4.75 15v6.5M17 10.5a2.25 4.5 0 1 0 4.5 0a2.25 4.5 0 1 0-4.5 0m2.25 4.5v6.5");
}

</style>
