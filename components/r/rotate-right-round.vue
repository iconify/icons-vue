<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u58qtlurp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-right-round" /></template>
<style>
.u58qtlurp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14v2a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9a3 3 0 0 0-3-3m-4 0H9a4 4 0 0 0-4 4m4-7l3 3l-3 3");
}

</style>
