<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2ya4fxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:soup-sharp" /></template>
<style>
.hl2ya4fxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11h18a9 9 0 0 1-18 0m6-6L8 7m5-2l-1 2m5-2l-1 2m3 4l2-5");
}

</style>
