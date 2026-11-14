<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p3cpd_bdv"/><path class="bny2psisg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:store-event" /></template>
<style>
.bny2psisg {
  d: path("m4.25 11.75l3 1l-1.75 3.5ZM8.75 13l3 .5L10 17.25Zm3.5.5l3-.5L14 17.25Zm4.5-.75l3-1l-1.25 4.5ZM3 11v10.5M21 11v10.5");
}

.p3cpd_bdv {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M3 11c5 3 13 3 18 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
