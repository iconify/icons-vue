<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="t0_wgvzrl"/><path class="ny_8c3c9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tea-bag-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ny_8c3c9z {
  d: path("M224 160a16 16 0 0 1-16-16V64a56 56 0 0 0-112 0v8H76.53a16.09 16.09 0 0 0-13.72 7.77L42.28 114a16.06 16.06 0 0 0-2.28 8.22V216a16 16 0 0 0 16 16h96a16 16 0 0 0 16-16v-93.78a16.06 16.06 0 0 0-2.28-8.24l-20.53-34.21A16.09 16.09 0 0 0 131.47 72H112v-8a40 40 0 0 1 80 0v80a32 32 0 0 0 32 32a8 8 0 0 0 0-16m-92.53-72L152 122.22V216H56v-93.78L76.53 88H96v48a8 8 0 0 0 16 0V88Z");
}

.t0_wgvzrl {
  d: path("M160 122.22V216a8 8 0 0 1-8 8H56a8 8 0 0 1-8-8v-93.78a8 8 0 0 1 1.14-4.12l20.53-34.22A8 8 0 0 1 76.53 80h54.94a8 8 0 0 1 6.86 3.88l20.53 34.22a8 8 0 0 1 1.14 4.12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
