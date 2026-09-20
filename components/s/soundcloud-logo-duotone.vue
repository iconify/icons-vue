<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="x3xk9pwyb"/><path class="tlzcezbbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:soundcloud-logo-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tlzcezbbr {
  d: path("M24 120v48a8 8 0 0 1-16 0v-48a8 8 0 0 1 16 0m24-32a8 8 0 0 0-8 8v96a8 8 0 0 0 16 0V96a8 8 0 0 0-8-8m32-8a8 8 0 0 0-8 8v104a8 8 0 0 0 16 0V88a8 8 0 0 0-8-8m32-32a8 8 0 0 0-8 8v136a8 8 0 0 0 16 0V56a8 8 0 0 0-8-8m110.84 58.34A80 80 0 0 0 144 40a8 8 0 0 0 0 16a63.76 63.76 0 0 1 63.68 57.53a8 8 0 0 0 6.44 7A32 32 0 0 1 208 184h-64a8 8 0 0 0 0 16h64a48 48 0 0 0 14.84-93.66");
}

.x3xk9pwyb {
  d: path("M248 152a40 40 0 0 1-40 40h-64V48a72 72 0 0 1 71.64 64.73A40 40 0 0 1 248 152");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
