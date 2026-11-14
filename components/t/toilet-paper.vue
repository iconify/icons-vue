<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sveth0vyr"/><path class="n0s37qbiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toilet-paper" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0s37qbiu {
  d: path("M8 4.5h8a5 5 0 0 1 5 5v11h-8v-6H8m0-5h.01");
}

.sveth0vyr {
  d: path("M3 9.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
