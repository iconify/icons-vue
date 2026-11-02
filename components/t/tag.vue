<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm-xw5bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag" /></template>
<style>
.mm-xw5bmk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4h3c.64 0 1.36.36 2 1l6 6a1.414 1.414 0 0 1 0 2l-6 6a1.414 1.414 0 0 1-2 0l-6-6c-.64-.64-1-1.36-1-2V6a2 2 0 0 1 2-2zm0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
