<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="irspgly1g"/><path class="v7pxfosqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.irspgly1g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.707 10.293l4 4a1 1 0 0 1 0 1.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a1 1 0 0 1 1.414 0");
}

.v7pxfosqi {
  d: path("m16.707 3.293l4 4a.999.999 0 1 1-1.414 1.414L18 7.414L16.414 9l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 12.414l-5.293 5.293a2.414 2.414 0 0 1-3.414 0L8 17.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414L6.586 16l-.293-.293a2.414 2.414 0 0 1 0-3.414L11.586 7l-.293-.293a.999.999 0 1 1 1.414-1.414L15 7.586L16.586 6l-1.293-1.293a.999.999 0 1 1 1.414-1.414M13 8.414l-5.293 5.293a.414.414 0 0 0 0 .586l2 2a.414.414 0 0 0 .586 0L15.586 11Z");
}

</style>
