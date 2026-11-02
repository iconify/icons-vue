<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n92ifub3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-round" /></template>
<style>
.n92ifub3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14L17 4c.64-.64 1.72-1 3-1h1v1c0 1.28-.36 2.36-1 3L10 17m-5-5l7 7m-4-3l-4 4m-1-1l2 2");
}

</style>
