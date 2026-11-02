<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eu1hj9bcg"/><path class="qyf3a35ct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tram-side-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eu1hj9bcg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6h7a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Zm-8 5h3V8H5a1 1 0 0 0-1 1Zm5 0h3V8H9Zm5 0h6V9a1 1 0 0 0-1-1h-5Z");
}

.qyf3a35ct {
  d: path("M15 2a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0V4H9a1 1 0 0 1 0-2Zm6 18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
