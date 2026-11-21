<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkfonllql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:postcard-sharp" /></template>
<style>
.bkfonllql {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12L6 12L10 12L11 12M5 16L6 16L14 16L15 16M2 4L22 4L22 20L2 20ZM14 8L18 8L18 12L14 12Z");
}

</style>
