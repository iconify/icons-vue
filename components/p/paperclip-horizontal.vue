<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hssgmbcyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paperclip-horizontal" /></template>
<style>
.hssgmbcyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6h8a6 6 0 1 1 0 12H7a4 4 0 1 1 0-8h8a2 2 0 1 1 0 4H8");
}

</style>
