<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv8kh0bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiator" /></template>
<style>
.jv8kh0bbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4a1 1 0 0 1 2 0v16a1 1 0 0 1-2 0Zm7 0a1 1 0 0 1 2 0v16a1 1 0 0 1-2 0Zm7 0a1 1 0 0 1 2 0v16a1 1 0 0 1-2 0ZM3 8h16M5 16h16");
}

</style>
