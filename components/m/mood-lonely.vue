<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sw_b1nbrc"/><path class="di4bbsbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-lonely" /></template>
<style>
.di4bbsbbm {
  d: path("M16.5 20q1.5-1.5 3 0");
}

.sw_b1nbrc {
  d: path("M5.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3 14c0-4.5 3-7 7-7c1.148 0 2.213.206 3.148.605M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm2.25-1.25h.01m2.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
