<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dtro9rbwa"/><path class="ph0fcs29q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-close-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dtro9rbwa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.874 1.514l10 18A1 1 0 0 1 22 21H2a1 1 0 0 1-.874-1.486l10-18a1 1 0 0 1 1.748 0");
}

.ph0fcs29q {
  d: path("M10.707 11.293L12 12.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 15.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
