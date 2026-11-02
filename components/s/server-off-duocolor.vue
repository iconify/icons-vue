<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e72o9db0j"/><path class="rzj1uuier"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-duocolor" /></template>
<style>
.e72o9db0j {
  stroke-opacity: 0.4;
  d: path("M7 17h.01M2 2l20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rzj1uuier {
  d: path("M10 10H5a2 2 0 0 1-2-2V6c0-.811.306-1.686 1-2m6 0h9a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-3m4 10c-.251.114-.707 0-1 0H5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h9");
}

</style>
