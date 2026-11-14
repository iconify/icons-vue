<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic06p6f8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-fishing-zone" /></template>
<style>
.ic06p6f8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15.5q1.577-2.669 3.39-4.72m4.185-3.705Q15.296 4.248 20.5 4m0 0v7m0 0v1.5q0 .086-.008.172t-.026.169q-.016.085-.041.167t-.058.162q-.033.079-.074.155t-.088.147t-.102.138t-.116.127q-.06.061-.127.116q-.066.054-.138.102q-.071.048-.147.088q-.076.041-.155.074q-.08.033-.162.058t-.167.041q-.084.017-.169.026t-.172.008q-.397 0-.754-.171m-.813-.799Q17 12.911 17 12.5M3 20q2.5-2 5 0t5 0M3.5 3.5l17 17");
}

</style>
