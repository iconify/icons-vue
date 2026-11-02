<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t5lwdeoxd"/><path class="qlk438mrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:workflow-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlk438mrc {
  d: path("M3 3h8v8H3Zm10 10h8v8h-8Z");
}

.t5lwdeoxd {
  stroke-opacity: 0.4;
  d: path("M7 11v6h6");
}

</style>
