<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diq82sbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scales-justice" /></template>
<style>
.diq82sbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25v18M5.75 7.5l12.5-2m-12.5 2L3.25 14m2.5-6.5l2.5 6.5m10-8.5l-2.5 6m2.5-6l2.5 6m-18 3h6a3 3 0 0 1-6 0m12.5-2.5h6a3 3 0 0 1-6 0m-7.5 9.25h8.5");
}

</style>
