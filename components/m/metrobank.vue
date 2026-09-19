<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_uizsnjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metrobank" /></template>
<style>
.l_uizsnjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.07 40.702l3.575-33.403H9.23L5.5 40.702Zm10.824 0l-6.144-13.65l1.747-16.194l4.435 9.26l5.85-12.82h7.057L42.5 40.701h-9.011L31.72 27.16Z");
}

</style>
