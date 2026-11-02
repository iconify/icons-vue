<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ach8j2bjb"/><path class="ly4mftb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-bulk-round" /></template>
<style>
.ach8j2bjb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.781 4.672A4 4 0 0 1 21 8v8a4 4 0 0 1-6.219 3.328l-6-4a4 4 0 0 1 0-6.656Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ly4mftb3k {
  d: path("M5 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

</style>
