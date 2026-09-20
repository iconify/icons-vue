<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyjhnybfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-lock" /></template>
<style>
.zyjhnybfv {
  fill: currentColor;
  d: path("M12 21L0 9q2.375-2.425 5.488-3.713T12 4t6.513 1.288T24 9l-2.475 2.475q-.575-.275-1.213-.413t-1.287-.137q-2.525 0-4.3 1.775T12.95 17q0 .65.138 1.288T13.5 19.5zm5 0q-.425 0-.712-.288T16 20v-3q0-.425.288-.712T17 16v-1q0-.825.588-1.412T19 13t1.413.588T21 15v1q.425 0 .713.288T22 17v3q0 .425-.288.713T21 21zm1-5h2v-1q0-.425-.288-.712T19 14t-.712.288T18 15z");
}

</style>
