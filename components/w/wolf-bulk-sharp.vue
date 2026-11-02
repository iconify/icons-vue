<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tncq_b45v"/><path class="f04fi9bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f04fi9bus {
  d: path("M10.707 11.293a.999.999 0 1 1-1.414 1.414l-1-1a.999.999 0 1 1 1.414-1.414Zm4 1.414a.999.999 0 1 1-1.414-1.414l1-1a.999.999 0 1 1 1.414 1.414ZM12.01 17a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.tncq_b45v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3a1.002 1.002 0 0 1 1.707-.707L9.414 6h5.172l3.707-3.707A1 1 0 0 1 20 3v5.586l1.707 1.707a1 1 0 0 1 0 1.414L20.414 13l1.293 1.293a1 1 0 0 1-.336 1.635l-4.647 1.859l-1.83 3.66A1 1 0 0 1 14 22h-4a1 1 0 0 1-.894-.553l-1.83-3.66l-4.647-1.859a1 1 0 0 1-.336-1.635L3.586 13l-1.293-1.293a1 1 0 0 1 0-1.414L4 8.586Z");
}

</style>
