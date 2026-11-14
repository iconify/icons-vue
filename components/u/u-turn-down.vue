<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obdhrqbem"/><path class="zvrid2nje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:u-turn-down" /></template>
<style>
.obdhrqbem {
  d: path("M4.5 5.5h10a5 5 0 0 1 0 10h-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvrid2nje {
  d: path("m11.5 18.5l-3-3l3-3");
}

</style>
