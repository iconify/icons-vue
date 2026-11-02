<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ehiseh6_n"/><path class="k18y86g-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallbox-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ehiseh6_n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm14 3a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

.k18y86g-z {
  d: path("M9.707 6.707L8.414 8H10a1.002 1.002 0 0 1 .707 1.707l-3 3a.999.999 0 1 1-1.414-1.414L7.586 10H6a1.002 1.002 0 0 1-.707-1.707l3-3a.999.999 0 1 1 1.414 1.414M9 15v2a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1v-4a1 1 0 0 1 2 0v4a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0");
}

</style>
