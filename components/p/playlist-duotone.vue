<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ue_kr-b8y"/><path class="r32jczb6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.r32jczb6f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6h18M3 12h8m-8 6h8m4-7v6c0 .23.54.23 1 0l4-2a1.118 1.118 0 0 0 0-2l-4-2c-.46-.23-1-.23-1 0");
}

.ue_kr-b8y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 17v-6c0-.23.541-.23 1 0l4 2a1.118 1.118 0 0 1 0 2l-4 2c-.459.23-1 .23-1 0");
}

</style>
