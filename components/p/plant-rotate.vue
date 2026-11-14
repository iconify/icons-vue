<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qw2gqobqj"/><path class="llo3vibby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-rotate" /></template>
<style>
.llo3vibby {
  d: path("m17.5 17.25l-.75 3l3 .75");
}

.qw2gqobqj {
  d: path("M4 15h10l-1 6H5Zm5 0v-5m0 0c0-3-2-5-5-5c0 3 2 5 5 5Zm0 0c0-2.5 1.5-4.5 4.5-4.5C13.5 8 11.75 9.75 9 10Zm7.75-6.227a9.5 9.5 0 0 1 0 16.454");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
