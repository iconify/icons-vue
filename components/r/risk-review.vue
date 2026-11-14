<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxx6gou9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:risk-review" /></template>
<style>
.nxx6gou9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.275 7.451l4.96 8.614A2.625 2.625 0 0 1 16.96 20H7.04a2.625 2.625 0 0 1-2.275-3.935l4.96-8.614a2.625 2.625 0 0 1 4.55 0M12 9.5v4m0 3.25h.01");
}

</style>
