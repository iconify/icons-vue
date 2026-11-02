<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyctegbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-round" /></template>
<style>
.oyctegbmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10a4 4 0 0 0-4 4v3a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4v-3a4 4 0 0 0-4-4m-1-4l-3-3l-3 3m3-3v10");
}

</style>
