<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mjl0m97gs"/><path class="iihfrlmdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-host" /></template>
<style>
.iihfrlmdk {
  d: path("M7.75 10.25a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM5 21.5c0-1.5 3-2.75 7-2.75s7 1.25 7 2.75m-1.25-8.25a2.5 2.5 0 0 1-2.5 2.5");
}

.mjl0m97gs {
  d: path("M6.25 8.25a5.75 5.75 0 0 1 11.5 0m-13 0h3v5h-3Zm11.5 0h3v5h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
