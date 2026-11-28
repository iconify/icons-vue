<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="actlb520u"/><path class="knxh9-cgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-variable-two-tone" /></template>
<style>
.actlb520u {
  stroke-opacity: 0.4;
  d: path("M6 6L6 5C6 3.8954 6.8954 3 8 3L16 3C17.1046 3 18 3.8954 18 5L18 6M12 3L12 11M9 11L15 11M3 18L13 18M21 18L17 18");
}

.knxh9-cgx {
  d: path("M17 15L17 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
