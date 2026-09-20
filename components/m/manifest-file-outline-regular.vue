<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tks4a4biu"/><path class="lgr612izs"/><path class="fhluz1bdh"/><path class="i6r7zygac"/><path class="wyp7k2b7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:manifest-file-outline-regular" /></template>
<style>
.fhluz1bdh {
  d: path("M11 12h5");
}

.i6r7zygac {
  d: path("M8 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.lgr612izs {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tks4a4biu {
  d: path("M13 3H6v18h12V8Z");
}

.wyp7k2b7p {
  d: path("M11 16h5");
}

</style>
