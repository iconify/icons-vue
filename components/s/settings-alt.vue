<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udrxy39ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-alt" /></template>
<style>
.udrxy39ou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 8.236v7.528a2 2 0 0 1-1.106 1.789l-6 3a2 2 0 0 1-1.788 0l-6-3A2 2 0 0 1 4 15.763V8.237a2 2 0 0 1 1.106-1.789l6-3a2 2 0 0 1 1.788 0l6 3A2 2 0 0 1 20 8.237M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
