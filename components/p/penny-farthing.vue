<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="am3rabbto"/><path class="smlgng2al"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:penny-farthing" /></template>
<style>
.am3rabbto {
  d: path("M6 12a8 8 0 1 0 16 0a8 8 0 1 0-16 0Zm-3.5 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM14 12h.01");
}

.smlgng2al {
  d: path("M4.5 19c0-8 2.5-14 7-14.75M9.5 3h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
