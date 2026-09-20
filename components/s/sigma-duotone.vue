<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fchcbmbrf"/><path class="d13n7pfpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sigma-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d13n7pfpp {
  d: path("M184 72V56H80.65l53.6 67a8 8 0 0 1 0 10l-53.6 67H184v-16a8 8 0 0 1 16 0v24a8 8 0 0 1-8 8H64a8 8 0 0 1-6.25-13l60-75l-60-75A8 8 0 0 1 64 40h128a8 8 0 0 1 8 8v24a8 8 0 0 1-16 0");
}

.fchcbmbrf {
  d: path("M192 48v160H64l64-80l-64-80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
