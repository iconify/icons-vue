<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><circle class="v90gbqbox"/><circle class="h_tsn8bxt"/><path class="v3fh7p3zu"/><path class="aljsoyb4u"/><path class="l46bgqtbq"/><path class="binvscbqf"/><path class="uumj9dwvi"/><path class="q5uwqn6cw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-line-duotone" /></template>
<style>
.aljsoyb4u {
  d: path("M14 12L18 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.binvscbqf {
  d: path("M13 10.2681L15 6.80403");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l46bgqtbq {
  d: path("M9 17.1962L11 13.7321");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.q5uwqn6cw {
  d: path("M11 10.2681L9 6.80396");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.uumj9dwvi {
  d: path("M15 17.1963L13 13.7322");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v3fh7p3zu {
  d: path("M6 12L10 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v90gbqbox {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

</style>
