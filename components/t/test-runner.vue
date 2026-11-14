<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ib-ky-bwj"/><path class="v7h8rpsds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-runner" /></template>
<style>
.ib-ky-bwj {
  d: path("M19.25 8.25A8.5 8.5 0 1 1 12 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7h8rpsds {
  d: path("m10 2l2 2l-2 2m4 2.5h.01m-1.26 2l-1.5 3.5l2.25 1.5l-.75 2m-1.5-3.5L9 15.5m.25-4.25l3.5-.75l2 2");
}

</style>
