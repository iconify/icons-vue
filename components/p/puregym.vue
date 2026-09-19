<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p37v6vqmj"/><circle class="pa_qjch1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:puregym" /></template>
<style>
.p37v6vqmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.178 4.5h7.645c5.54 0 10 4.46 10 10v6.399c0 5.892-3.109 5.543-6.788 6.57s-6.79 3.283-8.09 7.19C21.67 38.493 20.812 43.5 16.13 43.5s-5.953-3.697-5.953-8.323V14.5c0-5.54 4.46-10 10-10z");
}

.pa_qjch1b {
  cx: 31.608px;
  cy: 37.1px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
