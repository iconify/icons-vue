<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="k_fcqwbrx"/><path class="h6-9uee7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sign-in-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h6-9uee7z {
  d: path("m141.66 133.66l-40 40a8 8 0 0 1-11.32-11.32L116.69 136H24a8 8 0 0 1 0-16h92.69L90.34 93.66a8 8 0 0 1 11.32-11.32l40 40a8 8 0 0 1 0 11.32M200 32h-64a8 8 0 0 0 0 16h56v160h-56a8 8 0 0 0 0 16h64a8 8 0 0 0 8-8V40a8 8 0 0 0-8-8");
}

.k_fcqwbrx {
  d: path("M200 40v176H40a16 16 0 0 1-16-16V56a16 16 0 0 1 16-16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
