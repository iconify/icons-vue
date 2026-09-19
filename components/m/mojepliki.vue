<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vhiovobfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mojepliki" /></template>
<style>
.vhiovobfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 13.044H24.77c-1.963-.108-5.931-4.238-8.188-4.238H6.68v-.001a2.176 2.176 0 0 0-2.18 2.171v7.307m6.18 20.912h30.64a2.176 2.176 0 0 0 2.18-2.171V18.283h-27m-12 0v20.912");
}

</style>
