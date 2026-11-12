<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyj_45bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-clock-corner-round" /></template>
<style>
.cyj_45bkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4L3 6l4 2l2 4l3-9zM7 8l1-1m4 10a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
