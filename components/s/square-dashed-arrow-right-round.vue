<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc3i4-22h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-arrow-right-round" /></template>
<style>
.sc3i4-22h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a3 3 0 0 1 3-3m12 0a3 3 0 0 1 3 3m0 12a3 3 0 0 1-3 3M6 21a3 3 0 0 1-3-3m7-15h4m7 7v4m-7 7h-4m-7-7v-4m10 5l3-3l-3-3m3 3H8");
}

</style>
