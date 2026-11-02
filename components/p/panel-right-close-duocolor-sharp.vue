<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s6b_nxbdr"/><path class="fx3dyzbmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-close-duocolor-sharp" /></template>
<style>
.fx3dyzbmz {
  d: path("M4 4h16v16H4Zm11 0v16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s6b_nxbdr {
  stroke-opacity: 0.4;
  d: path("m8 15l3-3l-3-3");
}

</style>
