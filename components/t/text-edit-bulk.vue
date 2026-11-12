<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wj0ocrb0s"/><path class="owipazk1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-edit-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.owipazk1p {
  d: path("m15.707 5.293l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.999.999 0 1 1 1.414-1.414m-10.414 12a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L6 19.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414ZM21 22h-8a1 1 0 0 1 0-2h8a1 1 0 0 1 0 2");
}

.wj0ocrb0s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 12c0-.265.105-.52.293-.707l8-8a2.414 2.414 0 0 1 3.414 0l1 1a2.414 2.414 0 0 1 0 3.414l-8 8A1 1 0 0 1 12 16H9a1 1 0 0 1-1-1Z");
}

</style>
