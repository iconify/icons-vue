<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sju9b47kv"/><path class="lin5xkb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-duocolor" /></template>
<style>
.lin5xkb-l {
  d: path("M6 6v13a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V6M4 6h16M8 6V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sju9b47kv {
  stroke-opacity: 0.4;
  d: path("M10 10v7m4-7v7");
}

</style>
