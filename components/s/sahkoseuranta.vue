<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k0jinzoyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sahkoseuranta" /></template>
<style>
.k0jinzoyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.583 4.69l-11.42 25.357l9.725-1.47L14.245 43.5h7.468c0-.845 13.213-23.111 16.124-25.503c-4.49 0-12.263 1.518-12.263 1.518c2.85-5.325 6.73-10.02 10.119-15.015H21.684z");
}

</style>
