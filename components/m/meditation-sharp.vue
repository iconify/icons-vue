<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9-7-8-2z"/><path class="yz-s4yb6n"/><path class="tc6jd4byo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meditation-sharp" /></template>
<style>
.e9-7-8-2z {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

.tc6jd4byo {
  d: path("M2.75 18.5v-3h14.5c2.25 0 4 1.25 4 3s-1.75 2.75-4 2.75H2.75zm5.5 0h7.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz-s4yb6n {
  d: path("M11.25 9h3l.34 1.46l.82 3.58l.34 1.46h-7.5l.34-1.46l.82-3.58L9.75 9zM9.5 10l-3 2.75L4.75 16m9.75-6l3 2.75L19.25 16");
}

</style>
