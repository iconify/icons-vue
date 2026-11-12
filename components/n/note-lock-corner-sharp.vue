<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpzqxgbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-lock-corner-sharp" /></template>
<style>
.bpzqxgbrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 20H4V4h16v4m-7 8h8v5h-8Zm2 0v-1a2 2 0 1 1 4 0v1");
}

</style>
