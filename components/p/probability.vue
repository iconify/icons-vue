<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o052dmbzp"/><path class="qv39mta-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:probability" /></template>
<style>
.o052dmbzp {
  d: path("M7.5 12a4.5 8.5 0 1 0 9 0a4.5 8.5 0 1 0-9 0Z");
}

.qv39mta-v {
  d: path("M10 12a2 5.25 0 1 0 4 0a2 5.25 0 1 0-4 0Zm7.592-7.987a9.75 9.75 0 0 1 3.826 5.464m-15.01 10.51a9.75 9.75 0 0 1-3.826-5.464");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
