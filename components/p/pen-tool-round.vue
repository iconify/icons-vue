<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doc4uemle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-round" /></template>
<style>
.doc4uemle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 4l10 3l3 6l-4 4l-6-3Zm13 9l1 1a2.828 2.828 0 1 1-4 4l-1-1M4 4l4 4m3 3h.01");
}

</style>
