<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tttpw3btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shirt-sharp" /></template>
<style>
.tttpw3btv {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 2L20.5 4L22.0001 8.5L18.5 10.5L18 22L6 22L5.5 10.5L1.9999 8.5L3.5 4L9 2C9 3.6569 10.3431 5 12 5C13.6569 5 15 3.6569 15 2Z");
}

</style>
