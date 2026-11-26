<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsqs1h73d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-wrap-sharp-fill" /></template>
<style>
.bsqs1h73d {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 3L22 3M2 9L3 9L18 9C19.6569 9 21 10.3431 21 12C21 13.6569 19.6569 15 18 15L12 15M14.2929 12.7071L14 13L12 15L14 17L14.2929 17.2929M2 15L3 15L8 15L9 15M2 21L15 21L16 21");
}

</style>
