<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch4mkgudn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sprout" /></template>
<style>
.ch4mkgudn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10a6 6 0 0 0-6-6H3v2a6 6 0 0 0 6 6h3Zm0 4a6 6 0 0 1 6-6h3v1a6 6 0 0 1-6 6h-3Zm0 6V10");
}

</style>
