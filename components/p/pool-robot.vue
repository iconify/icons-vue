<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s53c88bta"/><path class="r6p525n_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pool-robot" /></template>
<style>
.r6p525n_t {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.25-7.5H21m0-3v6M7.5 5.5v-1A1.5 1.5 0 0 1 9 3h3a1.5 1.5 0 0 1 1.5 1.5v1");
}

.s53c88bta {
  d: path("M3.5 5.5h13.75a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H3.5a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
