<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dmfpm2rbl"/><circle class="upu83lbfh"/><path class="kwt9vubhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pay-later-sharp" /></template>
<style>
.dmfpm2rbl {
  d: path("M11.75 18.75h-9V5.25h18.5v6m-18.5-2h18.5");
}

.kwt9vubhj {
  d: path("M17 14.75V17h2");
}

.upu83lbfh {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
