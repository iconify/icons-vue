<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nnzlfsekh"/><path class="w28ybhbjm"/><path class="g85aieyzp"/><path class="e3dol68is"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metric-card-outline-regular" /></template>
<style>
.e3dol68is {
  d: path("M15 11v3");
}

.g85aieyzp {
  d: path("M11 9v5");
}

.nnzlfsekh {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w28ybhbjm {
  d: path("M7 10v4");
}

</style>
