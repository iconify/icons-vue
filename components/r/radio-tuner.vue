<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhuvow97a"/><path class="qjs9-d4kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-tuner" /></template>
<style>
.mhuvow97a {
  d: path("M2.5 5.5h19v13h-19Z");
}

.qjs9-d4kc {
  d: path("M13.75 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-8.5-3.5v2m5.5-2v2M8 8.5v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
