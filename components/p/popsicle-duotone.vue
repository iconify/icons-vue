<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="kwvy6wbli"/><path class="ymozgdcam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:popsicle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kwvy6wbli {
  d: path("M192 80v96a8 8 0 0 1-8 8H72a8 8 0 0 1-8-8V80a64 64 0 0 1 64-64a64 64 0 0 1 64 64");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymozgdcam {
  d: path("M128 8a72.08 72.08 0 0 0-72 72v96a16 16 0 0 0 16 16h32v40a24 24 0 0 0 48 0v-40h32a16 16 0 0 0 16-16V80a72.08 72.08 0 0 0-72-72m8 224a8 8 0 0 1-16 0v-40h16Zm48-56H72V80a56 56 0 0 1 112 0zM120 72v80a8 8 0 0 1-16 0V72a8 8 0 0 1 16 0m32 0v80a8 8 0 0 1-16 0V72a8 8 0 0 1 16 0");
}

</style>
