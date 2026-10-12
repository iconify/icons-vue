<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qti76cb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roundabout" /></template>
<style>
.qti76cb1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.85 8.63a6.75 6.75 0 0 0-8.7-2.75m2.28.74l-2.28-.74l.9-2.22M12 18.75a6.75 6.75 0 0 0 6.72-6.16m-1.78 1.61l1.78-1.61l1.48 1.89M6.15 8.63a6.75 6.75 0 0 0 1.98 8.9m-.5-2.35l.5 2.35l-2.38.33M14 12a2 2 0 1 1-4 0a2 2 0 1 1 4 0");
}

</style>
