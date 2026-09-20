<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hidfxz0es"/><path class="hcqw_hf6u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:question-mark-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hcqw_hf6u {
  d: path("M192 96c0 28.51-24.47 52.11-56 55.56V160a8 8 0 0 1-16 0v-16a8 8 0 0 1 8-8c26.47 0 48-17.94 48-40s-21.53-40-48-40s-48 17.94-48 40a8 8 0 0 1-16 0c0-30.88 28.71-56 64-56s64 25.12 64 56m-64 96a16 16 0 1 0 16 16a16 16 0 0 0-16-16");
}

.hidfxz0es {
  d: path("M216 40v176a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V40a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
