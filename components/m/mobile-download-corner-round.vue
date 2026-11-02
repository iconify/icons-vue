<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9pzk5bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-download-corner-round" /></template>
<style>
.e9pzk5bwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V7a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v3m-3 11H7a4 4 0 0 1-4-4v-5m11 6l3 3l3-3m-3 3v-8");
}

</style>
