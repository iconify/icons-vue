<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pcw_l4b7d"/><path class="rntq0_x6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quikshort" /></template>
<style>
.pcw_l4b7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.26 12.243C2.593 17.049-4.19 42.676 18.123 42.07");
}

.rntq0_x6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.646 5.92l10.859 5.782l-2.978 12.34z");
}

</style>
