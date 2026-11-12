<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sgnwlo5xs"/><path class="noe1vbbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.noe1vbbmn {
  d: path("M13 19v-4a1 1 0 0 1 2 0v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L16.414 18H18a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1");
}

.sgnwlo5xs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H11a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1ZM7 10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1Z");
}

</style>
