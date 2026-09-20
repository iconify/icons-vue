<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="hvlyykxck"/><path class="kj5sq8cet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sock-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hvlyykxck {
  d: path("M200 112v33.37a16 16 0 0 1-4.69 11.32l-33 33A48 48 0 0 1 200 112m-8-88h-88a8 8 0 0 0-8 8v24h104V32a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kj5sq8cet {
  d: path("M192 16h-88a16 16 0 0 0-16 16v76.69l-38.75 38.74a58.92 58.92 0 0 0 83.32 83.32L201 162.34a23.85 23.85 0 0 0 7-17V32a16 16 0 0 0-16-16m0 16v16h-88V32Zm-70.75 187.43a42.91 42.91 0 1 1-60.68-60.68l41.09-41.09A8 8 0 0 0 104 112V64h88v40.58A56.09 56.09 0 0 0 144 160a55.4 55.4 0 0 0 7.93 28.76ZM189.66 151l-25.91 25.91A39.6 39.6 0 0 1 160 160a40.05 40.05 0 0 1 32-39.19v24.56a8 8 0 0 1-2.34 5.63");
}

</style>
