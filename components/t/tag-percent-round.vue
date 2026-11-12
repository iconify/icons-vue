<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwjre3nuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-percent-round" /></template>
<style>
.lwjre3nuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14v5a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8c0-.64.36-1.36 1-2l2-2c.64-.64 1.36-1 2-1h4c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2zm-8-8h2m2 5l-6 6m-1-6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
