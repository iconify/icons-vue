<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="biqmlmb-q"/><g class="y9tr6bcfx"><circle class="ahx04p98k"/><path class="nieoitw_r"/><circle class="uj2conbns"/><path class="swdmk4byf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:serialusbterminal" /></template>
<style>
.ahx04p98k {
  cx: 15.25px;
  cy: 23.95px;
  r: 2.16px;
}

.biqmlmb-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.87 25.92v-3.75m1.94 3.75v-3.75m1.94 3.75v-3.75m9.83 15.61V34m1.94 3.78V34m1.93 3.78V34m-3.89-20v-3.78M19.49 14v-3.78M21.43 14v-3.78m20.69 7.27l.05 13m-1.99-13v13m-1.94 2.39h4.63m-4.63-17.73h4.63m-4.63-4.93H23.37v5.86L9.68 18.47v11.06l13.69 2.39v5.86h14.87Z");
}

.nieoitw_r {
  d: path("M22.18 24a1.4 1.4 0 0 1 .79.3l2.7 2.86h0a2.44 2.44 0 0 0 1.56.69h2M17.71 24h16m.12 1.43L36.39 24l-2.56-1.48Z");
}

.swdmk4byf {
  d: path("M26.07 20.1H24a2.4 2.4 0 0 0-1.56.69l-2.71 2.86a1.37 1.37 0 0 1-.79.3m12.96 5.13h-2.56v-2.57h2.56Z");
}

.uj2conbns {
  cx: 27.37px;
  cy: 20.1px;
  r: 1.27px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
