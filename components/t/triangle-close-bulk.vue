<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q_ntab3ct"/><path class="ph0fcs29q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ph0fcs29q {
  d: path("M10.707 11.293L12 12.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 15.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.q_ntab3ct {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m14.591 4.488l7 12A2.999 2.999 0 0 1 19 21H5a2.999 2.999 0 0 1-2.591-4.512l7-12a3 3 0 0 1 5.182 0");
}

</style>
