<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bg1zo0ebg"/><path class="toazbmqwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tapet" /></template>
<style>
.bg1zo0ebg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4m-29 12.01h6.429m-3.214 9.705V17.51m24.511 1.274v8.431m-1.273-6.43H38.5");
}

.toazbmqwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.152 24.789a2.426 2.426 0 0 1-4.852 0V23.21a2.426 2.426 0 0 1 4.852 0m0 4.005v-6.43m14.154 5.205a2.426 2.426 0 0 1-4.534-1.202v-1.577a2.426 2.426 0 0 1 4.852 0V24h-4.852m-7.16.789a2.426 2.426 0 0 0 4.852 0V23.21a2.426 2.426 0 0 0-4.852 0m0-2.425v9.705");
}

</style>
