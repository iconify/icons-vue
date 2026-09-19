<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j87swicgp"/><circle class="s9j0sdb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:muni" /></template>
<style>
.j87swicgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.125 24.375v9.75m26-16.25v9.75a6.5 6.5 0 1 1-13 0v-3.25a6.5 6.5 0 1 0-13 0a6.5 6.5 0 1 0-13 0v9.75");
}

.s9j0sdb8z {
  cx: 43.125px;
  cy: 14.625px;
  r: 0.75px;
  fill: currentColor;
}

</style>
