<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyup2fbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-round" /></template>
<style>
.yyup2fbjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H7a2 2 0 0 1-2-2V8c0-1.28.36-2.36 1-3l1-1c.64-.64 1.72-1 3-1h4c1.28 0 2.36.36 3 1l1 1c.64.64 1 1.72 1 3v7a2 2 0 0 1-2 2zm-4 0l-2 4m10-4l2 4M5 10h14M9 14h.01M15 14h.01");
}

</style>
