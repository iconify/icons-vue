<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vdmf-5_tq"/><path class="rs6y1caey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:skip-back-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rs6y1caey {
  d: path("M199.81 34a16 16 0 0 0-16.24.43L64 109.23V40a8 8 0 0 0-16 0v176a8 8 0 0 0 16 0v-69.23l119.57 74.78A15.95 15.95 0 0 0 208 208.12V47.88A15.86 15.86 0 0 0 199.81 34M192 208L64.16 128L192 48.07Z");
}

.vdmf-5_tq {
  d: path("M200 47.88v160.24a8 8 0 0 1-12.19 6.65L59.7 134.65a7.83 7.83 0 0 1 0-13.3l128.11-80.12A8 8 0 0 1 200 47.88");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
