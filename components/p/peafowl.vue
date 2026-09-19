<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6mt9s8vw"/><path class="h8rxweb4w"/><path class="gyz22gbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:peafowl" /></template>
<style>
.f6mt9s8vw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.778 34.283s-7.416-3.71-12.823-14.418c-2.597 9.807-.689 16.115 8.959 21.946c4.93-3.764 3.392-7.421 4.4-13.411c1.007-5.99 4.081-7.66 5.75-7.66s2.943.345 4.533 4.532c-.901-1.219-4.824-2.544-4.824 1.22s5.99 11.078 2.28 16.008c9.17-4.135 15.107-11.238 10.39-22.635C36.102 28.241 29.02 33.29 29.02 33.29");
}

.gyz22gbfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.709 11.732S19.829 7.832 24 5.5c2.773 2.12 5.656 5.613 5.656 5.613");
}

.h8rxweb4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.044 21.885c.189-5.03 4.053-9.494 8.877-13.576c-.954 9.277 1.378 16.115 3.392 20.09m17.229-6.546c-1.589-6.599-4.521-10.045-9.118-13.544c.954 8.217-.838 12.66-.838 12.66");
}

</style>
