<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j3k8n70yi"/><path class="wx7ogdbqc"/><path class="xug64tbnj"/><path class="pt-3kkb2k"/><path class="ae0h5kb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quest-duotone-regular" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.j3k8n70yi {
  fill: currentColor;
  d: path("M6 4v16h12V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.wx7ogdbqc {
  d: path("M6 4v16h12V4Z");
}

.xug64tbnj {
  d: path("M6 4C4 4 4 8 6 8");
}

</style>
