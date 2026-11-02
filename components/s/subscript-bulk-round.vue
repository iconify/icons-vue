<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qnfr3o3ao"/><path class="lcd1pac0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subscript-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lcd1pac0q {
  d: path("m9.414 7l3.293 3.293a.999.999 0 1 1-1.414 1.414L8 8.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414L6.586 7L3.293 3.707a.999.999 0 1 1 1.414-1.414L8 5.586l3.293-3.293a.999.999 0 1 1 1.414 1.414Z");
}

.qnfr3o3ao {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.707 17.707L18.414 20H20a1 1 0 0 1 0 2h-4a1.002 1.002 0 0 1-.707-1.707l3.646-3.646A1.002 1.002 0 0 0 17 17a1 1 0 0 1-2 0a3.001 3.001 0 0 1 6 0c0 .265-.105.52-.293.707");
}

</style>
