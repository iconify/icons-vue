<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="swmvc4_nc"/><path class="dfo2t1e6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-alt-duotone-round" /></template>
<style>
.dfo2t1e6b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4c.693 0 1.48.787 2 2l3 7c.78 1.82 2.353 3 4 3h6M6 7h13c.82 0 1.328 1.016 1 2l-1 3c-.2.597-.602 1-1 1H8m0 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ft5dv1b6b {
  fill: none;
}

.swmvc4_nc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 7c.82 0 1.328 1.016 1 2l-1 3c-.14.419-.495.999-1 1H8L6 7Z");
}

</style>
