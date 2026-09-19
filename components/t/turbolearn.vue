<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gib-2915u"/><path class="gb3gmcctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:turbolearn" /></template>
<style>
.gb3gmcctb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.541 20.222c2.591-3.887 7.04-12.982 2.79-13.795M13.39 26.733c1.232 1.716 3.554 2.267 5.988 2.364");
}

.gib-2915u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.671 38.533c1.75 3.844 9.842-2.748 11.66-.626c.53.617-.453 2.375-.453 2.375s7.666-3.066 9.48-1.597s-.065 5.333 3.692 3.174M10.605 38.62c-2.197-.824 1.75-9.555 2.786-11.887S23.447 2.386 28.808 5.873c3.984 2.592-6.908 19.37-9.43 23.224s-6.7 10.3-8.773 9.523");
}

</style>
