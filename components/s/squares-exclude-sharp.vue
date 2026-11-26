<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaw-czb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-exclude-sharp" /></template>
<style>
.iaw-czb6b {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L15 3L15 9L21 9L21 21L9 21L9 15L3 15ZM12 9L9 9L9 12M15 12L15 15L12 15");
}

</style>
