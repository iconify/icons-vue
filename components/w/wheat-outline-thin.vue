<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzgrsxbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wheat-outline-thin" /></template>
<style>
.tzgrsxbhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V4m0 4L7 3m5 5 5 -5m-5 10L7 8m5 5 5 -5m-5 10 -5 -5m5 5 5 -5");
}

</style>
