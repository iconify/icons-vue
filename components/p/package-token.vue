<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rhug6qnyc"/><path class="k2i33dbyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:package-token" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2i33dbyv {
  d: path("m2.5 6.5l7.75 4l7.75-4m-7.75 4V19m4.25.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3-1.25l3.75-3.75m-1.5 1.5l1.5 1.5");
}

.rhug6qnyc {
  d: path("m12.058 18.067l-1.12.578q-.16.082-.334.125t-.354.042t-.354-.042q-.174-.043-.334-.125l-6.25-3.226q-.091-.047-.175-.106t-.16-.129q-.075-.071-.14-.15q-.065-.08-.118-.168q-.053-.087-.094-.182q-.041-.094-.069-.193t-.042-.2q-.014-.102-.014-.205V7.414q0-.103.014-.205t.042-.2q.028-.099.069-.193q.041-.095.094-.182q.053-.088.118-.168q.065-.079.14-.15t.16-.129q.084-.059.175-.106l6.25-3.226q.16-.082.334-.125t.354-.042q.18 0 .354.042t.334.125l6.25 3.226q.091.047.175.106t.16.129q.075.071.14.15q.065.08.118.168q.053.087.094.182q.041.094.069.193t.042.2t.014.205v6.606");
}

</style>
