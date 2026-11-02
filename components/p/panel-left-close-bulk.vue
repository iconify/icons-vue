<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nu45ocbzb"/><path class="ty4cb4bzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nu45ocbzb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 3a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3Z");
}

.ty4cb4bzm {
  d: path("M10 4v16a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0m7.707 5.707L15.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414");
}

</style>
