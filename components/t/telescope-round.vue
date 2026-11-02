<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qblsphrvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telescope-round" /></template>
<style>
.qblsphrvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m10 7l6-3a2.236 2.236 0 0 1 2 4L8 13a2.236 2.236 0 0 1-2-4zm4-2l2 4m-4 2L7 21m5-10l5 10");
}

</style>
