<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tlao474nk"/><path class="i1afylb7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-dog-cover" /></template>
<style>
.i1afylb7a {
  d: path("M10.5 3.5c-2.5 1.25-3.25 5-2.75 9c1.5.75 2.75-.5 3.25-2.5m2.5-2h.01");
}

.tlao474nk {
  d: path("M5.25 21.5c-1.5-4.5-2-9.5-.5-13.5C6 4.75 8.5 3.5 11.25 3.5c2.25 0 3.75 1.25 4.5 3.5l3.5 1c1.25.5 1.75 1.25 1.5 2.5l-.25 1c-.25 1-1 1.5-2 1.5h-3.25c-1.75 1.75-3 4.5-3 8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
