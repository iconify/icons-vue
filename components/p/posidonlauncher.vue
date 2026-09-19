<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rane0i_8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:posidonlauncher" /></template>
<style>
.rane0i_8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31 8.13V22a7 7 0 0 1-4 6.27V4.5h-6v23.81A7 7 0 0 1 17 22V8.13l-6 3.24V22a13 13 0 0 0 10 12.64v8.86h6v-8.87A13 13 0 0 0 37 22V11.37Z");
}

</style>
