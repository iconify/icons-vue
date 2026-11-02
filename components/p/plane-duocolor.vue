<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs6xwkx0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-duocolor" /></template>
<style>
.bs6xwkx0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 8l-3 3l1.863 7.45a1 1 0 0 1-.263.95l-.737.737a1 1 0 0 1-1.54-.152L12 15l-3 2v2.586a1 1 0 0 1-.293.707L8.5 20.5a.58.58 0 0 1-.892-.088L6 18l-2.412-1.608A.58.58 0 0 1 3.5 15.5l.207-.207A1 1 0 0 1 4.414 15H7l2-3l-4.985-3.323a1 1 0 0 1-.152-1.54L4.6 6.4a1 1 0 0 1 .95-.263L13 8l3-3c2-2 3-2 4-1s1 2-1 4");
}

</style>
