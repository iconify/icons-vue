<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eir5imb_g"/><path class="br0zsyb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:natwest" /></template>
<style>
.br0zsyb9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.758 30.971H5.5l5.184-9.017h10.259zm0 0H5.5l5.184 9.018h10.259zM24 27.272l-3.057-5.318m0 18.035L24 34.67m7.429-12.716h5.887l-5.184 9.017H21.873l2.832-4.925m7.427 4.925H21.873l5.184 9.018h10.259zm5.184 9.018l5.184-9.018l-5.184-9.017");
}

.eir5imb_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.892 17.029H13.634l5.184-9.018h10.258zm-.597 9.017h5.781l-5.184-9.017H13.634l2.831 4.925m12.611 4.092l5.185-9.017l-5.185-9.018");
}

</style>
