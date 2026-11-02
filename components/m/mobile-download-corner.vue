<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8au3ys-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-download-corner" /></template>
<style>
.g8au3ys-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v5m-3 11H5a2 2 0 0 1-2-2v-7m11 6l3 3l3-3m-3 3v-8");
}

</style>
