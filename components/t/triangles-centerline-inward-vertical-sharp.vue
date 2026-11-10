<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu3r4ioix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-inward-vertical-sharp" /></template>
<style>
.vu3r4ioix {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 1V23M8.257 12L2 16.22V7.78L8.257 12ZM15.743 12L22 16.22V7.78L15.743 12Z");
}

</style>
