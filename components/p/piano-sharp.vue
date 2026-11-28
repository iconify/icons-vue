<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5u0i1xiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piano-sharp" /></template>
<style>
.q5u0i1xiv {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 20L2 20ZM6 4L6 13L10 13L10 4M8 13L8 20M14 4L14 13L18 13L18 4M16 13L16 20");
}

</style>
