<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwz_1dwde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:traffic-source" /></template>
<style>
.mwz_1dwde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 9h7.5a1.75 1.75 0 0 1 1.75 1.75v9a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-9A1.75 1.75 0 0 1 12.25 9m-1.75 3.5h11m-8.75-1.75h.01m2.24 0h.01M13 15.5h6m-6 3h4m-14.5-2h5.75m-2-2l2 2l-2 2M16 2.5V7m-2-2l2 2l2-2M3 3l5.25 5.25m-2.75 0h2.75V5.5");
}

</style>
