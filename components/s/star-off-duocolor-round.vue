<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p52u7fomt"/><path class="z_5r16mkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-off-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p52u7fomt {
  stroke-opacity: 0.4;
  d: path("m2 3l19 19");
}

.z_5r16mkm {
  d: path("m11 5l1-2l3 6l7 1l-3 3m-1.4 5.6L18 21l-6-3l-6 3l1-6l-5-5l6.125-.875");
}

</style>
