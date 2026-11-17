<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g66od7wcw"/><path class="sw0he-bxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g66od7wcw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.75 3v7H19l-8.75 11v-7H5Z");
}

.sw0he-bxd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.75 3L5 14h5.25v7L19 10h-5.25z");
}

</style>
