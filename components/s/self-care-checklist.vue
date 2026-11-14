<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zznirxo4v"/><path class="t9w7s7bwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:self-care-checklist" /></template>
<style>
.t9w7s7bwm {
  d: path("M8.5 2.5h7v4h-7ZM7 10l1.25 1.25L10.5 9M7 13.75L8.25 15l2.25-2.25M7 17.5l1.25 1.25l2.25-2.25M13 10h4m-4 3.75h4m-4 3.75h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zznirxo4v {
  d: path("M8.5 4.5H6a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-13a2 2 0 0 0-2-2h-2.5");
}

</style>
