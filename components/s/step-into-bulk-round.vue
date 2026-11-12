<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zo-37vb0x"/><path class="my0qmcc3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:step-into-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.my0qmcc3d {
  d: path("m13 10.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L11 10.586V3a1 1 0 0 1 2 0Z");
}

.zo-37vb0x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.236 17.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

</style>
