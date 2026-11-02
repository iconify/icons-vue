<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjh9_9bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-duocolor-round" /></template>
<style>
.wjh9_9bqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 9A7.616 7.616 0 0 0 5 9m6 0H5V3m0 12a7.616 7.616 0 0 0 14 0m-6 0h6v6");
}

</style>
