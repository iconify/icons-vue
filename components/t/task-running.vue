<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lqpnckb6o"/><path class="wnlo0ubib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:task-running" /></template>
<style>
.lqpnckb6o {
  d: path("m12 2.5l8.227 4.75v9.5L12 21.5l-8.227-4.75v-9.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnlo0ubib {
  d: path("M12 7.75a4.25 4.25 0 0 1 3.256 1.518m.425 4.857a4.25 4.25 0 0 1-2.943 2.06m-4.419-2.06a4.25 4.25 0 0 1-.313-3.579");
}

</style>
