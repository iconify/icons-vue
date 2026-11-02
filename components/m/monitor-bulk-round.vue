<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r889qqats"/><path class="m6b9t8bcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m6b9t8bcs {
  d: path("M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.r889qqats {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v5a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5Z");
}

</style>
