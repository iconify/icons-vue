<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwx9tqbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-size-sharp-fill" /></template>
<style>
.vwx9tqbgh {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 8L2 7L2 4L16 4L16 7L16 8M9 4L9 20M5 20L6 20L12 20L13 20M13 14L13 13L13 11L22 11L22 13L22 14M17.5 11L17.5 20M15 20L16 20L19 20L20 20");
}

</style>
