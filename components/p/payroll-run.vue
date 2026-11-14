<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt16o2u3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:payroll-run" /></template>
<style>
.tt16o2u3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15.5h14a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 18A2.5 2.5 0 0 1 5 15.5M5 18h.01M12 18h.01M19 18h.01M2.75 12.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M7.5 7h9m-2-2l2 2l-2 2");
}

</style>
