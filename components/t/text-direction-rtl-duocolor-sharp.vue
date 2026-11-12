<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tpoubkban"/><path class="vy3fg0adm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-direction-rtl-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tpoubkban {
  stroke-opacity: 0.4;
  d: path("m6 15l-3 3l3 3m-3-3h18");
}

.vy3fg0adm {
  d: path("M11 3h6m-5 0v8m4-8v8m-5-8a3 3 0 0 0 0 6h1");
}

</style>
