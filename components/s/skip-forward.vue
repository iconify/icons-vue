<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1bhkzbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward" /></template>
<style>
.y1bhkzbqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7.06 5.304l8 5a2 2 0 0 1 0 3.392l-8 5C5.728 19.529 4 18.571 4 17V7c0-1.57 1.728-2.529 3.06-1.696M20 5v14");
}

</style>
