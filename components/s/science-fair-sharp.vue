<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kccu0ubsp"/><path class="qoetznbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:science-fair-sharp" /></template>
<style>
.kccu0ubsp {
  d: path("M6.75 3.75h10.5v14H6.75zm0 2l-3.1 1.2l-.9.263v8.537l.003 1.06l1.047.17l2.95.77m10.5-12l3.1 1.2l.9.263v8.537l-.003 1.06l-1.047.17l-2.95.77");
}

.qoetznbth {
  d: path("M11.25 7h1.5v2.75l1.75 3.5l.736 1.461L13.6 14.7h-3.2l-1.636.011l.736-1.461l1.75-3.5Zm-8.5 14h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
