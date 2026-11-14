<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t23wj5bni"/><path class="d7-dvsb5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vr-headset-wireless" /></template>
<style>
.d7-dvsb5s {
  d: path("M5.25 13.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm7 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm4.25-8.75a2.5 2.5 0 0 1 2.5 2.5M16.5 2a5.25 5.25 0 0 1 5.25 5.25");
}

.t23wj5bni {
  d: path("M5 9h11a2.5 2.5 0 0 1 2.5 2.5v6A2.5 2.5 0 0 1 16 20h-3a2.5 2.5 0 0 0-5 0H5a2.5 2.5 0 0 1-2.5-2.5v-6A2.5 2.5 0 0 1 5 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
