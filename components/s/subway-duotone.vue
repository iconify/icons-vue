<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wydbc6s1p"/><path class="z84tt9i0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subway-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wydbc6s1p {
  d: path("M152 32h-48a64 64 0 0 0-64 64v112h176V96a64 64 0 0 0-64-64m24 136a16 16 0 0 1-16 16H96a16 16 0 0 1-16-16V96a16 16 0 0 1 16-16h64a16 16 0 0 1 16 16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z84tt9i0w {
  d: path("M224 96v112a8 8 0 0 1-16 0V96a56.06 56.06 0 0 0-56-56h-48a56.06 56.06 0 0 0-56 56v112a8 8 0 0 1-16 0V96a72.08 72.08 0 0 1 72-72h48a72.08 72.08 0 0 1 72 72m-40 0v72a24 24 0 0 1-19.29 23.53l2.45 4.89a8 8 0 0 1-14.32 7.16L147.06 192h-38.12l-5.78 11.58a8 8 0 0 1-14.32-7.16l2.45-4.89A24 24 0 0 1 72 168V96a24 24 0 0 1 24-24h64a24 24 0 0 1 24 24m-96 0v48h80V96a8 8 0 0 0-8-8H96a8 8 0 0 0-8 8m32 64v16h16v-16Zm-24 16h8v-16H88v8a8 8 0 0 0 8 8m72-8v-8h-16v16h8a8 8 0 0 0 8-8");
}

</style>
