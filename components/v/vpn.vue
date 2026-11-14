<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r8a9qcmsq"/><path class="m9f7w4b9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vpn" /></template>
<style>
.m9f7w4b9m {
  d: path("M7.5 10.5a3 7.5 0 1 0 6 0a3 7.5 0 1 0-6 0Zm-4.5 0h15M15 17h6v4.5h-6Zm1.25 0v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.r8a9qcmsq {
  d: path("M11.154 17.971a7.5 7.5 0 1 1 6.817-6.817");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
