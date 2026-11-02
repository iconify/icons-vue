<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z9b__3b_p"/><path class="a6ft3rbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-duotone-round" /></template>
<style>
.a6ft3rbot {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6h18M3 12h8m-8 6h8m4-6v4c0 .997 1.145 1.57 2 1l3-2a1.202 1.202 0 0 0 0-2l-3-2c-.855-.57-2 .003-2 1");
}

.ft5dv1b6b {
  fill: none;
}

.z9b__3b_p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 12c.001-1.031 1.175-1.549 2-1l3 2a1.202 1.202 0 0 1 0 2l-3 2c-.825.549-1.999.031-2-1Z");
}

</style>
