<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t926k4bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mon-espace-sant" /></template>
<style>
.t926k4bac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.508 42.5V12.363c.207-7.678 11.259-10.437 13.98 0v12.81m0-12.81c1.188-8.743 13.784-9.55 14.223 0v12.81l8.78.01");
}

</style>
