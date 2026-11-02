<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikp4edbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-up-round" /></template>
<style>
.ikp4edbed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 17l4-4a2.83 2.83 0 0 1 4 0a2.83 2.83 0 0 0 4 0l6-6m-6 0h6v6");
}

</style>
