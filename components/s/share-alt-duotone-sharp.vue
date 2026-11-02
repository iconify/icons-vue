<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k3bx-ybwa"/><path class="o_x9s7vbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-alt-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k3bx-ybwa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.943 9.943a4.16 4.16 0 0 1-5.886 0a4.16 4.16 0 0 1 0-5.886a4.16 4.16 0 0 1 5.886 0a4.16 4.16 0 0 1 0 5.886m-10 5a4.16 4.16 0 0 1-5.886 0a4.16 4.16 0 0 1 0-5.886a4.16 4.16 0 0 1 5.886 0a4.16 4.16 0 0 1 0 5.886m10 5a4.16 4.16 0 0 1-5.886 0a4.16 4.16 0 0 1 0-5.886a4.16 4.16 0 0 1 5.886 0a4.16 4.16 0 0 1 0 5.886");
}

.o_x9s7vbq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 8a3.162 3.162 0 1 1-6-2a3.162 3.162 0 0 1 6 2m-10 5a3.162 3.162 0 1 1-6-2a3.162 3.162 0 0 1 6 2m10 5a3.162 3.162 0 1 1-6-2a3.162 3.162 0 0 1 6 2m-10-7l4-3m-4 5l4 3");
}

</style>
