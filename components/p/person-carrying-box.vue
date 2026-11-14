<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gznll4-ip"/><path class="zvc50jbfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-carrying-box" /></template>
<style>
.gznll4-ip {
  d: path("M6 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1 16v-7A3.5 3.5 0 0 1 8.5 11h3m0-1.5h9V18h-9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvc50jbfl {
  d: path("M8 14v2h3.5m1 2v3.5m3.5-12v3");
}

</style>
