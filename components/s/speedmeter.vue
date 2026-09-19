<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="npt1ucb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:speedmeter" /></template>
<style>
.npt1ucb-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.13 5.52L29.2 22.81l4.05-3.47l7.9 4.39l-8.15.62v3.13l-26.18 15L19.34 31L9.28 8.9l7 5.76l-2.16-9.14ZM29.2 22.81l-9.86 8.18m13.7-6.64l-6.28.49");
}

</style>
