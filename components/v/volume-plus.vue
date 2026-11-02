<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvy28sb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-plus" /></template>
<style>
.bvy28sb3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 6v12c0 .738-.631 1.369-1 1l-2-2c-.64-.64-1.36-1-2-1H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1c.64 0 1.36-.36 2-1l2-2c.369-.369 1 .262 1 1m4 6h6m-3-3v6");
}

</style>
