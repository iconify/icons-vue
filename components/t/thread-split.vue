<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6ss0rbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thread-split" /></template>
<style>
.s6ss0rbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12h6c3.5 0 4.5-6.25 8-6.25h4.5M8.75 12c3.5 0 4.5 6.25 8 6.25h4.5M12.75 12h8.5");
}

</style>
