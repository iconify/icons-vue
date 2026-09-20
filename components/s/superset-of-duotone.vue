<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mh517eb7p"/><path class="bgxbomtga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:superset-of-duotone" /></template>
<style>
.bgxbomtga {
  d: path("M216 200a8 8 0 0 1-8 8H56a8 8 0 0 1 0-16h152a8 8 0 0 1 8 8m-64-48H56a8 8 0 0 0 0 16h96a64 64 0 0 0 0-128H56a8 8 0 0 0 0 16h96a48 48 0 0 1 0 96");
}

.cuyn6tgcc {
  fill: currentColor;
}

.mh517eb7p {
  d: path("M208 104a56 56 0 0 1-56 56H56V48h96a56 56 0 0 1 56 56");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
