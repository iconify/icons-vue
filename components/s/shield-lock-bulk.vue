<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sf2-14icu"/><path class="ekcojebgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-lock-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ekcojebgp {
  d: path("M16 11v2a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-2c0-.715.38-1.376 1-1.733V9a3 3 0 1 1 6 0v.267A2 2 0 0 1 16 11m-3-2a1 1 0 0 0-2 0Z");
}

.sf2-14icu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2h12a3 3 0 0 1 3 3v5c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5a3 3 0 0 1 3-3");
}

</style>
