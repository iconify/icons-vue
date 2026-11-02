<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g9i4yiffc"/><path class="mlth9vbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:superscript-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g9i4yiffc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.707 5.707L18.414 8H20a1 1 0 0 1 0 2h-4a1.002 1.002 0 0 1-.707-1.707l3.646-3.646A1.002 1.002 0 0 0 17 5a1 1 0 0 1-2 0a3.001 3.001 0 0 1 6 0c0 .265-.105.52-.293.707");
}

.mlth9vbtv {
  d: path("m8 15.586l3.293-3.293a.999.999 0 1 1 1.414 1.414L9.414 17l3.293 3.293a.999.999 0 1 1-1.414 1.414L8 18.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414L6.586 17l-3.293-3.293a.999.999 0 1 1 1.414-1.414Z");
}

</style>
