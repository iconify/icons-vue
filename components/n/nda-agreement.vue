<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cfekiqlkn"/><path class="r-ntr9b0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nda-agreement" /></template>
<style>
.cfekiqlkn {
  d: path("M2.5 12c3-4.5 7-5 9.5-3.5c2.5-1.5 6.5-1 9.5 3.5c-3 4.5-7 5.5-9.5 5.5s-6.5-1-9.5-5.5Zm2 0h15M7 11v2m2.5-2v2m2.5-2v2m2.5-2v2");
}

.r-ntr9b0i {
  d: path("M16.5 12H19v3.25h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
