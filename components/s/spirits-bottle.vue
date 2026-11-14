<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ff6lsop8u"/><path class="vi97vpbrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spirits-bottle" /></template>
<style>
.ff6lsop8u {
  d: path("M6.5 11A2.5 2.5 0 0 1 9 8.5h1v-3h4v3h1a2.5 2.5 0 0 1 2.5 2.5v8.5a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2Zm3.75-8.5h3.5v3h-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vi97vpbrc {
  d: path("M9.5 13h5v5h-5Z");
}

</style>
