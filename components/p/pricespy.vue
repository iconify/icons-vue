<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><circle class="svlekqb2n"/><circle class="tbm68bcwo"/><path class="spx79sb0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pricespy" /></template>
<style>
.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.spx79sb0q {
  d: path("M11.34 32.946A15.43 15.43 0 0 1 8.5 24a15.43 15.43 0 0 1 2.865-8.98L9.4 12.976a18.4 18.4 0 0 1 3.637-3.623l2.031 1.977A15.43 15.43 0 0 1 24 8.5a15.43 15.43 0 0 1 8.913 2.817l2.07-1.949a18.4 18.4 0 0 1 3.61 3.598l-1.972 2.033a15.43 15.43 0 0 1 2.879 9a15.43 15.43 0 0 1-2.822 8.92l1.954 2.063a18.4 18.4 0 0 1-3.636 3.64l-1.998-2A15.43 15.43 0 0 1 24 39.5c-3.346 0-6.445-1.06-8.978-2.864l-2.06 1.954a18.4 18.4 0 0 1-3.568-3.573z");
}

.svlekqb2n {
  cx: 24px;
  cy: 24px;
  r: 10.5px;
}

.tbm68bcwo {
  cx: 24px;
  cy: 24px;
  r: 5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
