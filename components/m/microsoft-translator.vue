<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oqm_8lbew"/><path class="svtlinrev"/><path class="xube9sc9q"/><path class="ga6qrnb0b"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-translator" /></template>
<style>
.ga6qrnb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.701 18.758l-2.329 2.329l-2.332-2.329");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.oqm_8lbew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.315 35.636l4.142-11.144m3.97 11.177l-3.97-11.177m2.642 7.439h-5.407m14.166-18.584h12.457m-6.228-2.468v2.468m3.486 0c0 3.408-3.957 9.048-7.913 9.91");
}

.svtlinrev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.287 16.441c.392 2.35 4.466 6.268 8.09 6.816m-9.631 11.676a5.166 5.166 0 0 0 5.165-5.166v-2.575");
}

.xube9sc9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.581 29.522l2.33-2.33l2.331 2.33M19.537 13.347a5.166 5.166 0 0 0-5.166 5.165v2.575");
}

</style>
