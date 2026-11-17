<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="koqaqubzl"/><path class="mp2t67j5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.koqaqubzl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9.375 8.5l3.752-4.717A.35.35 0 0 1 13.75 4v5a1 1 0 0 0 1 1H18a.481.481 0 0 1 .377.783l-7.504 9.434A.35.35 0 0 1 10.25 20v-5a1 1 0 0 0-1-1H6a.481.481 0 0 1-.377-.783Z");
}

.mp2t67j5p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9.375 8.5l-3.752 4.717A.482.482 0 0 0 6 14h3.25a1 1 0 0 1 1 1v5c0 .33.417.476.623.217l7.504-9.434A.482.482 0 0 0 18 10h-3.25a1 1 0 0 1-1-1V4a.35.35 0 0 0-.623-.217z");
}

</style>
