<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rbj9sacvm"/><path class="r-91z-pnj"/><path class="caadc8bnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retaining-wall-sharp" /></template>
<style>
.caadc8bnt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 10.75h.01m2.49 1.5h.01");
}

.r-91z-pnj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 7h3.875l4.125 1.5V15h-8Z");
}

.rbj9sacvm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h2.25v15h11v3.25H2.75V18h4.5V3z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
