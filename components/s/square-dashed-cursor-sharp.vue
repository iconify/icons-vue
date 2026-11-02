<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snk0ly50r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-sharp" /></template>
<style>
.snk0ly50r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6V3h3m12 0h3v3M6 21H3v-3m7-15h4M3 14v-4m6-1l12 4l-4 1l3 3l-3 3l-3-3l-1 4z");
}

</style>
