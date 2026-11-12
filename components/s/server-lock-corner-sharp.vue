<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4kyekbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-sharp" /></template>
<style>
.m4kyekbuj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v6H3Zm0 10h6m0 6H3v-6m4-7h.01M7 17h.01M13 16h8v5h-8Zm2 0v-1a2 2 0 1 1 4 0v1");
}

</style>
