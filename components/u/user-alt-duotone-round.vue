<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m_526vbpb"/><path class="w85-lohkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-alt-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m_526vbpb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.472 5.664a6.001 6.001 0 1 1 11.055 4.674A6.001 6.001 0 0 1 6.472 5.664M20 22H4a1 1 0 0 1-1-1c0-.829.336-1.577.865-2.203c.552-.651 1.272-1.14 2.031-1.52C7.741 16.355 9.953 16 12 16s4.259.355 6.104 1.277c.759.38 1.479.869 2.031 1.52c.529.626.865 1.374.865 2.203a1 1 0 0 1-1 1");
}

.w85-lohkm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 0 0 7 8M4 21c0-2.21 3.582-4 8-4s8 1.79 8 4");
}

</style>
