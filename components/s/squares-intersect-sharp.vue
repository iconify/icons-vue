<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv11dkb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-intersect-sharp" /></template>
<style>
.fv11dkb7z {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9L15 9L15 15L9 15ZM6 15L3 15L3 10.5M3 7.5L3 3L7.5 3M10.5 3L15 3L15 6M18 9L21 9L21 13.5M21 16.5L21 21L16.5 21M13.5 21L9 21L9 18");
}

</style>
