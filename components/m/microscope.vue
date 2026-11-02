<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia75os76n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microscope" /></template>
<style>
.ia75os76n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6h6v5a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm1 0V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2M3 21h18M6 17h8m0 4a6 6 0 0 0 6-6a5 5 0 0 0-5-5h-2");
}

</style>
