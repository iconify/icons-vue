<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="il-rnqb5b"/><path class="dr5emhbkc"/><path class="f31g_5bod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speed-limit-20" /></template>
<style>
.dr5emhbkc {
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.f31g_5bod {
  d: path("M8 10.5a1.375 1.375 0 0 1 2.75 0C10.75 12 8 13 8 15h2.75m2.75-6h2.75v6H13.5Z");
}

.il-rnqb5b {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
