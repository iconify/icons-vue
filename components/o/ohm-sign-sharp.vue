<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucb-mqbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ohm-sign-sharp" /></template>
<style>
.ucb-mqbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13.25H9v-1.5a4.75 4.75 0 1 1 6 0v1.5h2.5m-14.75 5.5h3l1.5-2l2 3.75l2-3.75l2 3.75l2-3.75l1.5 2h3");
}

</style>
