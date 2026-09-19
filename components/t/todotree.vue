<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shj_34byq"/><g class="y9tr6bcfx"><path class="r_llmcbex"/><path class="gme4llbva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:todotree" /></template>
<style>
.gme4llbva {
  d: path("M38.477 23.727h-3.925V31.4h7.674v-7.674");
}

.r_llmcbex {
  d: path("M20.848 27.564v10.963h13.705m1.917-12.334l1.645 2.866l4.385-9.443");
}

.shj_34byq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.011 12.763h7.674v7.674h-7.674zM5.5 5.637V16.6h11.511m3.837 3.838v7.126h13.705m0 7.124h7.674v7.674h-7.674z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
