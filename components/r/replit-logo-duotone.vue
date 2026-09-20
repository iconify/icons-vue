<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="v-4as6dea"/><path class="m1g_51bur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:replit-logo-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m1g_51bur {
  d: path("M216 88h-64V40a16 16 0 0 0-16-16H72a16 16 0 0 0-16 16v48a16 16 0 0 0 16 16h64v48H72a16 16 0 0 0-16 16v48a16 16 0 0 0 16 16h64a16 16 0 0 0 16-16v-48h64a16 16 0 0 0 16-16v-48a16 16 0 0 0-16-16m-80 128H72v-48h64Zm0-176v48H72V40zm80 112h-64v-48h64Z");
}

.v-4as6dea {
  d: path("M72 160h72v56a8 8 0 0 1-8 8H72a8 8 0 0 1-8-8v-48a8 8 0 0 1 8-8m144-64h-72v64h72a8 8 0 0 0 8-8v-48a8 8 0 0 0-8-8m-80-64H72a8 8 0 0 0-8 8v48a8 8 0 0 0 8 8h72V40a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
