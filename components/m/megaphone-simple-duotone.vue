<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rsxxw_90u"/><path class="iueajva_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:megaphone-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iueajva_z {
  d: path("m228.54 86.66l-176.06-54A16 16 0 0 0 32 48v144a16 16 0 0 0 16 16a16 16 0 0 0 4.52-.65L136 181.73V192a16 16 0 0 0 16 16h32a16 16 0 0 0 16-16v-29.9l28.54-8.75A16.09 16.09 0 0 0 240 138v-36a16.09 16.09 0 0 0-11.46-15.34M136 165l-88 27V48l88 27Zm48 27h-32v-15.18l32-9.82Zm40-54h-.11L152 160.08V79.92l71.89 22h.11v36Z");
}

.rsxxw_90u {
  d: path("M144 69.09v101.82l-93.76 28.76A8 8 0 0 1 40 192V48a8 8 0 0 1 10.24-7.67Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
