<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3ok9b3ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-report" /></template>
<style>
.n3ok9b3ix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12h.5A1.75 1.75 0 0 1 7 13.75v5.5A1.75 1.75 0 0 1 5.25 21h-.5A1.75 1.75 0 0 1 3 19.25v-5.5A1.75 1.75 0 0 1 4.75 12m7-8h.5A1.75 1.75 0 0 1 14 5.75v13.5A1.75 1.75 0 0 1 12.25 21h-.5A1.75 1.75 0 0 1 10 19.25V5.75A1.75 1.75 0 0 1 11.75 4m7 4h.5A1.75 1.75 0 0 1 21 9.75v9.5A1.75 1.75 0 0 1 19.25 21h-.5A1.75 1.75 0 0 1 17 19.25v-9.5A1.75 1.75 0 0 1 18.75 8");
}

</style>
