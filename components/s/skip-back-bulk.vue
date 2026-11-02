<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cem457b5p"/><path class="ly4mftb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-bulk" /></template>
<style>
.cem457b5p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.41 4.456A2.999 2.999 0 0 1 21 7v10a3 3 0 0 1-4.59 2.544l-8-5a3 3 0 0 1 0-5.088Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ly4mftb3k {
  d: path("M5 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

</style>
