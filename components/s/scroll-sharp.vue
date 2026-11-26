<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lte72s4_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scroll-sharp" /></template>
<style>
.lte72s4_g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 16L18 3L2 3L2 9L7 9M7 3L7 21L22 21L22 16L12 16L12 21M10 8L15 8M10 12L15 12");
}

</style>
