<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="tqz_sbb6t"/><circle class="rvcbqobfx"/><path class="hqvy4jiig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wisetimer" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hqvy4jiig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 26.495v7.063M37.91 24H26.63m-4.677-2.047l-8.744-8.744");
}

.rvcbqobfx {
  cx: 24px;
  cy: 24px;
  r: 2.498px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tqz_sbb6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.013v-3.362m-10.496.549l1.68-2.911M5.82 34.517l2.912-1.68m-5.724-8.816H6.37m-.55-10.496l2.912 1.68m4.772-9.364l1.68 2.912M24 3.029v3.362m10.496-.55l-1.68 2.912m9.363 4.772l-2.911 1.68m5.724 8.816H41.63m.549 10.496l-2.911-1.68M34.496 42.2l-1.68-2.911");
}

</style>
