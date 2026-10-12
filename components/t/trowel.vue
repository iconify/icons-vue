<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he3tiobsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trowel" /></template>
<style>
.he3tiobsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.09 19.79l2.62-11.4q.34-1.46 1.4-.4l8.9 8.9q1.06 1.06-.4 1.4l-11.4 2.62q-1.46.34-1.12-1.12m8.47-7.35l3.19-3.19m4.39-5.09l.7.7q1.41 1.41 0 2.82l-2.16 2.16q-1.41 1.41-2.82 0l-.7-.7q-1.41-1.41 0-2.82l2.16-2.16q1.41-1.41 2.82 0");
}

</style>
