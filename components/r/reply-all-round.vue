<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9u8yg5wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reply-all-round" /></template>
<style>
.d9u8yg5wu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5L3 9l4 4m6-8L9 9l4 4M3 9h14a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4h-6");
}

</style>
