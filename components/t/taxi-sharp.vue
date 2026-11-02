<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg19muazf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-sharp" /></template>
<style>
.tg19muazf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5h4M8 15h.01M16 15h.01M4 18v-6l2-4h12l2 4v6zm2 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

</style>
