<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p5sdxbcmv"/><path class="k6gaqhbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k6gaqhbeq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m10.59 4.456l8 5c1.88 1.175 1.88 3.913 0 5.088l-8 5C8.592 20.793 6 19.356 6 17V7c0-2.356 2.592-3.793 4.59-2.544");
}

.p5sdxbcmv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m10.59 4.456l8 5a3 3 0 0 1 0 5.088l-8 5A2.999 2.999 0 0 1 6 17V7a3 3 0 0 1 4.59-2.544");
}

</style>
