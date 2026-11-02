<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m6azqacoa"/><path class="ulmahmbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tunnel-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m6azqacoa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10v7a3 3 0 1 1-6 0v-7a4 4 0 0 0-8 0v7a3 3 0 1 1-6 0Z");
}

.ulmahmbth {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 19v-7a9 9 0 0 1 18 0v7a2 2 0 1 1-4 0v-7a5 5 0 0 0-10 0v7a2 2 0 1 1-4 0M8 8L6 6m6-3v4m4 1l2-2M3 11h4m10 0h4M3 16h4m10 0h4");
}

</style>
