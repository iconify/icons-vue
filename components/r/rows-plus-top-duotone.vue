<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="p6-wodb_m"/><path class="t2nbx65ge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rows-plus-top-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p6-wodb_m {
  d: path("M216 176v24a8 8 0 0 1-8 8H48a8 8 0 0 1-8-8v-24a8 8 0 0 1 8-8h160a8 8 0 0 1 8 8m-8-80H48a8 8 0 0 0-8 8v24a8 8 0 0 0 8 8h160a8 8 0 0 0 8-8v-24a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t2nbx65ge {
  d: path("M208 160H48a16 16 0 0 0-16 16v24a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16v-24a16 16 0 0 0-16-16m0 40H48v-24h160zm0-112H48a16 16 0 0 0-16 16v24a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16v-24a16 16 0 0 0-16-16m0 40H48v-24h160zM96 40a8 8 0 0 1 8-8h16V16a8 8 0 0 1 16 0v16h16a8 8 0 0 1 0 16h-16v16a8 8 0 0 1-16 0V48h-16a8 8 0 0 1-8-8");
}

</style>
