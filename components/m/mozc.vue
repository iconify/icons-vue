<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="obmgwib_r"/><circle class="vlhghzf_h"/><path class="w3rlvibwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mozc" /></template>
<style>
.obmgwib_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.399 38.03c-8.521 3.532-18.293-.511-21.825-9.032s.51-18.293 9.031-21.826c8.521-3.532 18.293.511 21.826 9.032a16.7 16.7 0 0 1-3.04 17.597");
}

.vlhghzf_h {
  cx: 34.992px;
  cy: 37.852px;
  r: 4.253px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.w3rlvibwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.477 15.017h16.44m-10.29-2.819v9.9c0 2.143.332 4.735 1.977 6.12m3.803-8.53c-2.014 6.955-4.774 11.755-8.501 11.755c-2.406 0-4.064-1.9-4.064-4.19c0-4.077 4.674-7.809 10.662-7.823c3.977-.01 7.232 2.931 7.232 6.675c0 3.48-2.83 5.494-7.12 6.303");
}

</style>
