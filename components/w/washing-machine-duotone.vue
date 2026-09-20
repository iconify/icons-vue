<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="pu29vvnwl"/><path class="imaenjard"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:washing-machine-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.imaenjard {
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m0 176H48V48h160zM128 64a64 64 0 1 0 64 64a64.07 64.07 0 0 0-64-64m0 112a48 48 0 1 1 48-48a48.05 48.05 0 0 1-48 48m72-108a12 12 0 1 1-12-12a12 12 0 0 1 12 12m-74.34 49.66l-16 16a8 8 0 0 1-11.32-11.32l16-16a8 8 0 0 1 11.32 11.32m32-3.32a8 8 0 0 1 0 11.32l-32 32a8 8 0 0 1-11.32-11.32l32-32a8 8 0 0 1 11.32 0");
}

.pu29vvnwl {
  d: path("M184 128a56 56 0 1 1-56-56a56 56 0 0 1 56 56");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
