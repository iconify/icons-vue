<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dxl_10b1n"/><path class="nol9hdroo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dxl_10b1n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 16a4 4 0 1 1 8 0a4 4 0 0 1-8 0M2 18a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

.nol9hdroo {
  d: path("M8 9c0-1.737.989-3.465 2.725-3.962l7-2c1.737-.495 3.31.673 3.945 2.243c.22.546.332 1.13.33 1.719v9a1 1 0 0 1-2 0V7a2.6 2.6 0 0 0-.185-.97c-.237-.587-.832-1.271-1.54-1.068l-7 2c-.374.106-.674.361-.887.68A2.44 2.44 0 0 0 10 9v9a1 1 0 0 1-2 0Z");
}

</style>
