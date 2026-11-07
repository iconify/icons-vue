<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv5d4rb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-text-round" /></template>
<style>
.pv5d4rb0p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a4 4 0 0 1 4-4m10 0a4 4 0 0 1 4 4m0 10a4 4 0 0 1-4 4M7 21a4 4 0 0 1-4-4m4-9h10M7 12h10M7 16h6");
}

</style>
