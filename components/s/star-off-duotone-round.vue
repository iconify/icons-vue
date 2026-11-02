<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v5_knyx6q"/><path class="sgmsrbbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sgmsrbbap {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 5l1-2l3 6l7 1l-3 3m-1 6v2l-6-3l-6 3l1-6l-5-5l6-1M2 3l19 19");
}

.v5_knyx6q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.66 8.084l6.481.926a1.001 1.001 0 0 1 .566 1.697l-4.636 4.636l.915 5.493a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L12 19.118l-5.553 2.776a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.915-5.493l-4.636-4.636a1.001 1.001 0 0 1 .566-1.697l6.481-.926l2.766-5.531a.998.998 0 0 1 1.788 0Z");
}

</style>
