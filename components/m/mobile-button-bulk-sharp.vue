<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m1ausq56u"/><path class="zenlmhbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-button-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m1ausq56u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

.zenlmhbbk {
  d: path("M12 17h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
