<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoi7d7b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-zap-round" /></template>
<style>
.uoi7d7b9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7h1a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-2a4 4 0 0 1 4-4zM6 3v4m4-4v4M8 17v4M20 7l-3 5h4l-3 5");
}

</style>
