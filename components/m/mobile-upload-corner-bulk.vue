<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g1sh-zeaw"/><path class="nye7ypq7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-upload-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g1sh-zeaw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 11h-1a.997.997 0 0 0-1 1v9a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v5a1 1 0 0 1-1 1");
}

.nye7ypq7n {
  d: path("M18 15.414V21a1 1 0 0 1-2 0v-5.586l-1.293 1.293a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414Z");
}

</style>
