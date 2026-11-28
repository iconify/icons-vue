<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_pjncbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piano-off" /></template>
<style>
.b_pjncbec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.6569 4L19 4C20.6569 4 22 5.3431 22 7L22 16.3431M19.8715 19.8715C19.5957 19.9551 19.3031 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 7C2 5.6462 2.8967 4.5019 4.1285 4.1285M6 6L6 12C6 12.5523 6.4477 13 7 13L9 13C9.5523 13 10 12.5523 10 12L10 10M8 13L8 20M14 4L14 8.3431M17.9549 12.298C17.9842 12.2039 18 12.1038 18 12L18 4M2 2L22 22");
}

</style>
