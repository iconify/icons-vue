<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0njbhb3m"/><path class="bbajcnbwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reptile-hide" /></template>
<style>
.bbajcnbwo {
  d: path("M3 12a2.5 6 0 1 0 5 0a2.5 6 0 1 0-5 0Zm8 6v-3a3 3 0 0 1 6 0v3");
}

.i0njbhb3m {
  d: path("M5.5 6h13a2.5 6 0 0 1 0 12h-13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
