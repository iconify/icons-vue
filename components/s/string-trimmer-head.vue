<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zl24vkbix"/><path class="qlp2dabxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:string-trimmer-head" /></template>
<style>
.qlp2dabxx {
  d: path("M10 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8 0c1.5 0 3 1 3.5 2.5M6 13.5c-1.5 0-3-1-3.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zl24vkbix {
  d: path("M6 13.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm6-6V3");
}

</style>
