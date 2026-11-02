<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6_ymacif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-round" /></template>
<style>
.j6_ymacif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16L14 6a2.828 2.828 0 1 1 4 4L8 20m0 0H4v-4m7-11L9 7m10 6l-2 2m-4-8l-2-2a2.83 2.83 0 0 0-4 0L5 7a2.83 2.83 0 0 0 0 4l2 2m10-2l2 2a2.83 2.83 0 0 1 0 4l-2 2a2.83 2.83 0 0 1-4 0l-2-2");
}

</style>
