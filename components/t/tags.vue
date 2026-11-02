<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb6gpabjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags" /></template>
<style>
.eb6gpabjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6h2c.64 0 1.36.36 2 1l4 4a1.414 1.414 0 0 1 0 2l-4 4a1.414 1.414 0 0 1-2 0l-4-4c-.64-.64-1-1.36-1-2V8a2 2 0 0 1 2-2zm1 4h.01M15 6l5 5a1.414 1.414 0 0 1 0 2l-5 5");
}

</style>
