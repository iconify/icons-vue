<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8j5vfbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-quest-marker" /></template>
<style>
.b8j5vfbty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5s-7.5-7-7.5-12a7.5 7.5 0 0 1 15 0c0 5-7.5 12-7.5 12M12 6v4.5m0 3.25h.01");
}

</style>
