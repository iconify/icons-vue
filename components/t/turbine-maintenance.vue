<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9j_hi1pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:turbine-maintenance" /></template>
<style>
.k9j_hi1pw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5v-6m0 6l-5.25 3m5.25-3l5.25 3m-5.25-3v13m-3 0h6m8-7.5a2.5 2.5 0 1 0 2 2m-7 5l2.75-2.75");
}

</style>
