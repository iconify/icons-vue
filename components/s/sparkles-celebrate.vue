<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agxucbcxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sparkles-celebrate" /></template>
<style>
.agxucbcxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4q.75 7.25 8 8q-7.25.75-8 8q-.75-7.25-8-8q7.25-.75 8-8m7-1.5q.25 2.25 2.5 2.5q-2.25.25-2.5 2.5q-.25-2.25-2.5-2.5q2.25-.25 2.5-2.5m-14 14q.25 2.25 2.5 2.5q-2.25.25-2.5 2.5q-.25-2.25-2.5-2.5q2.25-.25 2.5-2.5");
}

</style>
