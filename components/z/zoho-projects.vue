<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jf9nz_ocv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-projects" /></template>
<style>
.jf9nz_ocv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.79 12.72L21.55 41.78L3.79 28.79l4.87-6.66l11.1 8.12l16.37-22.4l3.312 2.45l.342.223l-19.167 25.533l-11.687-8.43");
}

</style>
