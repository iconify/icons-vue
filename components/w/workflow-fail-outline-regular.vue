<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f21or-k3k"/><path class="gujomac1p"/><path class="v0w-kwjac"/><path class="bd2iewblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:workflow-fail-outline-regular" /></template>
<style>
.bd2iewblu {
  d: path("m20 12 -7 7");
}

.f21or-k3k {
  d: path("M2 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.gujomac1p {
  d: path("M6 10v6h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0w-kwjac {
  d: path("m13 12 7 7");
}

</style>
