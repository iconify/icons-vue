<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="mx9l0ccbj"/><path class="cvaixh1ux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rainbow-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cvaixh1ux {
  d: path("M184 168v16a8 8 0 0 1-16 0v-16a40 40 0 0 0-80 0v16a8 8 0 0 1-16 0v-16a56 56 0 0 1 112 0m-56-88a88.1 88.1 0 0 0-88 88v16a8 8 0 0 0 16 0v-16a72 72 0 0 1 144 0v16a8 8 0 0 0 16 0v-16a88.1 88.1 0 0 0-88-88m0-32A120.13 120.13 0 0 0 8 168v16a8 8 0 0 0 16 0v-16a104 104 0 0 1 208 0v16a8 8 0 0 0 16 0v-16A120.13 120.13 0 0 0 128 48");
}

.mx9l0ccbj {
  d: path("M240 168v16h-64v-16a48 48 0 0 0-96 0v16H16v-16a112 112 0 0 1 224 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
