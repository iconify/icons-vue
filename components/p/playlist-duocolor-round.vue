<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z-uthhbdl"/><path class="yhdsbe0jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yhdsbe0jv {
  d: path("M3 6h18M3 12h8m-8 6h8");
}

.z-uthhbdl {
  stroke-opacity: 0.4;
  d: path("M15 12v4c0 .997 1.145 1.57 2 1l3-2a1.202 1.202 0 0 0 0-2l-3-2c-.855-.57-2 .003-2 1");
}

</style>
