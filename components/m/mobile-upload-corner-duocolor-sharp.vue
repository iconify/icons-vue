<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nv473kb_y"/><path class="nwtk29f6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-upload-corner-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nv473kb_y {
  stroke-opacity: 0.4;
  d: path("m20 16l-3-3l-3 3m3-3v8");
}

.nwtk29f6q {
  d: path("M3 12V3h10v7m-3 11H3v-9");
}

</style>
