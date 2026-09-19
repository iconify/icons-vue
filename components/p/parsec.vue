<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uoxqd6bao"/><path class="dtzzkcccc"/><path class="to2mt92hp"/><path class="z7ug12b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:parsec" /></template>
<style>
.dtzzkcccc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.88 8.69c0-1.905 1.913-1.905 3.19-1.27l15.948 8.893c2.551 1.27 2.551 1.905 2.551 5.716v19.054c0 1.906-1.914 3.176-3.827 1.906L13.155 32.826c-1.276-.635-1.276-1.905-1.276-3.81z");
}

.to2mt92hp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.955 17.33v9.145l5.597 3.269");
}

.uoxqd6bao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.26 15.678V28.38l8.293 5.08v-12.7z");
}

.z7ug12b_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.431 7.173V6.15c0-1.905 1.914-1.905 3.19-1.27l15.948 8.892c2.552 1.27 2.552 1.905 2.552 5.716v19.055c0 1.491-1.173 2.594-2.6 2.393");
}

</style>
