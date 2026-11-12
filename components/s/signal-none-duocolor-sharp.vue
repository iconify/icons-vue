<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i21l4cbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-none-duocolor-sharp" /></template>
<style>
.i21l4cbtl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-opacity: 0.4;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 20h.01M10 20h.01M14 20h.01M18 20h.01");
}

</style>
