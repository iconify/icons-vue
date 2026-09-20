<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vp4_qkipl"/><path class="cmvo-_bow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:video-conference-duotone" /></template>
<style>
.cmvo-_bow {
  d: path("M216 40H40a16 16 0 0 0-16 16v144a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16m0 80h-48V56h48ZM40 56h112v144H40Zm176 144h-48v-64h48zM180 88a12 12 0 1 1 12 12a12 12 0 0 1-12-12m24 80a12 12 0 1 1-12-12a12 12 0 0 1 12 12m-68.25-2a39.76 39.76 0 0 0-17.19-23.34a32 32 0 1 0-45.12 0A39.84 39.84 0 0 0 56.25 166a8 8 0 0 0 15.5 4c2.64-10.25 13.06-18 24.25-18s21.62 7.73 24.25 18a8 8 0 1 0 15.5-4M80 120a16 16 0 1 1 16 16a16 16 0 0 1-16-16");
}

.cuyn6tgcc {
  fill: currentColor;
}

.vp4_qkipl {
  d: path("M40 48a8 8 0 0 0-8 8v144a8 8 0 0 0 8 8h120V48Zm56 96a24 24 0 1 1 24-24a24 24 0 0 1-24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
