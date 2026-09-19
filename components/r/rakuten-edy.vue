<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kc53_dbdo"/><path class="cti6oxg3k"/><path class="zg7sfcapo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-edy" /></template>
<style>
.cti6oxg3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.823 37.001a6.999 6.999 0 1 1-13.998 0a6.999 6.999 0 0 1 13.998 0m-8.999 0h2.61");
}

.kc53_dbdo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.31 30.552V4h8.873c5.119 0 9.214 3.983 9.214 8.961s-4.095 8.961-9.214 8.961H12.31m9.206-.007l8.54 8.305m-.141 7.69L9.449 41l-5.272-4.687h25.716");
}

.zg7sfcapo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.824 41.001h-4v-8h4");
}

</style>
