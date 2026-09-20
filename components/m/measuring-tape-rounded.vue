<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sczzxuj0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:measuring-tape-rounded" /></template>
<style>
.sczzxuj0j {
  fill: currentColor;
  d: path("M13.5 20H7q-.825 0-1.412-.587T5 18v-6.5q0-3.55 2.475-6.025T13.5 3t6.025 2.475T22 11.5t-2.475 6.025T13.5 20m2.475-6.025Q17 12.95 17 11.5t-1.025-2.475T13.5 8t-2.475 1.025T10 11.5t1.025 2.475T13.5 15t2.475-1.025m-3.538-1.412Q12 12.125 12 11.5t.438-1.062T13.5 10t1.063.438T15 11.5t-.437 1.063T13.5 13t-1.062-.437M3 20q-.425 0-.712-.288T2 19v-3q0-.425.288-.712T3 15t.713.288T4 16v3q0 .425-.288.713T3 20");
}

</style>
