<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oouo4ab_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:satellite-dish-sharp" /></template>
<style>
.oouo4ab_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 19a5.657 5.657 0 1 1-8-8Zm-4-4l4-4m0-4a4 4 0 0 1 4 4m-4-8a8 8 0 0 1 8 8");
}

</style>
