<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="gpyfylzod"/><path class="m_dlj9b6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:union-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gpyfylzod {
  d: path("M200 64v80a72 72 0 0 1-144 0V64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m_dlj9b6m {
  d: path("M208 64v80a80 80 0 0 1-160 0V64a8 8 0 0 1 16 0v80a64 64 0 0 0 128 0V64a8 8 0 0 1 16 0");
}

</style>
