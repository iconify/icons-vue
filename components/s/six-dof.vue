<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nae4uob8z"/><path class="qc9cbqauu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:six-dof" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nae4uob8z {
  d: path("M9.5 10.5v-8M7.25 4.75L9.5 2.5l2.25 2.25M9.5 10.5h9m-2.25-2.25l2.25 2.25l-2.25 2.25M9.5 10.5L3 17m0-3.5V17h3.5m12-1.25a2.75 2.75 0 1 1-2.75 2.75");
}

.qc9cbqauu {
  d: path("m14.5 19.75l1.25-1.25L17 19.75");
}

</style>
