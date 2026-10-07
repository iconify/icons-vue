<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0_anwbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:voicemail-sharp" /></template>
<style>
.y0_anwbkc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12C10 14.2091 8.2091 16 6 16C3.7909 16 2 14.2091 2 12C2 9.7909 3.7909 8 6 8C8.2091 8 10 9.7909 10 12ZM22 12C22 14.2091 20.2091 16 18 16C15.7909 16 14 14.2091 14 12C14 9.7909 15.7909 8 18 8C20.2091 8 22 9.7909 22 12ZM6 16L18 16");
}

</style>
