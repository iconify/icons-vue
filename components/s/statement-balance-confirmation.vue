<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s39lbabuq"/><path class="qdlwxtb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-balance-confirmation" /></template>
<style>
.qdlwxtb3y {
  d: path("M7.5 11.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm5 0H16M8 15.5h3m3.75 2.5l2 2L21 15.75");
}

.s39lbabuq {
  d: path("M14.3 21.5H4.5v-19h15v10.8m0 7.9v.3h-.3M8 6.5h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
