<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmuhltsqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:regex-round" /></template>
<style>
.pmuhltsqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 3v10m-4-8l8 6m-8 0l8-6M3 19a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
