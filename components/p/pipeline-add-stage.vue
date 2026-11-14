<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-frd7blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pipeline-add-stage" /></template>
<style>
.u-frd7blp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3zA2.25 2.25 0 0 1 7 5.25v13.5A2.25 2.25 0 0 1 4.75 21a2.25 2.25 0 0 1-2.25-2.25V5.25A2.25 2.25 0 0 1 4.75 3M12 3za2.25 2.25 0 0 1 2.25 2.25v6.5A2.25 2.25 0 0 1 12 14a2.25 2.25 0 0 1-2.25-2.25v-6.5A2.25 2.25 0 0 1 12 3m7.25 0za2.25 2.25 0 0 1 2.25 2.25v2.5A2.25 2.25 0 0 1 19.25 10A2.25 2.25 0 0 1 17 7.75v-2.5A2.25 2.25 0 0 1 19.25 3M18 15v6m-3-3h6");
}

</style>
