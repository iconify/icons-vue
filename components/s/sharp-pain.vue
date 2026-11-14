<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uf0ine87u"/><path class="ojdjtbvcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sharp-pain" /></template>
<style>
.ojdjtbvcd {
  fill: currentColor;
  d: path("M11 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.uf0ine87u {
  d: path("M12 9V2.5M12 15v6.5M9 12H2.5M15 12h6.5M14 10l3-3m-3 7l3 3m-7-3l-3 3m3-7L7 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
