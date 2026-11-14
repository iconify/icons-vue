<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n2u2d5b3w"/><path class="jmpot0bdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-alert-tag" /></template>
<style>
.jmpot0bdt {
  d: path("M9.25 11h5.5A2.25 2.25 0 0 1 17 13.25v5a2.25 2.25 0 0 1-2.25 2.25h-5.5A2.25 2.25 0 0 1 7 18.25v-5A2.25 2.25 0 0 1 9.25 11ZM12 13.25v5m-2.5-2.5h5");
}

.n2u2d5b3w {
  d: path("M7 14.25c-2.75-1-4.5-2.75-4.5-4.75c0-3.25 4.25-6 9.5-6s9.5 2.75 9.5 6c0 2-1.75 3.75-4.5 4.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
