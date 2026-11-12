<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o38rzofgs"/><path class="gtjvk1txz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skip-previous-broken" /></template>
<style>
.gtjvk1txz {
  d: path("M2 5V12M2 16V19");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o38rzofgs {
  d: path("M22 11L22 18.9671C22 21.2763 19.8658 22.736 18.1292 21.6145L7.34016 14.6474C5.55328 13.4935 5.55328 10.5065 7.34015 9.35258L18.1292 2.38548C19.8658 1.26402 22 2.72368 22 5.03289V7");
}

</style>
