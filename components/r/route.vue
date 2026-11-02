<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_jkv9b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route" /></template>
<style>
.g_jkv9b-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0M16 6H8a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H8m8-12a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
