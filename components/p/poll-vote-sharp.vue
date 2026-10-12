<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><circle class="w7-glrb_d"/><path class="p0wu51vaj"/><circle class="v_u09sohe"/><path class="dlqe2221s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:poll-vote-sharp" /></template>
<style>
.dlqe2221s {
  d: path("M11.5 15.5h4");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.p0wu51vaj {
  d: path("M11.5 8.5H17");
}

.v_u09sohe {
  cx: 7.75px;
  cy: 15.5px;
  r: 1.75px;
}

.w7-glrb_d {
  cx: 7.75px;
  cy: 8.5px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
