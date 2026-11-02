<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ft036dbav"/><path class="yhz-zccdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-1-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ft036dbav {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 9a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-8 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.yhz-zccdk {
  d: path("M3 8h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m15 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2M6 14a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm4 0h11a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2");
}

</style>
