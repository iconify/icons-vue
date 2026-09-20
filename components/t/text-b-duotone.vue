<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="pxz9e3kpk"/><path class="kvz21zbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-b-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kvz21zbuk {
  d: path("M178.48 115.7A44 44 0 0 0 148 40H80a8 8 0 0 0-8 8v152a8 8 0 0 0 8 8h80a48 48 0 0 0 18.48-92.3M88 56h60a28 28 0 0 1 0 56H88Zm72 136H88v-64h72a32 32 0 0 1 0 64");
}

.pxz9e3kpk {
  d: path("M200 160a40 40 0 0 1-40 40H80V48h68a36 36 0 0 1 0 72h12a40 40 0 0 1 40 40");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
