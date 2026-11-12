<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy_jwlbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:step-over" /></template>
<style>
.hy_jwlbge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11a7 7 0 0 1 14 0v2m-3-3l3 3l3-3m-5 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
