<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl8fs8f5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:underline-sharp-fill" /></template>
<style>
.nl8fs8f5c {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 2L6 11C6 14.3137 8.6863 17 12 17C15.3137 17 18 14.3137 18 11L18 2M2 21L22 21");
}

</style>
