<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="syu9tw6_u"/><path class="i8uxn2cvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-plus-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i8uxn2cvn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h6l4 4v14H5V7zm2 3h2m-4 8h6m-3-3v6");
}

.syu9tw6_u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 3h6l4 4v14H5V7Z");
}

</style>
