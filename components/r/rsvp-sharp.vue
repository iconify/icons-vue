<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nbzf5lruc"/><circle class="upu83lbfh"/><path class="o69111nsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rsvp-sharp" /></template>
<style>
.nbzf5lruc {
  d: path("M2.75 3.75h16.5v13.5H2.75zM6.5 8h8m-8 3.5H11");
}

.o69111nsa {
  d: path("m15.25 17l1.25 1.25l2.5-2.5");
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
