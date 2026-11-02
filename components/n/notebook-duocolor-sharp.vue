<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ra9bqhbdv"/><path class="vg_nymjal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notebook-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ra9bqhbdv {
  stroke-opacity: 0.4;
  d: path("M12 8h4m-4 4h4");
}

.vg_nymjal {
  d: path("M4 4h16v16H4Zm4 0v16");
}

</style>
