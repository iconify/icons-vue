<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e3xlw3esn"/><path class="bndddt2vm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-duocolor-sharp" /></template>
<style>
.bndddt2vm {
  d: path("M10 6h7l3 3l-3 3H4V6z");
}

.e3xlw3esn {
  stroke-opacity: 0.4;
  d: path("M12 3v3m0 6v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
