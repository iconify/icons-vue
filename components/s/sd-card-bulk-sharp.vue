<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ivlm3ivsq"/><path class="nbiuz816b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sd-card-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ivlm3ivsq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.293 6.293l4-4A1 1 0 0 1 9 2h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V7c0-.265.105-.52.293-.707");
}

.nbiuz816b {
  d: path("M11 10a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm3 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm3 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Z");
}

</style>
