<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c5icmybsm"/><path class="ozx545qvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:signed-release-outline-regular" /></template>
<style>
.c5icmybsm {
  d: path("m4 12 6 -6h10v12H10Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozx545qvz {
  d: path("m11 12 2 2 4 -4");
}

</style>
