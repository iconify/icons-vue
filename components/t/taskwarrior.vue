<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iub2cdc_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taskwarrior" /></template>
<style>
.iub2cdc_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.75 27.1v16.4c-3.37-.87-8.12-4.58-11-7.63c1.91-4.75 2.72-8.76 1.83-15.54c-5.79-21.11 28.77-21.11 23 0c-.88 6.77-.08 10.79 1.77 15.54c-2.86 3.05-7.64 6.76-11 7.63V27.1l6.82-5l.18-2.74L24 21.13l-9.18-1.79l.18 2.74Z");
}

</style>
