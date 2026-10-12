<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yjcim0p-e"/><path class="kca9ygbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voice-id-sharp" /></template>
<style>
.kca9ygbqt {
  d: path("M15.75 7.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3Zm-2.5 8.75V13.5h5v2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjcim0p-e {
  d: path("M2.75 4.5h18.5v15H2.75zm3 6v3m3-5v7m3-4.5v2");
}

</style>
