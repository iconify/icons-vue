<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_7jbu_kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff" /></template>
<style>
.b_7jbu_kd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 8l-2 2l.915 5.492a1 1 0 0 1-.279.872l-.136.136a.613.613 0 0 1-.924-.066L12 13l-2 1v1.586a1 1 0 0 1-.293.707L9.5 16.5a.707.707 0 0 1-1 0l-3-3a.707.707 0 0 1 0-1l.207-.207A1 1 0 0 1 6.414 12H8l1-2l-3.434-2.576A.613.613 0 0 1 5.5 6.5l.136-.136a1 1 0 0 1 .872-.28L12 7l2-2c2-2 3-2 4-1s1 2-1 4M3 21h18");
}

</style>
