<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="regdjobyu"/><circle class="k5zm5ebnd"/><path class="v7sme061k"/><path class="rwt_dhxqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:public-india" /></template>
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

.k5zm5ebnd {
  cx: 24px;
  cy: 15.884px;
  r: 2.324px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.regdjobyu {
  cx: 24px;
  cy: 15.884px;
  r: 5.811px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rwt_dhxqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.351 35.534s2.618-5.81 4.649-5.81s4.649 5.81 4.649 5.81m-13.946 0c-.872 1.51 2.034 4.53 4.648 0m13.946 0c.872 1.51-2.034 4.53-4.648 0");
}

.v7sme061k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.703 35.534s5.224-10.46 9.297-10.46s9.297 10.46 9.297 10.46");
}

</style>
