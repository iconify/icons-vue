<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k645rez1q"/><path class="tp_mxlott"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-close-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k645rez1q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m4 17a1 1 0 0 1-1 1H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1Z");
}

.tp_mxlott {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm7.697 7.293L17 15.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L18.414 17l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 18.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L15.586 17l-2.293-2.293a.999.999 0 1 1 1.414-1.414M7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
