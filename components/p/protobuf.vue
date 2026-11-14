<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qizo2mn0q"/><path class="wb5-lbjwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:protobuf" /></template>
<style>
.qizo2mn0q {
  d: path("m7.948 4.112l.187-1.554h1.73l.187 1.554l1.66.688l1.231-.967l1.224 1.224l-.967 1.231l.688 1.66l1.554.187v1.73l-1.554.187l-.688 1.66l.967 1.231l-1.224 1.224l-1.231-.967l-1.66.688l-.187 1.554h-1.73l-.187-1.554l-1.66-.688l-1.231.967l-1.224-1.224l.967-1.231l-.688-1.66l-1.554-.187v-1.73l1.554-.187l.688-1.66l-.967-1.231l1.224-1.224l1.231.967Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wb5-lbjwc {
  d: path("M7 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.372 6.839l.052-1.038h1.152l.052 1.038l.929.537l.925-.474l.576.997l-.873.564v1.074l.873.564l-.576.997l-.925-.474l-.929.537l-.052 1.038h-1.152l-.052-1.038l-.929-.537l-.925.474l-.576-.997l.873-.564v-1.074l-.873-.564l.576-.997l.925.474Z");
}

</style>
