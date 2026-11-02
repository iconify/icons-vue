<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="riisj1nkm"/><path class="m5e3v6b2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plus-minus-duocolor-sharp" /></template>
<style>
.m5e3v6b2t {
  d: path("M6 10h12m-6-6v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.riisj1nkm {
  stroke-opacity: 0.4;
  d: path("M6 20h12");
}

</style>
