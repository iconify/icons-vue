<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vnvos_bib"/><path class="vmvvs_b5h"/><path class="lr8gldu6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-sick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr8gldu6s {
  d: path("M17.75 5.5c2 1.5 2 4.5.5 6.25c-1.75-1.5-1.75-4.5-.5-6.25M12 9c-2.5-1-5.5-.25-6.5 2.5C8.5 12 11 11 12 9");
}

.vmvvs_b5h {
  d: path("M12 14.5v-7c0-3.5 4-4.5 5.75-2");
}

.vnvos_bib {
  d: path("M9.09 14.5h5.82a1.75 1.75 0 0 1 1.723 2.058l-.625 3.5a1.75 1.75 0 0 1-1.723 1.442h-4.57a1.75 1.75 0 0 1-1.723-1.442l-.625-3.5A1.75 1.75 0 0 1 9.09 14.5");
}

</style>
