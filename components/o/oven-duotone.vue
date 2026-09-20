<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wa1ojwbgv"/><path class="waruxkbpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:oven-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wa1ojwbgv {
  d: path("M184 112v72H72v-72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.waruxkbpl {
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m0 176H48V48h160zM72 76a12 12 0 1 1 12 12a12 12 0 0 1-12-12m44 0a12 12 0 1 1 12 12a12 12 0 0 1-12-12m44 0a12 12 0 1 1 12 12a12 12 0 0 1-12-12m24 28H72a8 8 0 0 0-8 8v72a8 8 0 0 0 8 8h112a8 8 0 0 0 8-8v-72a8 8 0 0 0-8-8m-8 72H80v-56h96Z");
}

</style>
