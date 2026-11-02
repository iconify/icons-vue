<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h3k3f5whw"/><path class="cmaa2qbld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-duocolor-sharp" /></template>
<style>
.cmaa2qbld {
  d: path("m11 8l10-5v16l-10-5zm0 0H3v6h8");
}

.h3k3f5whw {
  stroke-opacity: 0.4;
  d: path("M5 14v7h4v-7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
