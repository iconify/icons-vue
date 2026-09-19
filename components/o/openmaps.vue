<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0qiuubas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openmaps" /></template>
<style>
.n0qiuubas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.81 5.5L6.25 9.45a1 1 0 0 0-.74 1v31a1 1 0 0 0 1 1h.33l11-4.26l12.3 4.31l11.56-4a1 1 0 0 0 .74-1v-31a1 1 0 0 0-1-1l-.33.07l-11 4.19Zm12.31 4.31V42.5m-12.27-4.31V5.6");
}

</style>
