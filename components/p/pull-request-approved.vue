<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c43ucacfd"/><path class="zi3l0qb3p"/><path class="jw809gbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pull-request-approved" /></template>
<style>
.c43ucacfd {
  d: path("M3.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM6 7.25v9.5M3.75 19a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11.5-8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.jw809gbmr {
  d: path("m13 3l-2 2l2 2m1.75 11l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zi3l0qb3p {
  d: path("M17.5 8.25V5H11");
}

</style>
