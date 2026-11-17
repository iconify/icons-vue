<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="do3x_vbln"/><path class="ltwks1vjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-diagonal-duotone" /></template>
<style>
.do3x_vbln {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 8a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-5 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-5 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.ltwks1vjp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
