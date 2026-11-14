<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa9kfby4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shoe-repair" /></template>
<style>
.qa9kfby4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.429 13H7.5v2h-5V4.5h4c1 2 3 3 6 3.5l6 1c1.5.25 3 1.5 3 3v1h-2.271M2.5 12h19m-13-6.25L9.75 7.5M11 6.75l1 1.5m2.75 13.25l4-4m-.707-1.871l2.828 2.828a1 1 0 0 1 0 1.414a1 1 0 0 1-1.414 0l-2.828-2.828a1 1 0 0 1 0-1.414a1 1 0 0 1 1.414 0");
}

</style>
