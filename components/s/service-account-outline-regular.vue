<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wlnjwfbkn"/><path class="jtqt-jkjg"/><path class="ptxh1kbpm"/><path class="avdamgajo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:service-account-outline-regular" /></template>
<style>
.avdamgajo {
  d: path("M6 21a6 6 0 0 1 12 0");
}

.jtqt-jkjg {
  d: path("M9 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ptxh1kbpm {
  d: path("M13 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wlnjwfbkn {
  d: path("M7 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
