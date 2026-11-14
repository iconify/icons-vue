<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jw_3cj0ru"/><path class="z0h8v-qvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:text-translate" /></template>
<style>
.jw_3cj0ru {
  d: path("m3.5 12.5l4-8.5l4 8.5M5 9.5h5m3.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6-3v6M14 4h3a2.5 2.5 0 0 1 2.5 2.5v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z0h8v-qvv {
  d: path("m18 8l1.5 1.5L21 8");
}

</style>
