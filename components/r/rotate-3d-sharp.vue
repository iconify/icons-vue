<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vflt74b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-3d-sharp" /></template>
<style>
.vflt74b8f {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12C2 17.52 6.477 22 12 22C17.523 22 22 17.52 22 12M2 12C2 6.48 6.477 2 12 2C17.523 2 22 6.48 22 12M2 12L4.322 13.03C6.097 13.82 7.982 14.33 9.912 14.55C11.3 14.7 12.7 14.7 14.088 14.55C16.018 14.33 17.903 13.82 19.678 13.03L22 12M11.184 21.96L9.846 19.62C9.066 18.25 8.511 16.77 8.202 15.23C7.777 13.1 7.832 10.9 8.357 8.8C8.563 7.97 8.841 7.17 9.186 6.39L11.117 2.04");
}

</style>
