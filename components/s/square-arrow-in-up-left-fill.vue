<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnj9tub0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-in-up-left-fill" /></template>
<style>
.pnj9tub0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17L6 17C4.3431 17 3 15.6569 3 14L3 6C3 4.3431 4.3431 3 6 3L14 3C15.6569 3 17 4.3431 17 6L17 9M21 21L13.5 13.5M21 13L13.5 13C13.2239 13 13 13.2239 13 13.5L13 21");
}

</style>
