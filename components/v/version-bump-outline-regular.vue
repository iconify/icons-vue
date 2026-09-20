<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yq5pecxxv"/><path class="qyslyhbbq"/><path class="nbo3zob7q"/><path class="g5_a6d0kj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:version-bump-outline-regular" /></template>
<style>
.g5_a6d0kj {
  d: path("m14.5 10 2 -2 2 2");
}

.nbo3zob7q {
  d: path("M16.5 8v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qyslyhbbq {
  d: path("M13 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.yq5pecxxv {
  d: path("M2 12a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
