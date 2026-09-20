<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qad3kqbgr"/><path class="hob4evbuj"/><path class="hrabrxb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:place-search-outline-regular" /></template>
<style>
.hob4evbuj {
  d: path("M9 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hrabrxb6m {
  d: path("M11.5 9.5 15 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qad3kqbgr {
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
}

</style>
