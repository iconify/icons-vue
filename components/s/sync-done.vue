<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vkrpgmbcp"/><path class="eiko52b1a"/><path class="eqg9a_s-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sync-done" /></template>
<style>
.eiko52b1a {
  d: path("M8 18.928A8 8 0 0 1 12 4m10 5.75L20 12l-2-2.25");
}

.eqg9a_s-p {
  d: path("m9 12.25l2.25 2.25L15 10.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkrpgmbcp {
  d: path("M16 5.072A8 8 0 0 1 12 20M2 14.25L4 12l2 2.25");
}

</style>
