<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff3q3ybsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-shuttle" /></template>
<style>
.ff3q3ybsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.47 3.63l1.31 2.49q.47.88.47 1.88v1.5q0 1 .73 1.68l5.04 4.64q.73.68.73 1.68v.25q0 1-1 1H4.25q-1 0-1-1v-.25q0-1 .73-1.68l5.04-4.64q.73-.68.73-1.68V8q0-1 .47-1.88l1.31-2.49q.47-.88.94 0M12 11.5v5m-1.5 2.25h3q.5 0 .6.49l.3 1.52q.1.49-.4.49h-4q-.5 0-.4-.49l.3-1.52q.1-.49.6-.49");
}

</style>
