<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvasnf8li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mountain-snow-sharp" /></template>
<style>
.mvasnf8li {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 20L7 10L9.5 13L14.0349 4L22 20ZM10.481 11.0531C10.9498 10.8292 12.2136 10.0874 13.5 10.5C15.835 11.249 16.1204 10.1424 16.8571 9.6692");
}

</style>
